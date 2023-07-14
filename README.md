# Desafios-ci-ncia-de-dados-python-01
Sistema básico de banco feito em python

print ("BANCO TEM!")

limite = 500
saldo = 0
saque = 0
deposito = 0
numero_saque = 3
extrato = " "
recomeçar = "s"
cont = -1
sum = 0
soma = 0
while recomeçar == "s":
     
     menu = print ("\nMENU PRINCIPAL\n\nSAQUE    [s]\nDEPOSITO [d]\nEXTRATO  [e]")
     
     começo = str(input ("\nPor favor digite a opção desejada: "))
     cont += +1
     soma = deposito - saque
     
     
     if começo == "d":
          deposito = int(input("\nDigite o valor do depósito: "))
          soma += deposito
          
          print (f"Seu novo saldo é: {soma}")
          print (60*"-")
          
     if começo == "s":
          saque  = int(input ("\nDigite o valor do seu saque: "))
                  
          print (f"Seu novo saldo é: {soma - saque} ")
          print (60*"-")
          
          
     if  começo  == "e":
          print (f"\nEXTRATO DA CONTA:\n\nValores depositados 30 dias:.….. {deposito}\nValores sacados 30 dias: ........{saque}\nSaldo:.......................... {soma}")
          print (60*"-")
               
     recomeçar = str(input("\nGostaria de fazer mais uma operação? [S/N] "))
     print (60*"-")
     
else:
          print ("\nObrigado por usar nossos serviços! tenha um bom dia!")
