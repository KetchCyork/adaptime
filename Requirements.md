## Thoughts on future state of time and expense tracking
- Often times people want to be able to submit time from various methods and they should be able to do any of the below
     - Web app
     - Mobile app
     - Slack
     - Command Line

-  Companies like Ketch need easy management and approval of time and expenses within policies that need to be flexible by client
     - Need ability to track time and dollars against budget for the person and project
     - Need ability to handle multiple layers between contractor and Ketch
         - Example is 1 person might be an employee of Ketch - in this case their time and expense once approved should go straight into our accounting system and create invoice line items for the billing period (this means we need a way to configure the invoicing periods - weekly, two weeks, monthly as well as if the bill format from the employee to Ketch that would just capture the expenses since they are paid a salary via payroll their time is billable to the client but not reimbursable to the employee (also in our accounting system)and also how that translates into the invoice format from Ketch to the client)
         - Example is 2 person might be an direct contractor of Ketch - in this case their time and expense once approved should go straight into their accounting system if they have one or generate an invoice that can be mailed to Ketch and create invoice line items for the billing period as well as into Ketch's accounting system to create a bill FROM the contractor (this means we need a way to configure the invoicing periods - weekly, two weeks, monthly as well as if the bill format from the contractor to Ketch (in our accounting system)and also how that translates into the invoice format from Ketch to the client)
         - Example is 3 person might be an indirect contractor of Ketch meaning they have 1 or more contract companies in between themselves and Ketch - in this case their time and expense once approved should go straight into their accounting system and create invoice line items for the billing period that can be sent to their contracting company or allow them to specify our solution creates an invoice that gets emailed to their contracting company along with copies of their expense reports as well as into Ketch's accounting system to create a bill FROM the contractor (this means we need a way to configure the invoicing periods - weekly, two weeks, monthly as well as if the bill format from the contractor to Ketch (in our accounting system)and also how that translates into the invoice format from Ketch to the client)
    -  Need to be able to configure for each team member the client bill rate, and the rate for each layer
         - Employee: employee cost is captured for margin calculations but when classified as an employee their time is not part of the bill to Ketch, their bill rate to client is also captured.  
         - For contractor direct to Ketch capture their bill rate to Ketch and bill rate to client
         - For contractor that is indirect to Ketch capture their bill rate to Ketch and bill rate to client - HOWEVER when they create their profile they would update their bill rate to their contracting company  (The Ketch admin folks cannot see this bill rate only the individual can see this)
         - If there are multiple layers between the contractor and Ketch we could only capture the information known
