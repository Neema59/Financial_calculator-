# Financial Calculator

This program is a calculator for interest on investment and home loan. It allows users to calculate the amount of interest they will earn from an investment or the interest they will have to pay on a home loan.

## Usage

1. Run the program and select the operation you want to execute from the menu.

2. If you choose "investment", you will be prompted to provide the following information:
   - The amount you want to deposit (`P`).
   - The percentage of interest rate you want to apply to your investment (`r`).
   - The number of years you plan to invest (`t`).
   - Whether you want to calculate simple or compound interest.

   If you choose simple interest, the program will calculate the amount of interest you'll earn from your investment and display the result.

   If you choose compound interest, you will also be asked to enter the number of compound periods per year (`n`). The program will then calculate the amount of interest you'll earn from your investment and display the result.

3. If you choose "bond", you will be prompted to provide the following information:
   - The present value of your house (`P`).
   - The annual interest rate on the home loan.
   - The number of months you plan to repay the loan (`n`).

   The program will calculate the monthly repayment amount (`s_bond`) and display the result.

4. If you enter an invalid input, an error message will be displayed.

## Example Usage


investment - to calculate the amount of interest you'll earn from your investment
bond - to calculate the interest you'll have to pay on a home loan
Enter either 'investment' or 'bond' from the menu above to proceed : investment

How much you want to deposit? 10000
What percentage of interest rate you want to apply to your investment? 5
For how many years do you plan to invest? 3
Please enter 'simple' or 'compound' interest : compound
Please enter numbers of compound per year : 12

The amount of interest you'll earn from your investment is: 11592.75


investment - to calculate the amount of interest you'll earn from your investment
bond - to calculate the interest you'll have to pay on a home loan
Enter either 'investment' or 'bond' from the menu above to proceed : bond

Enter your house present value : 200000
Enter the interest rate : 6
For how many months do you plan to repay? 240

The monthly repayment amount for your home loan is: 1304.12


## Note

- The program assumes that all input values are valid and of the correct data type (e.g., integers for amounts, percentages, and periods).

- The interest rates should be entered as percentages, and the program will convert them to decimal form for calculations.

- For compound interest calculations, the program assumes that the interest is compounded annually unless the user specifies the number of compound periods per year.

- The program calculates the amount of interest only and does not take into account any additional fees or charges that may be associated with investments or home loans.

- This calculator is for educational and illustrative purposes only.
