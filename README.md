# Assignment-1-Basic-Decisions-solution

Download Here: [Assignment 1: Basic Decisions solution](https://jarviscodinghub.com/assignment/assignment-1-basic-decisions-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

1.1. Write if statements with a simple condition.
1.2. Convert strings to numbers and store in integer/double data types.
1.3. Use switch statements to choose between multiple options.
1.4. Perform math operations in C#
Application Overview
You are required to create a tax calculator, which calculates both federal and state tax for an
individual. It should prompt the user for his or her gross income and calculate the applicable
federal and state income. The total tax, which is the sum of the federal and state tax liabilities is
presented back to the user.
Formulas
Net Income = Gross Income – Deduction
Federal Tax = Net Income * Federal Tax Rate
State Tax = Net Income * 2.5%
Final Tax = Federal Tax + State Tax
© 2017 Altaf Ahmad and Arizona Board of Regents
Calculating the Deduction
The deduction depends on the filing status as follows:
Filing Status Deduction ($)
Single (SG) 5,950
Married, Filing Jointly (MJ) 11,900
Married, Filing Separately( MS) 5,950
Head of Household (HH) 8,700
Other / Not specified / Error 0
Table 1. Deduction Amounts
Calculating the Federal Tax Rate
Net Income Federal Tax Rate
< $30,000 0%
$30,000 to less than $60,000 10%
$60,000 to less than $100,000 20%
$100,000 to less than $250,000 30%
>= $250,000 40%
Table 2. Federal Tax Rates
The following assumption is made for simplification: the tax rate is applied to the full income
amount, i.e. if somebody earns $100,000, with their federal tax rate at 30%, the tax will be
100,000 * 0.3 (net income * fed tax rate)
Calculating the State Tax
State Tax is applied at a constant rate of 2.5% of net income.
Calculating the Final Tax
The final tax liability is the sum of the federal and state income tax.
© 2017 Altaf Ahmad and Arizona Board of Regents
Sample Output
© 2017 Altaf Ahmad and Arizona Board of Regents
Instructions (Psuedocode)
Implement the following as a Visual C# Console application. Name your Project A1. Rename
your Program.cs class to “TaxCalculator.cs”
This following instructions are “pseudocode,” i.e., detailed instructions but not the actual code.
Psuedocode is helpful because it shows the logical progression that is needed for a program to
work – however, it is “easier” to write since it is English rather than programming language
code.
1. Declare and initialize variables for gross income, deduction, and net income. Decide what
data type is best suited for the variables.
2. Declare and initialize variables for federal tax, state tax, and income tax. Decide what
data type is best suited for the variables.
3. Declare and initialize a variable to store whether the filing status code. Decide what data
type is best suited for the variables.
4. Write the header information and welcome message to the screen.
5. Prompt the user for his/her gross income.
6. Read input and store it in your gross income variable. Remember that ReadLine() gives
you a string, not a number. So, when reading numbers, you will always have to do
a Convert.ToInt32 or Convert.ToDouble.
7. Write a list of filing status codes (see sample output). You may use multiple lines or try
to create the same format as visible in the sample output using fewer lines and more “\n”
formatting characters.
8. Read input and store it in your filing status variable.
9. Calculate the deduction based on the filing status. Decide if you should use a switch
structure or a series of if statements – one of the two is to be used and is the best “tool”
for the job.
10. Calculate the net income.
11. Calculate the federal tax based on the formula listed above. You will need to know the
federal tax rate, which is dependent on the net income. If net income is between x and y
values, then tax rate will be a. If net income is between p and q values, then tax rate is b,
and so on. Decide if you should use a switch structure or a series of if statements – one
of the two is to be used and is the best “tool” for the job.
12. Calculate the state tax.
13. Calculate the final income tax.
14. Write the stated income to the screen. Format the income using placeholders and make
sure you format it as Currency.
15. Write the final tax liability to the screen. Format the income using placeholders and make
sure you format it as Currency.
16. Put in a ReadKey as the last statement in the program!
© 2017 Altaf Ahmad and Arizona Board of Regents
Formatting
Output should be properly formatted and easy to look at. “White space” or “line breaks” should
be used to create space between lines that are logically distinct. If the user is asked to enter input,
the cursor should wait for input on the same line.
Assignment-specific Submission Instructions (if any)
All CIS 340 submissions must adhere to standards detailed in the following documents
available on Blackboard, for full credit.
• CIS 340 Assignment Submission Instructions
• CIS 340 Programming Conventions
• CIS 340 Commenting Guide
General Grading Criteria
1. Assignments will be scored out of 30 points.
2. Assignments will be on source code AND output, with the emphasis on the code.
3. Assume perfect input by user – no input validation is necessary (for now). Also, do not worry
about the program crashing due to large numbers. We will handle these issues in the second half
of the semester.
Grading Criteria Points
Input 6
Deduction Calculation & Implementation Choices 5
Tax Rate and Tax Calculations & Implementation Choices 10
Output 6
Style and Standards
CIS 340 & 345 Programming Conventions are followed
File names and project names are accurate
Class file has name, class, assignment number, and class time
written on Line 1.
White space and line breaks make reading both the source code
and output easy to look at as well as easier to read.
Line breaks are entered properly at appropriate locations.
3
© 2017 Altaf Ahmad and Arizona Board of Regents

