# 23/12/2024 - CURSO DE STREAMILIT - DAY 1

## 1 - A linguagem Python

### O que é Python?
Python é uma linguagem de programação de alto nível, interpretada e de propósito geral, criada por Guido van Rossum e lançada pela primeira vez em 1991. Ela foi projetada para ser simples e fácil de aprender, com uma sintaxe clara que favorece a legibilidade do código. Python é amplamente utilizada em diversas áreas, incluindo desenvolvimento web, automação, análise de dados, inteligência artificial, e muito mais.

### Características de Python

### a. Simplicidade e Legibilidade
Python tem uma sintaxe simples e limpa, que lembra o pseudocódigo, tornando-a ideal tanto para iniciantes quanto para desenvolvedores experientes. A linguagem promove a legibilidade, o que facilita a manutenção do código.

### b. Interpretada
Python é uma linguagem interpretada, o que significa que o código é executado linha por linha, sem a necessidade de compilação prévia. Isso facilita a depuração e o desenvolvimento rápido.

### c. Multiparadigma
Python suporta múltiplos paradigmas de programação, como:
- **Programação Procedural**: baseada em funções.
- **Programação Orientada a Objetos (POO)**: com suporte completo a classes e objetos.
- **Programação Funcional**: permitindo o uso de funções como objetos de primeira classe.

### d. Linguagem Dinamicamente Tipada
Em Python, o tipo das variáveis é determinado automaticamente durante a execução, o que reduz a necessidade de declarar tipos explicitamente. Por exemplo:

```python
x = 10       # Inteiro
x = "Python" # Agora x é uma strin`
```

### e. Biblioteca Padrão Extensa
Python possui uma vasta biblioteca padrão ("batteries included"), que oferece funcionalidades para manipulação de arquivos, expressões regulares, interfaces gráficas, redes, web scraping, e muito mais.

### f. Portabilidade
Python é multiplataforma, ou seja, o código escrito em Python pode ser executado em diferentes sistemas operacionais (Windows, macOS, Linux) sem modificações significativas.

### g. Comunidade Ativa
Python possui uma comunidade global enorme e muito ativa, o que significa que há uma vasta quantidade de documentação, tutoriais, fóruns de suporte e bibliotecas de terceiros para praticamente qualquer tarefa.

### h. Suporte a Integração
Python pode ser facilmente integrado com outras linguagens, como C, C++ e Java. Além disso, é possível utilizá-lo em conjunto com tecnologias como .NET, através de bibliotecas específicas.

### i. Gerenciamento Automático de Memória
Python tem um gerenciamento automático de memória, utilizando coleta de lixo para liberar a memória que não está mais sendo utilizada, o que simplifica o processo de programação.

### j. Aplicações de Python
Python é amplamente usado em diversas áreas:

- **Desenvolvimento Web:** Frameworks como Django e Flask.
- **Ciência de Dados:** Bibliotecas como Pandas, NumPy e Matplotlib.
- **Inteligência Artificial e Machine Learning:** Bibliotecas como TensorFlow, Keras e Scikit-learn.
- **Automação de Tarefas:** Scripts para automação de processos e tarefas administrativas.
- **Desenvolvimento de Jogos:** Bibliotecas como Pygame.

## 2 - Instalação da IDE VScode

- (https://code.visualstudio.com/download/)

## 3 - Instalação do Python

### Passo 1: Baixar o Instalador

**No Windows:**

1. Acesse o site oficial do Python: [python.org/downloads](https://www.python.org/downloads/)

2. Baixe a versão mais recente do Python para Windows (recomendado: **Python 3.x**).

### Passo 2: Executar o Instalador

1. Execute o instalador baixado (`python-3.x.x.exe`).
2. Marque a opção **"Add Python to PATH"** antes de clicar em **"Install Now"**.
3. O Python será instalado automaticamente. Isso inclui o `pip`, o gerenciador de pacotes do Python.

### Passo 3: Verificar a Instalação

Após a instalação, abra o **Prompt de Comando** e digite o seguinte comando para verificar se o Python foi instalado corretamente:

```bash
python --version
```

**No Linux:**

- sudo apt update
- sudo apt install python3

## 4 - Primeiro Programa

```python
# Aprendendo Python
print("Olá Mundo")
print("Aprendendo a Linguagem Python")
"""
    Python é muito
    divertido
"""
```
# 24/12/2024 - CURSO DE STREAMILIT - DAY 2

## 5 - Tipos de dados

## Regras para criar variáveis em Python

As regras para criar variáveis em Python são:

1. O nome da variável deve começar com uma letra ou um underscore (`_`).
2. O nome da variável pode conter letras, números e underscores.
3. O nome da variável **não pode** começar com um número.
4. O nome da variável **não pode** conter espaços ou caracteres especiais.
5. O nome da variável **não pode** ser uma palavra reservada do Python, como `if`, `for`, `print`, etc.
6. Python diferencia maiúsculas de minúsculas, portanto `variavel` e `Variavel` seriam consideradas variáveis diferentes.

## Criando uma variável

Para criar uma variável, basta atribuir um valor a ela usando o sinal de igual (`=`). Por exemplo: **nome = 'maria'**

```python
# Pythonflix
name = "Top Gun Maverick"
yearLaunch = 2023
noteMovie = 9.5
planIncluded = False

