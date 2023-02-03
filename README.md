# AWC-Repoting-App
This is the project to practice to build an application in Salesforce

Requirements are follows:

An expense report consists of multiple line items.
For each expense report, the following need to be tracked: a. Date submitted. b. Purpose of the trip. c. The status of the report: New, Complete, Submitted, Approved, Not Approved. d. The department of the expens report owner.
Users should only be able to choose an expense report status of New or Complete.
Three types of expenses must be captured: ● Transportation ○ Type of Transportation Airline : United, Delta, British Airways, KLM Taxi : Uber, Lyft, Yellos Cab, Other Rental Car : Avis, Budget, Herz ○ Amount ○ Comments ● Accommodation ○ Vendor ○ Number of Nights ○ Nightly Rate (does not vary) ○ Amount ○ Comments ● Food ○ Meal Type: Breakfast, Lunch, Dinner ○ Amount ○ Business Guest ○ (must be included for all meals over $50) ○ Comments
Each expense line item should only show fields relevant to the type.
The following calculations need to be performed: ● Total Transportation Expenses ● Total Accommodation Expenses ● Total Food Expenses
Once an expense report is complete, it should be automatically submitted for approval by the record owner’s manager.
Once an expense report is approved,the expense report should be reassigned to the expense processing team. ● Expense Processing Team: Jacob Lerner, Ted Kim, Maya Lorrette
No one is allowed to delete an expense report except the expense team.
The expense team must be able to edit all expense reports and line items.
All users can create expense reports, but should not be able to access anyone else’s expense report.
Managers need to be able to access their subordinates’ expense reports.
