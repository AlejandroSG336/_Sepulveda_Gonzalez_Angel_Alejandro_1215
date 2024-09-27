# Sepulveda_Gonzalez_Angel_Alejandro_1215

# Solicito al usuario que ingrese un número entero no negativo

n = int(input("Ingresa un número entero no negativo: "))

# Verifico que el número sea no negativo

if n < 0:

  print("El factorial no está definido para números negativos.")
  
  else:
  
  # Inicializo la variable factorial en 1
    
  factorial = 1
    
  # Calculo el factorial utilizando un bucle

  for i in range(1, n + 1):        factorial *= i  # Multiplico el factorial actual por el número i

  # Muestro el resultado del factorial
  
  print(f"El factorial de {n} es: {factorial}")
![image](https://github.com/user-attachments/assets/78fd62e4-31db-49cf-8337-5a5c65a2a9a2)

![image](https://github.com/user-attachments/assets/f85f1091-6bae-427c-ba56-d61ca4bb2fe5)
