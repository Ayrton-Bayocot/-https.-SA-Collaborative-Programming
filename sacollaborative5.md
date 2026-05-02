# Input tentative grades
t1 = float(input("Enter Tentative Grade Q1: "))
t2 = float(input("Enter Tentative Grade Q2: "))
t3 = float(input("Enter Tentative Grade Q3: "))
t4 = float(input("Enter Tentative Grade Q4: "))

# Computation (Cumulative weighted average)
q1 = t1
q2 = (q1 + 2 * t2) / 3
q3 = (q2 + 2 * t3) / 3
q4 = (q3 + 2 * t4) / 3




# GET EQUIVALENT
equiv, adjectival = pshs_equivalent(q4)

print("-" * 30)
print(f"Final Grade: {q4:.2f}") # Formatted to 2 decimal places
print(f"Equivalent: {equiv}")
print(f"Adjectival Rating: {adjectival}"
print("Final Grade:", q4)
print("Equivalent:", equiv)
print("Adjectival Rating:", adjectival)
return "5.00", "FAILED"

