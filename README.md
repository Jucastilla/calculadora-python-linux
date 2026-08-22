# Projeto de Programação | Python e Linux

## Calculadora em Python e Shell Script

## Sobre o Projeto

Este projeto foi desenvolvido durante a formação em **Análise de Dados da EBAC**, com o objetivo de aplicar conceitos de lógica de programação utilizando Python e Shell Script.

O projeto consiste no desenvolvimento de duas versões de uma calculadora executada por linha de comando: uma implementada em **Python** e outra em **Shell Script**.

As calculadoras permitem realizar operações de soma, subtração, multiplicação e divisão, além de possibilitar a realização de múltiplos cálculos durante uma mesma execução.

Na implementação em Python, também foram aplicados tratamento de entradas inválidas e tratamento de divisão por zero.

## Objetivo

Desenvolver uma calculadora em linha de comando para aplicar conceitos fundamentais de lógica de programação em Python e Shell Script.

O projeto permite praticar entrada de dados, operações matemáticas, estruturas condicionais, estruturas de repetição e controle do fluxo de execução.

## Etapas Desenvolvidas

### 1. Desenvolvimento da Calculadora em Python

Foi desenvolvida uma calculadora em Python executada por meio do terminal.

O programa solicita ao usuário dois números e a operação matemática desejada, permitindo realizar:

- Soma;
- Subtração;
- Multiplicação;
- Divisão.

Os valores informados são convertidos para `float`, permitindo trabalhar com números inteiros e decimais.

A seleção da operação é realizada por meio de estruturas condicionais `if`, `elif` e `else`.

### 2. Controle de Execução e Tratamento de Erros em Python

A calculadora utiliza um laço `while` para permitir que novas operações sejam realizadas sem a necessidade de reiniciar o programa.

Após cada cálculo, o usuário pode escolher se deseja realizar uma nova operação.

Também foram implementados tratamentos para situações específicas:

- Entrada de valores que não podem ser convertidos em números;
- Tentativa de divisão por zero;
- Seleção de uma operação diferente de `+`, `-`, `*` ou `/`;
- Tratamento de exceções inesperadas durante a execução.

Para o tratamento das entradas inválidas e demais exceções, foram utilizados `try`, `except ValueError` e `except Exception`.

### 3. Desenvolvimento da Calculadora em Shell Script

Também foi desenvolvida uma versão da calculadora utilizando Shell Script.

O script solicita pelo terminal:

- Primeiro número;
- Segundo número;
- Operação matemática desejada.

A leitura dos valores é realizada utilizando o comando `read`, enquanto estruturas condicionais `if`, `elif` e `else` determinam a operação que será executada.

A calculadora em Shell Script permite realizar:

- Soma;
- Subtração;
- Multiplicação;
- Divisão.

As operações são executadas utilizando a expansão aritmética do Bash `$((...))`.

### 4. Controle de Execução no Shell Script

Assim como na implementação em Python, a versão em Shell Script utiliza uma estrutura de repetição para permitir a realização de múltiplos cálculos.

O laço `while` mantém a calculadora em execução enquanto o usuário optar por continuar.

O script também verifica:

- Tentativas de divisão por zero;
- Operações diferentes das opções disponíveis.

Ao final de cada cálculo, o usuário pode informar se deseja realizar outra conta.

### 5. Execução em Ambiente Linux

O Shell Script possui o interpretador Bash definido na primeira linha do arquivo:

```bash
#!/bin/bash
```

Durante o desenvolvimento do projeto também foram utilizados comandos de Linux relacionados à criação, permissões e execução do script.

Para edição do arquivo:

```bash
nano calculadora.sh
```

Para conceder permissão de execução:

```bash
chmod +x calculadora.sh
```

Com a permissão de execução, o script pode ser executado diretamente:

```bash
./calculadora.sh
```

Também é possível executá-lo por meio do Bash:

```bash
bash calculadora.sh
```

### 6. Gerenciamento de Permissões

Durante o projeto também foram aplicados conceitos relacionados às permissões de arquivos no Linux.

Foi utilizada a configuração:

```bash
chmod 644 calculadora.sh
```

Nessa configuração:

- Proprietário: leitura e escrita;
- Grupo: leitura;
- Outros usuários: leitura.

Como essa configuração não concede permissão de execução ao arquivo, sua execução pode ser realizada por meio do interpretador Bash:

```bash
bash calculadora.sh
```

### 7. Conclusões

O projeto permitiu aplicar conceitos fundamentais de lógica de programação por meio da construção de duas versões de uma calculadora em linha de comando.

Na implementação em Python foram utilizados entrada de dados, conversão para números decimais, estruturas condicionais, estrutura de repetição e tratamento de exceções.

Na implementação em Shell Script foram utilizados leitura de dados pelo terminal, estruturas condicionais, repetição e operações aritméticas do Bash.

O projeto também envolveu conceitos relacionados à execução de scripts e gerenciamento de permissões em ambiente Linux.

## Habilidades Demonstradas

- Python
- Shell Script
- Bash
- Linux
- Lógica de Programação
- Entrada de Dados
- Estruturas Condicionais
- Estruturas de Repetição
- Tratamento de Exceções em Python
- Operações Aritméticas
- Linha de Comando
- Execução de Scripts
- Gerenciamento de Permissões

## Arquivos do Projeto

Os scripts desenvolvidos no projeto estão organizados na pasta `scripts`.

### Scripts

🐍 [Calculadora em Python](https://github.com/Jucastilla/calculadora-python-linux/blob/main/scripts/calculadora.py)

Script em Python responsável pela calculadora, permitindo realizar operações de soma, subtração, multiplicação e divisão, com tratamento de entradas inválidas e divisão por zero.

🐚 [Calculadora em Shell Script](https://github.com/Jucastilla/calculadora-python-linux/blob/main/scripts/calculadora.sh)

Script em Shell que implementa a calculadora para execução em ambiente Linux, permitindo realizar as quatro operações matemáticas básicas diretamente pelo terminal.
