### Hi there 👋

<!--
**coder-mtt3/coder-mtt3** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

####  I have various projects to show that are currently private

# working_with_datasets

This project is a demonstration of how to use pandas library to manipulate and analyze data in Python.

## Installation

Before running this project, make sure you have Python and pandas installed on your computer. If not, please download and install them from the official websites.

## Usage

To run this project, you can copy the code into a Python script or Jupyter Notebook and execute each line of code. The code reads data from a file called 'balance.txt' and performs various data manipulation and analysis tasks using pandas library.

## Code Explanation

- `import pandas as pd`: This line of code imports pandas library and assigns it to a variable `pd`.

- `df = pd.read_csv('balance.txt',sep=' ')`: This line of code reads data from a file called 'balance.txt' and stores it in a pandas DataFrame called `df`.

- `df.iloc[0:5,[2,3]]`: This line of code selects the 'Limit' and 'Rating' columns of the first five observations.

- `df[df.Cards == 4].head()`: This line of code selects the first five observations with 4 cards.

- `df.sort_values(by='Education',ascending=False).head()`: This line of code sorts the observations by 'Education' and shows users with a high education value first.

- `df.iloc[:,:]`: This line of code selects the entire dataset.

- `df.iloc[5:,5:]`: This line of code selects from the sixth to eleventh and last five observations only showing the "Age", "Education", "Gender", "Student", "Married" and "Ethnicity" columns.

- `df.iloc[:,0]`: This line of code selects only the balance column for the entire dataset.

- `df.iloc[9,:]`: This line of code selects all columns for the 10th observation. Count starts from 0.

## Credits

This project was created by Erike Akwuba.



# Finance Calculator Program

This program calculates the interest rate of an investment or bond and also calculates compound or simple interest.

## Usage

To use this program, follow these steps:

1. Run the program
2. You will be prompted to enter either "investment" or "bond"
3. If you enter "investment", you will be prompted to enter the amount of money you are depositing, the interest rate (as a percentage), the number of years you will invest, and whether you want simple or compound interest.
4. If you enter "bond", you will be prompted to enter the present value of the house, the interest rate (as a percentage), and the number of months you need to repay the loan.

After you have entered the necessary information, the program will calculate the interest rate or bond repayment for you.

## Technologies Used

This program was written in Python and utilizes the math module.

## Examples

Here are a few examples of how this program can be used:

### Example 1

User input:

Enter either 'investment' or 'bond' from the menu above to proceed: investment
What is the amount of money you are depositing? 5000
What is the interest rate? (as a percentage) 5
How many years will you invest? 10
Do you want compound or simple interest? Type 'simple' or 'compound'. compound


Program output:

The interest earned is: 3270.0040485836534


### Example 2

User input:

Enter either 'investment' or 'bond' from the menu above to proceed: bond
What is the present value of the house? 250000
What is the interest rate? (as a percentage) 4.5
How many months do you need to repay the loan? 360


Program output:

The monthly bond repayment is: 1266.7103662889853




## [minesweeper game project](https://github.com/coder-mtt3/hyperiondev_project/blob/master/minesweeper.py)


This is a Python code for the Minesweeper game. The code takes a grid as input and returns a new grid of the same dimensions, where each cell either contains the number of adjacent mines or a hash if the cell itself contains a mine.

### Function

The `minesweeper(grid)` function takes one argument:
- `grid` : a list of lists representing the input grid, where each element is either a dash (-) or a hash (#).

The function returns a new grid, which is also a list of lists, where each element is either a string representing the number of adjacent mines or a hash (#).

### How it works

The function loops through each cell in the input grid and checks whether it contains a mine or not. If the current cell is a dash, it counts the number of adjacent mines (up to 8 adjacent cells) and sets the new cell value to that number. If the current cell is a hash, it sets the new cell value to a hash. Finally, the function returns the new grid.

### Usage

To use this function, simply call `minesweeper(grid)` where `grid` is a list of lists representing the input grid.

Example usage:
```python
grid = [['-', '#', '-'], ['#', '-', '#'], ['-', '#', '-']]
new_grid = minesweeper(grid)
print(new_grid)
```















