# Tip-Calclator
A calculator to help figure out cost per person with tip included 
cost=float(input("how much was the bill?: "))
tip=int(input("How much would you like to tip? 10, 12, 15, or 20?: "))
party=int(input("how many people are splitting the bill?: "))


total_per_person= ((tip/100)*cost+cost)/(party)

print("{:.2f}".format(total_per_person))


