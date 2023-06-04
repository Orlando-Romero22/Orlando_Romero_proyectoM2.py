# Orlando_Romero_proyectoM2.py
Longitud de una frase

print ("Genera contraseña para consultar nomina")
palabra1 = input("Introduce la primera palabra: ")
palabra2 = input("Introduce la segunda palabra: ")
palabra3 = input("Introduce la tercera palabra: ")
#Si la palabra es de menos de 4 caracteres, se rellena con X  
if len(palabra1) < 2:
    palabra1 = "X" + palabra1
if len(palabra2) < 2:
    palabra2 = "X" + palabra2
if len(palabra3) < 2:
    palabra3 = "X" + palabra3
#Se genera la contraseña
contraseña = palabra1[0] + palabra2[0] + palabra3[0] + palabra1[1] + palabra2[1] + palabra3[1] + palabra1[2] + palabra2[2]
print("La contraseña es:", contraseña)
       
# Se solicita contraseña al usuario
# Si la contraseña es de menos de 4 caracteres informa cuántos faltan
# Si la contraseña es de más de 8 caracteres informa cuántos sobran
# Si la contraseña es correcta, informa que es correcta

if len(contraseña) < 4:
    print("contraseña muy corta, debe de tener mas de 4 caracteres")

elif len(contraseña) > 8:
    print("contraseña muy larga, debe de tener menos de 8 caracteres")

elif len(contraseña) ==8:
    print("contraseña correcta")    
