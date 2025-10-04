# simpleinterest
principal = float(input("Enter the principal amount: "))
rate = float(input("Enter the annual interest rate (%): "))
time = float(input("Enter the time in years: "))

# Calculate Simple Interest
simple_interest = (principal * rate * time) / 100

# Display the result
print(f"\nSimple Interest = {simple_interest:.2f}")
