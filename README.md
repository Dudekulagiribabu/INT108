import random
password = "ABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890abcdefghijklmnopqrstuvwxyz!@#$%^&*()_+}{:"
length_password = int(input("Enter the length of the password "))
a = "".join(random.sample(password,length_password))
print(f"your password is {a}")
