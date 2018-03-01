# hello-world
# Test-random roulette number generator
from random import randint

master = []

def random_number(x):

  a = randint(0, 3)

  b = randint(0, 9)

  if a == 3 and b > 6:
    b = randint(0, 6)
    x.append(a)
    x.append(b)
    
  else:
    x.append(a)
    x.append(b)

  return x



num_gen = random_number(master)



print(num_gen)
print(" ")
print("Now, got bet that combination at the casino roulette!!!")
