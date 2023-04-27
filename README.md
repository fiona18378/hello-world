# hello-world
Генератор сложных паролей
import random

a = "abcdefghijklmnopqrstuvwxz"
b = "ABCDEFJHIJKLMNOPQRSTUVWXYZ"
c = "0123456789"
d = "{}[]()*/,_-!?"

all = a + b + c + d
length = 16
password = "".join(random.sample(all,length))
print(password)
input()
