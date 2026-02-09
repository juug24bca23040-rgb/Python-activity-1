# Python-activity-1

**Python Programming Tasks:**

Case Study Title:Net Salary Calculation
USN:24BCAR0520
24BCAR0497
24BCARO501
Name:TANYA BAID
SEHREEN
SHIVANI RAM 

Algorithm:
STEP 1: START
STEP 2:INPUT BASIC SAL
STEP 3:INPUT ALLOWANCES
STEP 4:INPUT DEDUCTIONS
STEP 5: CAL NET SAL USING FORMULA 
STEP 6: NET SAL=BASIC+ ALLOWANCES -DEDUCTION
STEP 7: DISPLAY NET SAL 
STEP 8: STOP.

Code:
basic=float (input(" enter basic salary:"))
allowances =float (input("enter allowances:"))
deduction=float(input("enter deduction:"))

net_sal = basic +allowances-deductions
print ("net sal=",net_sal)



Output: enter basic salary:20000
enter allowances:50000
enter deduction:3000
net sal=22000


topic :income tax slab decision 
algortithm 2
step 1: start
step 2:input income
step 3:display tax
step 4:stop

code:
income = float(input("enter your annual income:"))
if income <= 250000:
    tax = 0
elif income <= 500000:
    tax = (income - 250000) * 0.05
elif income <= 1000000:
    tax = 12500 + (income - 500000) * 0.20
else:
    tax = 112500 + (income - 1000000) * 0.30
print(“income tax =", tax)

output:
enter your annual income:400000
income tax = 7500




topic:display elements 1 t0 100
Algorithm 3
step 1:start
step2: set a counter i=1
step 3: repeat while i<_ 10
step 4: display i
step 5 :increase i by 1
step6: stop

code
for i in range (1,10):
print (i)

output
1
2
3
4
5
6
7
8
9

topic : Net Salary Calculation
Algorithm 4 
STEP 1: Start
STEP 2:Input basic salary
STEP 3:Calculate allowances and deductions
STEP 4:Compute net salary
STEP 5:Display net salary
STEP 6:Stop

CODE:
def net_sal(b):
    return b + (b*0.35) - (b*0.17)

b = float(input("enter basic sal: "))
print("Net Salary:", net_sal(b))

OUTPUT:
enter basic sal: 10000
Net Salary: 11800.0
