M = int(input("Começou a fazer o Tp no minuto: "))
I = int(input("Verificar as mensagens no intervalo de: "))
L = int(input("Larry enviou mensagem no minuto: "))

#for i in range(M, 100, I  ):
 # if L  >= i:
  #  print ("Quem sabe...")
  #else:
    
var1 = M + I
var2 = M + I * 2
var3 = M + I * 3

if var1 >= L:
  print(var1)
elif var2 >= L:
  print(var2)
elif var3 >= L:
  print(var3)
else:
  print("Quem sabe...")
