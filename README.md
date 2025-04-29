# aulas_python
Meu desenvolvimento no conteúdo visto nas aulas de python
 
tipos primitivos:
- string, number (int/float), boolean
- operadores aritméticos (soma,subtração, divisão, porcentagem)
- operadores lógicos/comparativos
- estruturas condicionais (if/elif/else)

# operadores
## string/int/float
### Conversa sobre café
```py
name = "Luciana"
age = 30
drink = "café puro"

print("Esta é {}, ela tem {} anos e adora tomar {} pela manhã".format(name, age, drink))
```
### Contenção de Mercado
```py
valorProduto1 = 15.99
valorProduto2 = 48.50
valorProduto3 = 36.00
soma = valorProduto1 + valorProduto2 + valorProduto3


print("A compra total foi de R$ {:.2f}.".format(soma))
```

### Tempo de leitura
```py
bookName = "É assim que começa"
pages = 336
days = pages/10

print("Ao ler '{}', você terminará o livro em {:.0f} dias.".format(bookName, days))
```

### Lista de reprodução do dia
```py
nameList = "Para estudar"
numberMusic = 23
avgTime = 3
time = numberMusic * avgTime

print("A playlist '{}' tem {} músicas e durará cerca de {} minutos.".format(nameList, numberMusic, time))
```

### Objetivo do Passo
```py
jaDei = 1107
precisoDar = 10000
faltaDar = precisoDar - jaDei

print("Você já deu {} passos. Faltam {} passos para alcançar seu objetivo!".format(jaDei, faltaDar))
```



  
# condicionais
## if/elif/else
### Saudação Personalizada
```py
name = input("Qual o seu nome?")

if name == "Alice" or "Bob":
  print(f"Olá {name}! Que bom te ver!")
else:
  print("Olá {name}!")
```
### Par ou Ímpar

```py
number = int(input("digite um número:"))

if number % 2 == 0:
  print("Esse é um número par!")
else:
  print("Esse é um número ímpar!")
```
### Classificação dos Triângulos
```py
a = float(input("Qual a primeira medida do triângulo?"))
b = float(input("Qual a segunda medida do triângulo?"))
c = float(input("Qual a terceira medida do triângulo?"))

if a == b == c:
  print("Seu triângulo é equilátero!")

elif a == b or c == b or a == c:
  print("Seu triângulo é isósceles!")

else:
  print("Seu triângulo é escaleno!")
```
### Cálculo de Bônus por Desempenho

```py
score = int(input("Qual a sua pontuação? "))
salary = 1000

if score >= 5:
  print(f"Seu bônus é de R${salary*0.1}!")
else:
  print("Você não recebeu bônus.")
```


