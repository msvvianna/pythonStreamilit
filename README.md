# 14/10/2024 - CURSO DE STREAMILIT - DAY 1

## 1 - A linguagem Python

### O que é Python?
Python é uma linguagem de programação de alto nível, interpretada e de propósito geral, criada por Guido van Rossum e lançada pela primeira vez em 1991. Ela foi projetada para ser simples e fácil de aprender, com uma sintaxe clara que favorece a legibilidade do código. Python é amplamente utilizada em diversas áreas, incluindo desenvolvimento web, automação, análise de dados, inteligência artificial, e muito mais.

### Características de Python

### 1. Simplicidade e Legibilidade
Python tem uma sintaxe simples e limpa, que lembra o pseudocódigo, tornando-a ideal tanto para iniciantes quanto para desenvolvedores experientes. A linguagem promove a legibilidade, o que facilita a manutenção do código.

### 2. Interpretada
Python é uma linguagem interpretada, o que significa que o código é executado linha por linha, sem a necessidade de compilação prévia. Isso facilita a depuração e o desenvolvimento rápido.

### 3. Multiparadigma
Python suporta múltiplos paradigmas de programação, como:
- **Programação Procedural**: baseada em funções.
- **Programação Orientada a Objetos (POO)**: com suporte completo a classes e objetos.
- **Programação Funcional**: permitindo o uso de funções como objetos de primeira classe.

### 4. Linguagem Dinamicamente Tipada
Em Python, o tipo das variáveis é determinado automaticamente durante a execução, o que reduz a necessidade de declarar tipos explicitamente. Por exemplo:

```python
x = 10       # Inteiro
x = "Python" # Agora x é uma strin`
```

### 5. Biblioteca Padrão Extensa
Python possui uma vasta biblioteca padrão ("batteries included"), que oferece funcionalidades para manipulação de arquivos, expressões regulares, interfaces gráficas, redes, web scraping, e muito mais.

### 6. Portabilidade
Python é multiplataforma, ou seja, o código escrito em Python pode ser executado em diferentes sistemas operacionais (Windows, macOS, Linux) sem modificações significativas.

### 7. Comunidade Ativa
Python possui uma comunidade global enorme e muito ativa, o que significa que há uma vasta quantidade de documentação, tutoriais, fóruns de suporte e bibliotecas de terceiros para praticamente qualquer tarefa.

### 8. Suporte a Integração
Python pode ser facilmente integrado com outras linguagens, como C, C++ e Java. Além disso, é possível utilizá-lo em conjunto com tecnologias como .NET, através de bibliotecas específicas.

### 9. Gerenciamento Automático de Memória
Python tem um gerenciamento automático de memória, utilizando coleta de lixo para liberar a memória que não está mais sendo utilizada, o que simplifica o processo de programação.

### 10. Aplicações de Python
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