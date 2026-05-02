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


# Function to convert grade to PSHS equivalent and adjectival rating
def pshs_equivalent(grade):
    if grade >= 96:
        return "1.00", "EXCELLENT"
    elif grade >= 90:
        return "1.25", "VERY GOOD"
    elif grade >= 84:
        return "1.50", "VERY GOOD"
    elif grade >= 78:
        return "1.75", "GOOD"
    elif grade >= 72:
        return "2.00", "GOOD"
    elif grade >= 66:
        return "2.25", "SATISFACTORY"
    elif grade >= 60:
        return "2.50", "SATISFACTORY"
    elif grade >= 55:
        return "2.75", "FAIR"
    elif grade >= 50:
        return "3.00", "FAIR"
    elif grade >= 40:
        return "4.00", "FAILED ON CONDITION"
    else:
        return "5.00", "FAILED"


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

