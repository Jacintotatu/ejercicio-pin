# ejercicio-pin
Hay que introducir un pin y hay tres oportunidades de que sea incorrecto

intentos = 0
while intentos < 3:
    password = int(input("Introduzca la contraseña: ")) 
    if password == 3895:
        print("Pin correcto")
        break
    else:
        print("Pin incorrecto")
        intentos += 1
    if intentos == 3:
        print("Estamos llamando a la policia")
