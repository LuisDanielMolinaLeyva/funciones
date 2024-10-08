# funciones


print("Bienvenidos a la practica de funciones")

print(" ")

def my_function():
  print("Hello from a function")

my_function()

print(" ")

def my_function(fname):
  print(fname + " Refsnes")

my_function("Emil")
my_function("Tobias")
my_function("Linus")

print(" ")

def my_function(fname, lname):
  print(fname + " " + lname)

my_function("Emil", "Refsnes")

print(" ")

def my_function(*kids):
  print("The youngest child is " + kids[2])

my_function("Emil", "Tobias", "Linus")

print(" ")

def my_function(child3, child2, child1):
  print("The youngest child is " + child3)

my_function(child1 = "Emil", child2 = "Tobias", child3 = "Linus")

print(" ")

def my_function(**kid):
  print("His last name is " + kid["lname"])

my_function(fname = "Tobias", lname = "Refsnes")

print(" ")

def my_function(country = "Norway"):
  print("I am from " + country)

my_function("Sweden")
my_function("India")
my_function()
my_function("Brazil")

print(" ")

def my_function(food):
  for x in food:
    print(x)

fruits = ["apple", "banana", "cherry"]

my_function(fruits)

print(" ")

def my_function(x):
  return 5 * x

print(my_function(3))
print(my_function(5))
print(my_function(9))

print(" ")

![image](https://github.com/user-attachments/assets/d15d468d-73f1-478b-b2e3-57549902985f)
![image](https://github.com/user-attachments/assets/58b5a10f-51ff-4963-9e94-fd0f581404f5)
![image](https://github.com/user-attachments/assets/68af1ceb-cdf8-47d9-a1cf-a220bed1f6cd)


