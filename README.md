EMI Calculator

A Java-based console application that computes the Equated Monthly Installment (EMI) for a loan using the principal amount, annual interest rate, and loan tenure as inputs. The program provides an accurate EMI calculation using the standard financial formula and displays the monthly installment to the user.

Features

Takes user inputs for:

Loan Amount (Principal)

Annual Interest Rate (in percentage)

Loan Tenure (in years)

Converts annual interest rate to monthly interest rate.

Applies the EMI formula to compute the monthly installment.

Outputs EMI rounded to two decimal places.

Lightweight, clean, and beginner-friendly.

EMI Formula

The application uses the standard EMI formula:

𝐸
𝑀
𝐼
=
𝑃
×
𝑟
×
(
1
+
𝑟
)
𝑛
(
1
+
𝑟
)
𝑛
−
1
EMI=
(1+r)
n
−1
P×r×(1+r)
n
	​


Where:

P = Principal amount

r = Monthly interest rate

n = Total number of monthly installments

Example Usage

When executed, the program prompts for:

Loan amount

Annual interest rate

Tenure in years

After receiving inputs, it displays the calculated EMI.

Project Structure                       
EMI-Calculator/                                                   
│                                                                                        
├── EMICalculator.java                                         
└── README.md                                                  
                                    
License                                     

This project is open for learning and personal use.
