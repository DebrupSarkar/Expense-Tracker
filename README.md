# Problem Statement
In today’s fast-paced world, individuals need to track and manage their expenses   effectively. Your task is to build a personal expense tracker that allows users to log daily expenses, categorize them, and track spending against a monthly budget. The tracker should also be able to save and load expenses from a file for future reference. 
# Objectives:  
1. Design and implement a personal expense tracker that enables users to  
manage their expenses  
2. Allow users to categorize expenses and set monthly budgets  
3. Implement file-handling functionality to save and load expense data  
4. Create an interactive, menu-driven interface for ease of use 
# Approach: 
For the Personal Expense Tracker program, I am using data structures like dictionary to store the 
various categories of data as a single input and store it in a list. The following are the functions 
created to be used in this program: 
1. Add Expense 
  a. Prompt the user for expense details (date, category, expense, description) 
  b. Validate the input (date format, numeric input) 
  c. Append the valid expense to the list 
2. View Expense 
  a. Loop through the list of expenses and display each one 
  b. Ensure that only complete entries are shown  
3. Set and Track Budget 
  a. Allow user to input a monthly budget 
  b. Calculate total expenses by summing up the amounts 
  c. Compare total expenses against the budget and display the result 
4. Save Expense 
  a. Write all expenses to a CSV file with appropriate headers 
  b. Confirm the save action to the user 
5. Load Expense 
  a. Read from the CSV file when the program starts 
  b. Populate the expense list with the loaded data, ensuring that the amount is correctly 
  converted to a float 
6. Display Menu: 
  a. Provide a user-friendly interface for selecting actions (add, view, budget, save or exit) 
  b. Loop until the user decides to exit 
# Summary: 
The program is designed to be simple yet effective for managing personal expenses. It allows users to 
add, view, and track expenses against a set budget while providing persistent storage through CSV 
files. This modular approach ensures that each function is focused on a single task, making the 
program easier to maintain and expand in the future.
