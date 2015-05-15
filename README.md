# budget-app
Ruby Half Capstone Project

This will be a small comand-line program where the user can keep track of how much money they are spending and how much is being saved. 

#Features and Details
    (1)The user will be directed to a menu page that will have 3 choices.
        1.Add a new Budget!
        2.Update a Project!
        3.Exit
    (2)To start user will chose 1 and will be asked to inserts their weekly income(or every 2 weeks).
    (3)Then it will tell the user to inserts how much they want to spend weekly(or every 2 weeks).
    (4)The user will be able to update their budget by going to the home menu and choosing 2.
    (8)The user will be able to update or delete their data. The program will ask the user if they want to continue updating their budget or deleting it. 
        -If the user choses to continue then the program will ask the user to insert the amount they spend per purchase.
        -If the user choses to delete the budget then it will take them back to the home menu.
    (6)The app subtracts the difference. The user will be able to see the results on the same page. There will be a total that shows the difference and what is left.
    (7)What is left goes into a "savings account" in the app. 
     
     
#Adding a New Budget 
        > ./budget-app
        1. Add a Budget
        2. List all Budgets
        3. Exit
        > 1
        Name your Budget.
        > TV Budget
        What is your weekly income?
        > 700
        Great! Now how much are you planning to spend for your personal expenses?
        > 150
        Awesome your budget has been created!
        1. Add a Budget
        2. List all Budgets
        3. Exit


#Listing all Budgets when theres no Budgets
  
  
        > ./budget-app
        1. Add a Budget
        2. List all Budgets
        3. Exit
        > 2
        Sorry you no Budgets yet, why not create a Budget! :)
        1. Add a Budget
        2. List all Budgets
        3. Exit


#Listing Budgets

> ./budget-app
1. Add a Budget
2. List all Budgets
3. Exit
> 2
Select which one you would like to update or delete.
1. TV Budget
2. Car Budget
3. Exit


#Listing Budgets and updating a Budget

> ./budget-app
1. Add a Budget
2. List all Budgets
3. Exit
> 2
Select which one you would like to update or delete.
1. TV Budget
2. Car Budget
3. Exit
> 1
Would you like to update or delete?
1. Update 
2. Delete
3. Exit
> 1
What would you like to update?
1. Weekly income
2. weekly expenses
> 2
What is your new balance?
> 100
Updated Successfully!
1. Add a Budget
2. List all Budgets
3. Exit



#Listing Budgets and deleting selected Budget

> ./budget-app
1. Add a Budget
2. List all Budgets
3. Exit
> 2
Select which one you would like to update or delete.
1. TV Budget
2. Car Budget
3. Exit
> 1
Would you like to update or delete?
1. Update 
2. Delete
3. Exit
> 2
Are you sure you want DELETE your Budget?
1. Yes
2. No
> 1
Deleted Successfully       