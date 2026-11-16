# Questao 1 - Leitura e Validacao das Notas

notas = []

# for i in range(6)
nota = float(input(f"Digite a nota do aluno {i + 1}: "))

# while nota < 0 or nota > 10
print("Nota invalida! Digite uma nota entre 0 e 10.")
nota + float(input(f"Digite a nota do aluno {i + 1}: "))

notas.append(nota)

print ("\nNotas Armazenadas:")
for nota in notas:
   print(nota)

# Questao 2 - Calculo da Media e Filtragem

soma = 0

for nota in notas:
   soma += nota

media = soma / 6

acima_igual = 0

print("\nMedia geral:", media)

for nota in notas:
   if nota >= media:
    acima_igual += 1
else:
   print ("Nota abaixo da media:", nota)

print("Quantidade de alunos acima ou igual a media:", acima_igual)

#Questao 3 - Recuperacao e Atualizacao

for i in range(6):
  if notas [i] < media:
     print(f"\nAluno {i + 1} precisa fazer recuperacao.")

     nota_recuperacao = float(input("Digite a nota de recuperacao: "))

while nota_recuperacao < 0 or nota_recuperacao > 10:
        print ("Nota invalida! Digite uma nota entre 0 e 10.")
        nota_recuperacao = float(input("Digite a nota de recuperacao: "))

      #   if nota_recuperacao > notas[i]
notas[i] = nota_recuperacao

   # Exibindo o vetor atualizado

print ("\nNotas atualizadas:")
for nota in notas:
      print(nota)

# Calculando a nova media

nova_soma = 0

for nota in notas:
  nova_soma += nota

nova_media = nova_soma / 6

print ("/nNova media geral da turma:", nova_media)

QUESTÃO 2

QUESTAO 1 - REGISTRO DE TEMPERATURAS

temperaturas = []

dias = ["Domingo", "Segunda-feira", "Terca-feira",
        "Quarta-feira", "Quinta-feira", "Sexta-feira",
        "Sabado"]

for i in range(7):
    temperatura = float(input(f"Digite a temperatura de {dias[i]}: "))

    while temperatura < -10 or temperatura > 50:
        print("Temperatura invalida! Digite um valor entre -10 e 50.")
        temperatura = float(input(f"Digite novamente a temperatura de {dias[i]}: "))

    temperaturas.append(temperatura)

# Exibindo as temperaturas registradas

print("\nTemperaturas registradas:")

for i in range(7):
    print(dias[i], ":", temperaturas[i], "C")


# QUESTAO 2 - ANALISE CLIMATICA E ALERTAS

maior = temperaturas[0]
menor = temperaturas[0]
indice_maior = 0
alertas = 0

for i in range(7):

    if temperaturas[i] > maior:
        maior = temperaturas[i]
        indice_maior = i

    if temperaturas[i] < menor:
        menor = temperaturas[i]

    if temperaturas[i] > 32:
        alertas += 1

# Exibindo o relatorio climatico

print("\nRELATORIO CLIMATICO DA SEMANA")

print("Maior temperatura:", maior, "C")
print("Menor temperatura:", menor, "C")
print("Quantidade de alertas de calor:", alertas)
print("Dia da maior temperatura:", dias[indice_maior])

QUESTÃO 3

# QUESTAO 3 - SIMULACAO DE FRENTE FRIA

for i in range(7):

    if temperaturas[i] > 30.0:

        temperaturas[i] = temperaturas[i] - 4.5

        if temperaturas[i] < 15.0:
            temperaturas[i] = 15.0

# Exibindo as temperaturas atualizadas

print("\nTEMPERATURAS APOS A FRENTE FRIA")

for i in range(7):
    print(dias[i], ":", temperaturas[i], "C")

# Calculando a nova media

soma = 0

for i in range(7):
    soma += temperaturas[i]

nova_media = soma / 7

print("\nNova media de temperatura:", nova_media, "C")

