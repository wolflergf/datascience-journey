```python
# Day 2 Project: Tip Calculator

print("Welcome to the tip calculator!")
total_bill = float(input("What was the total bill? £"))
tip = float(input("How much tip would you like to give? 10, 12, or 15%? £"))
people_to_split = int(input("How many people to split the bill? "))
calc = (total_bill * (1 + (tip / 100))) / people_to_split
print(f"Each person should pay £{round(calc, 2)}")
```
