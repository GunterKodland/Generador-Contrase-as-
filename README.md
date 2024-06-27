# Generador-Contrase-as-
import _random

creadorec = []
c = ["+", "-", "/", "*", "¡", "="]
cr = int(input("añade eel numero de caracteres que tendra la contraseña"))
for i in range(cr):
    n = random.randint(0, len(c)-1)
    creadorec.append(c[n])
contraseñac = "". join(creadorec)
print("aqui esta la contraseña creada", contraseñac)
