SA1 = float(input("grade SA1: "))
SA2 = float(input("grade SA2: "))
FA1 = float(input("grade FA1: "))
FA2 = float(input("grade FA2: "))

Final_SA = ((SA1 + SA2) / 2) * .70
Final_FA = ((FA1 + FA2) / 2) * .30

current_grade = Final_SA + Final_FA
print(current_grade)

Q1 = current_grade

#second quarter
print("second quarter")

SA1q2 = float(input("grade SA1: "))
SA2q2 = float(input("grade SA2: "))
FA1q2 = float(input("grade FA1: "))
FA2q2 = float(input("grade FA2: "))

Final_SA = ((SA1q2 + SA2q2) / 2) * .70
Final_FA = ((FA1q2 + FA2q2) / 2) * .30

Q2 = Q1 + 2((Final_SA + Final_FA)) / 3
