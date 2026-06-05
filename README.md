# Calculadora em Python e Linux

## Sobre o Projeto

Este projeto foi desenvolvido com o objetivo de aplicar conceitos fundamentais de lógica de programação, automação em linha de comando e execução de scripts em ambientes Linux.

A solução contempla a criação de uma calculadora funcional utilizando Python e Shell Script, permitindo a realização de operações matemáticas básicas e demonstrando conhecimentos em desenvolvimento, execução de scripts e gerenciamento de permissões em sistemas Linux.

## Etapas Desenvolvidas

### 1. Desenvolvimento da Calculadora em Python

Foi desenvolvido um script em Python capaz de realizar operações matemáticas básicas por meio da interação com o usuário.

O projeto contemplou:

* Entrada e validação de dados;
* Operações matemáticas fundamentais;
* Estruturas condicionais;
* Estruturas de repetição;
* Manipulação de variáveis;
* Interação via terminal.

### 2. Implementação da Lógica de Execução

A calculadora foi estruturada para permitir múltiplas operações durante uma mesma execução.

Foram utilizados conceitos como:

* Laço `while`;
* Conversão de tipos de dados;
* Tratamento de números inteiros e decimais;
* Fluxo de controle da aplicação.

### 3. Execução em Ambiente Linux

Além da implementação em Python, o projeto também foi executado em ambiente Linux utilizando WSL (Windows Subsystem for Linux) e Ubuntu.

Durante o desenvolvimento foram aplicados conceitos relacionados a:

* Navegação em terminal;
* Manipulação de arquivos;
* Execução de scripts;
* Utilização do editor Nano;
* Gerenciamento de permissões.

### 4. Criação do Script Shell

Foi desenvolvido um script Shell para execução da calculadora diretamente pelo terminal Linux.

Entre os comandos utilizados estão:

#### Criação do Arquivo

```bash
nano calculadora.sh
```

#### Alteração de Permissões

```bash
chmod +x calculadora.sh
```

#### Execução Direta

```bash
./calculadora.sh
```

#### Execução via Bash

```bash
bash calculadora.sh
```

### 5. Gerenciamento de Permissões

Durante o projeto foram aplicados conceitos de permissões de arquivos no Linux.

Foi utilizada a configuração:

```bash
chmod 644 calculadora.sh
```

Nessa configuração:

* Proprietário: leitura e escrita;
* Grupo: leitura;
* Outros usuários: leitura.

Como o arquivo não possui permissão de execução direta, sua execução ocorre através do interpretador Bash.

## Habilidades Demonstradas

* Python
* Shell Script
* Linux
* Ubuntu
* WSL
* Lógica de Programação
* Estruturas Condicionais
* Estruturas de Repetição
* Manipulação de Variáveis
* Linha de Comando
* Terminal Linux
* Gerenciamento de Permissões
* Automação Básica

## Arquivos do Projeto

📄 [calculadora.py](calculadora.py)

📄 [calculadora.sh](calculadora.sh)
