# Exerc-cio-La-os-de-repeti-o
Imprimir um número para cada andar de um hotel de 20 andares, exceção do 13 andar.


# exemplo de código em Python que imprime todos os números de 1 a 20, exceto o número 13:

for numero in range(1, 20):
    if numero != 13:
        print(numero)
        
 # Neste exemplo, utilizamos um loop `for` para percorrer todos os números de 1 a 20. 
 # Dentro do loop, utilizamos uma estrutura de decisão `if` para verificar se o número é diferente 
 # de 13. Se for diferente, o número é impresso na tela.
 
 # mais dois exemplos de código em Python que resolvem o mesmo problema, utilizando os outros 
 # dois tipos de laços de repetição:
 
    numero = 1
while numero <= 20:
    if numero != 13:
        print(numero)
    numero += 1

 # Neste exemplo, utilizamos um laço `while` para iterar de 1 a 20. 
 # Enquanto o número for menor ou igual a 20, verificamos se ele é diferente de 13. 
 # Se for diferente, o número é impresso na tela. Em seguida, incrementamos o valor de `numero` em 1 
 # e o laço continua até que a condição seja falsa.  
 
    numero = 20
while numero >= 1:
    if numero != 13:
        print(numero)
    numero -= 1
    
 # Neste exemplo, começamos com o número 20 e decrementamos seu valor em 1 a cada iteração do loop. 
 # Enquanto o número for maior ou igual a 1, verificamos se ele é diferente de 13 e o imprimimos 
 # na tela. Em seguida, decrementamos o valor de `numero`. 
 # O loop continuará até que `numero` seja menor que 1.
