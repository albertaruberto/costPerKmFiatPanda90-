# costPerKmFiatPanda90-
cost per km in a year for a Fiat Panda year 1997



#driving the car to work
kmToWork = 15
driveAndReturnWork = kmToWork * 2

#others km driving in one week
others = 30

#Month in one Year
oneYear = 12
totalKm = (driveAndReturnWork + others)

#Total avarage km driving in one Year
totalKmInOneYear = (totalKm * oneYear)
print(totalKmInOneYear)

#Insurance for Fiat Panda
insurance = 316

#Auto tax
autoTax = 112

#total car cost in one Year
CostPerKm = 0.39 #cost per km for Fiat Panda
totCarCost = totalKmInOneYear * CostPerKm + insurance + autoTax
print(totCarCost)






