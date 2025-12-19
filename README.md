# Simple Interest Calculator

# Input values
principal = float(input("Enter the principal amount: "))
rate = float(input("Enter the rate of interest: "))
time = float(input("Enter the time (in years): "))

# Calculate simple interest
simple_interest = (principal * rate * time) / 100

# Display result
print("Simple Interest is:", simple_interest)
