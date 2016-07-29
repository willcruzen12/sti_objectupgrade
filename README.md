<<<<<<< HEAD
# Group based STI activity

You are going to write a single JavaScript file to automatically calculate employee STI (‘short term incentive’ or ‘bonus’) for a company.

They are providing you with a few sample arrays that serve as examples of how their data is currently being stored. Each array is like a row in a spreadsheet. There is also one main array named `employees` that stores each of these, much like an entire sheet of one spreadsheet.
=======
# Solo STI activity

You are going to write a single JavaScript file to automatically calculate employee STI (‘short term incentive’ or ‘bonus’) for a company.

## Overview
The company is providing you with a few sample arrays. These sample arrays contain employee data. 

Each array is like a row in a spreadsheet.
>>>>>>> 1d92f4c29c146b845f95c2474efb7527875ee49f

**Each array currently is configured in this way**:
The first item holds the employees name.
The second item has their employee number.
The third item is their annual salary.
The fourth item is their review rating.

<<<<<<< HEAD
Write a function that consumes one employee array, and returns another array that contains:
- The first item should also contain the employees name.
- The second item should contain the percentage of STI the employee is to receive.
- The third item should be the adjusted annual compensation (base annual + STI)
- The fourth item should be the employees total bonus rounded to the nearest dollar.

To calculate an individuals STI:
=======
## Instructions
1. Create an Employee constructor that is capable of holding each employee's data.
2. Convert each employee into an instance of an Employee object. 
3. Store each instance in an array called `employees`.
4. Write a function that evaluates the employees data. (Follow instructions in Evaluating Employee Data)
5. Iterate over the `employees` array and input each index of the array to your function. `console.log` the results of each iteration.

### Evaluating Employee Data
Write a function that consumes one employee object, and returns another object that contains
- employees name
- percentage of STI the employee is to receive
- adjusted annual compensation (base annual + STI)
- employee's total bonus rounded to the nearest dollar

See instructions for calculating the STI below.

## Calculating an employee's STI
>>>>>>> 1d92f4c29c146b845f95c2474efb7527875ee49f
- Those who have a rating of a 2 or below should not receive a bonus.
- Those who have a rating of a 3 should receive a base bonus of 4% of their base annual income.
- Those who have a rating of a 4 should receive a base bonus of 6% of their base annual income.
- Those who have a rating of a 5 should receive a base bonus of 10% of their base annual income.
- If they have 4 employee numbers, this means they have been with the company for longer than 15 years, 
and should receive an additional 5%.
- However, if their annual income is greater than $65,000, they should have their bonus adjusted down 1%. 
- No bonus can be above 13% total.

You may abstract out the STI calculation into a second function if you like, but this is not mandatory.
<<<<<<< HEAD

Finally, iterate over the `employees` array and input each index of the array to your first function, and `console.log` the results of each iteration. 
=======
>>>>>>> 1d92f4c29c146b845f95c2474efb7527875ee49f
