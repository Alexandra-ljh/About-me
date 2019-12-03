# About-me
Basic info about myself

print ("How much did you spend in the last Sephora sale?")
num = int(input())
total = 0.0
for i in range (num):
  print ("what"+str(i+1)+ "brand is it")
  brand = input()
  if brand.upper() == 'Tom Ford':
    total += 60
  elif brand.upper() == 'Dior':
    total += 40
  elif grade.upper() == 'Mac':
    total += 20
  else:
    total += 30
print ("Your total cost is" + str (total) + "!")