print(name)
print(yearLaunch)

print(type(name))
print(type(yearLaunch))
print(type(noteMovie))
print(type(planIncluded))

```
# Resumo dos Tipos de Dados em Python

Python possui diversos tipos de dados embutidos que são usados para armazenar diferentes tipos de informações. Aqui estão os principais:

## Tipos Numéricos

a. **int** (inteiros):
   - Números inteiros, positivos ou negativos, sem casas decimais.
   - Exemplo: `a = 5`, `b = -3`

b. **float** (ponto flutuante):
   - Números com casas decimais.
   - Exemplo: `c = 3.14`, `d = -0.99`

c. **complex** (números complexos):
   - Números no formato `a + bj`, onde `a` é a parte real e `b` a parte imaginária.
   - Exemplo: `z = 2 + 3j`

## Tipos de Sequência

a. **str** (strings):
   - Cadeias de texto, entre aspas simples ou duplas.
   - Exemplo: `nome = "Maria"`, `cidade = 'São Paulo'`

b. **list** (listas):
   - Coleção ordenada e mutável de itens, que podem ser de tipos diferentes.
   - Exemplo: `frutas = ["maçã", "banana", "laranja"]`

c. **tuple** (tuplas):
   - Coleção ordenada e imutável de itens.
   - Exemplo: `cores = ("vermelho", "azul", "verde")`

d. **range**:
   - Representa uma sequência de números, normalmente usado em laços.
   - Exemplo: `r = range(0, 10)`

## Tipos de Mapeamento

a. **dict** (dicionário):
   - Coleção desordenada de pares chave-valor, mutável.
   - Exemplo: `pessoa = {"nome": "Ana", "idade": 30}`

## Tipos de Conjuntos

a. **set** (conjunto):
   - Coleção desordenada e não indexada de itens únicos.
   - Exemplo: `letras = {"a", "b", "c"}`

b. **frozenset**:
   - Igual ao `set`, mas imutável.
   - Exemplo: `fset = frozenset(["a", "b", "c"])`

## Tipos Booleanos

a. **bool** (booleano):
   - Representa os valores lógicos `True` e `False`.
   - Exemplo: `verdadeiro = True`, `falso = False`

## Tipos Binários

a. **bytes**:
   - Sequência imutável de números inteiros de 0 a 255.
   - Exemplo: `b = b"hello"`

b. **bytearray**:
   - Semelhante a `bytes`, mas mutável.
   - Exemplo: `ba = bytearray(5)`

c. **memoryview**:
   - Fornece uma visão de memória de um objeto de bytes.
   - Exemplo: `mv = memoryview(b"hello")`

## Outros Tipos

a. **None**:
   - Representa a ausência de valor ou tipo.
   - Exemplo: `x = None`


## 6 - Utilizando o input

```python
# Utilizando o Input: input por padrão retorna uma string

name = input("Digite o nome do filme:\n")
yearLaunch = int(input("Digite o ano de lançamento do filme:\n")) # transformar o tipo para int
noteMovie = float(input("Digite a nota do filme:\n")) 

print(type(name))
print(type(yearLaunch))
print(type(noteMovie))
```

##  7 - Concatenando valores

```python
name = input("Digite o nome do filme:\n")
yearLaunch = int(input("Digite o ano de lançamento do filme:\n"))
noteMovie = float(input("Digite a nota do filme:\n"))

print("Dados do Filme")
print("=========================")
# Alternativa 1
# print("Nome do filme:",name)
# print("Ano de lançamento:",yearLaunch)
# print("Nota do filme:",noteMovie)

#Alternativa 2
print("Nome do Filme:", name, "\nAno de Lançamento:", yearLaunch, "\nNota do Filme:", noteMovie)

# Alternativa 3
print(f"Nome do jogo: {name}\n"
      f"Ano de lançamento: {yearLaunch}\n"
      f"Nota do filme: {noteMovie}\n"
      )

```
