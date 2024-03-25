# Funções de Entrada e Saída

## Função de Entrada
### *Input()*
> Função que permite a entrada de valores e atribuição de valores a variaves ou constantes

A função builtin *input()* é utilizada quando queremos ler dados da entrada padrão (teclado). Ela recebe um argumento do tipo string, que é exibido para o usuário na saída padrão (tela). A função lê a entradas, converte para string e retorna o valor

```
nome = input("Guilherme")
sobrenome = input("Henrique")

print(nome, sobrenome)

>>> Guilherme Henrique

```
> Lógicamente o exemplo acima onde temos a entrada dos valores serão preenchidos ao rodar o scripting que lhe solicitará o preenchimento do nome e sobrenome.

## Função de Saída
### *Print()*
> Função que permite a exibição em tela

A função builtin *print()* é quando queremos exibir dados na saída padrão (tela). Ela recebe um argumento obrigatório do tipo varargs e 4 argumentos opcionais *(sep, end, file e flush)*. Todos os objetos convertidos para string, separados por *sep* e terminados em *end*. A string final é exibida para o usuário.

```
nome = "Guilherme"
sobrenome = "Henrique"

print(nome, sobrenome)
print(nome, sobrenome, end="...\n")
print(nome, sobrenome, sep="#")

>>> Guilherme Henrique
>>> Guilherme Henrique...
>>> Guilherme#Henrique

```

> Basicamente temos como incluír/modificar separadores e terminações de forma personalizada conforme o exemplo ainda. 

