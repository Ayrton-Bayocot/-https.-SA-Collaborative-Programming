
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

