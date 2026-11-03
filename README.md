# 🌡️ Calculadora de Temperatura em C

Projeto desenvolvido em linguagem C para realizar conversões entre três escalas de temperatura: Celsius, Fahrenheit e Kelvin.

O programa permite que o usuário escolha o tipo de conversão, informe uma temperatura e visualize o resultado diretamente no terminal.

---

## 📌 Sobre o projeto

A Calculadora de Temperatura foi desenvolvida como exercício prático de programação, com o objetivo de aplicar conceitos fundamentais da linguagem C.

O código utiliza funções independentes para cada tipo de conversão, facilitando a organização e a reutilização das operações matemáticas.

## ⚙️ Funcionalidades

O programa possui seis opções de conversão:

| Opção | Conversão | Fórmula |
|:---:|---|---|
| 01 | Celsius → Fahrenheit | (°C × 1,8) + 32 |
| 02 | Celsius → Kelvin | °C + 273,15 |
| 03 | Fahrenheit → Celsius | (°F − 32) ÷ 1,8 |
| 04 | Fahrenheit → Kelvin | (°F − 32) × 5/9 + 273,15 |
| 05 | Kelvin → Celsius | K − 273,15 |
| 06 | Kelvin → Fahrenheit | (K − 273,15) × 1,8 + 32 |

## 💻 Tecnologias utilizadas

- **Linguagem C:** desenvolvimento da lógica e das conversões.
- **stdio.h:** entrada e saída de dados utilizando `scanf()` e `printf()`.
- **stdlib.h:** utilização do comando `system("pause")` para manter a tela aberta no Windows.

## 🧠 Conceitos de programação aplicados

Durante o desenvolvimento, foram utilizados:

- **Funções:** criação de seis funções independentes para realizar as conversões.
- **Variáveis:** armazenamento dos valores de temperatura e dos resultados.
- **Estrutura condicional:** utilização de `switch` e `case` para selecionar a conversão.
- **Entrada de dados:** utilização de `scanf()` para receber as informações do usuário.
- **Saída de dados:** utilização de `printf()` para apresentar os resultados.
- **Operadores aritméticos:** aplicação de multiplicação, divisão, adição e subtração nas fórmulas matemáticas.

## ▶️ Como executar o projeto

**1. Clone o repositório:**

```bash
git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
```

**2. Acesse a pasta do projeto:**

```bash
cd SEU-REPOSITORIO
```

**3. Compile o código:**

```bash
gcc temperatura.c -o temperatura
```

**4. Execute o programa:**

No Windows:

```bash
temperatura.exe
```

No Linux:

```bash
./temperatura
```

> Observação: o comando `system("pause")` é específico do Windows e pode precisar ser removido ou substituído para executar o programa em outros sistemas operacionais.

## 📷 Demonstração

O programa apresenta um menu com seis opções de conversão. Após selecionar uma delas, o usuário informa o valor da temperatura e recebe o resultado correspondente.

*Adicione aqui uma captura de tela do programa em execução.*

## 🎯 Objetivo acadêmico

O projeto tem como finalidade praticar a utilização de funções, estruturas condicionais e operadores matemáticos na linguagem C, desenvolvendo a capacidade de organizar e solucionar problemas por meio da programação.

## 👩‍💻 Autora

**Marina Alves**

Estudante de Análise e Desenvolvimento de Sistemas — 2º semestre

UDF — Centro Universitário

---

*Projeto acadêmico desenvolvido para fins de aprendizagem e prática de programação em linguagem C.*
