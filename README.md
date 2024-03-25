# respostas
respostas /vaga de emprego

1)A sequência de adições seria:

1 + 2 + 3 + 4 + 5 + 6 + 7 + 8 + 9 + 10 + 11 + 12 + 13

o valor da variável SOMA será 91.

2)def verifica_fibonacci(numero):
    a, b = 0, 1
    while b < numero:
        a, b = b, a + b
    if b == numero:
        return True
    else:
        return False

def main():
    numero_informado = int(input("Digite um número para verificar se pertence à sequência de Fibonacci: "))
    if verifica_fibonacci(numero_informado):
        print(f"O número {numero_informado} pertence à sequência de Fibonacci.")
    else:
        print(f"O número {numero_informado} não pertence à sequência de Fibonacci.")

if __name__ == "__main__":
    main()

3) 
a. 9
b. 128
c. 49
d. 64
e. 13
f. 20

4)Ligue um dos interruptores e espere alguns minutos.
Desligue o interruptor e ligue imediatamente outro interruptor.
Entre na sala das lâmpadas e observe:
Se a lâmpada estiver acesa, o interruptor que você ligou inicialmente está conectado a essa lâmpada.
Se a lâmpada estiver desligada e sentir que ela está quente ao toque, então o interruptor que você ligou inicialmente está conectado a essa lâmpada.
Se a lâmpada estiver desligada e fria ao toque, então o interruptor que você não tocou está conectado a essa lâmpada.
Dessa forma, com apenas duas idas até a sala das lâmpadas, você pode determinar qual interruptor controla cada lâmpada.

5) def inverter_string(string):
    string_invertida = ""
    for i in range(len(string) - 1, -1, -1):
        string_invertida += string[i]
    return string_invertida

def main():
    # String de exemplo
    string = input("Digite uma string para inverter: ")

    # Chamando a função para inverter a string
    string_invertida = inverter_string(string)

    # Imprimindo a string invertida
    print("String invertida:", string_invertida)

if __name__ == "__main__":
    main()
