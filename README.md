def verifica_fibonacci(numero):
    a, b = 0, 1
    while b <= numero:
        if b == numero:
            return True
        a, b = b, a + b
    return False

numero = int(input("Informe um número: "))
if verifica_fibonacci(numero):
    print(f"O número {numero} pertence à sequência de Fibonacci.")
else:
    print(f"O número {numero} não pertence à sequência de Fibonacci.")

# As sequências são:
# a) 1, 3, 5, 7, 9

# b) 2, 4, 8, 16, 32, 64, 128

# c) 0, 1, 4, 9, 16, 25, 36, 49

# d) 4, 16, 36, 64, 100

# e) 1, 1, 2, 3, 5, 8, 13

# f) 2, 10, 12, 16, 17, 18, 19, 20

# Para descobrir qual interruptor controla cada lâmpada, você pode seguir este procedimento:

# Ligue o primeiro interruptor e aguarde alguns minutos.
# Desligue o primeiro interruptor e ligue o segundo interruptor.
# Entre na sala onde as lâmpadas estão e observe:
# Se a lâmpada estiver acesa, o primeiro interruptor controla essa lâmpada.
# Se a lâmpada estiver apagada e quente, o segundo interruptor controla essa lâmpada.
# Se a lâmpada estiver apagada e fria, o terceiro interruptor controla essa lâmpada.
# Aqui está um programa Python que inverte os caracteres de uma string sem usar funções prontas:
    

def inverte_string(s):
    return s[::-1]

string = input("Informe uma string: ")
print("String invertida:", inverte_string(string))
