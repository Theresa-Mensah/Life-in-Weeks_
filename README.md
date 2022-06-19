# Life-in-Weeks_

age = input("What is your current age? ")


lifedury = int(90) - int(age)

lifedurw = int(4680) - (int(age)*52)

lifedurm = int(90)*12 - (int(age)*12)

lifedurd = int(90)*365 - (int(age)*365)

message = f"You have {lifedury} years, {lifedurw} weeks, {lifedurd}  to live."

print(message)
