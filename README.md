# Exerc-cio-La-os-de-repeti-o
Imprimir um número para cada andar de um hotel de 20 andares, exceção do 13 andar.

Escreva um código que imprima todos os números exceto o número 13.
Escreva mais dois códigos que resolvam o mesmo problema, mas dessa vez usando os outros dois tipos de laços de repetição aprendidos.

Como desafio, imprima eles em ordem decrescente (20, 19, 18...)


for numero in range(1, 20):
    if numero != 13:
        print(numero)
        


    numero = 1
while numero <= 20:
    if numero != 13:
        print(numero)
    numero += 1


  
    numero = 20
while numero >= 1:
    if numero != 13:
        print(numero)
    numero -= 1
    
 
