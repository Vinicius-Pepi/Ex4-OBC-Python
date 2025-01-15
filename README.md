# Projeto: Contagem Regressiva + Tabuada em Python

Este repositório contém dois projetos simples desenvolvidos em Python que têm como objetivo praticar a manipulação de loops, entrada de dados e integração com diferentes sistemas operacionais.

## 🚀 Descrição

### 1️⃣ **Contagem Regressiva do Lançamento de um Foguete**

Um programa simples que realiza uma contagem regressiva de 10 até 0 e emite um "beep" sonoro no final, simulando o lançamento de um foguete.

- **Desafio**: Garantir que o som funcionasse corretamente em sistemas **Windows** e **Linux**. No Windows, usei a biblioteca `winsound`, enquanto no Linux utilizei `pygame.mixer` para reprodução de áudio.

### 2️⃣ **Tabuada Personalizada**

Programa que calcula a tabuada de um número inserido pelo usuário, com valores de início e fim definidos também pelo usuário.

- **Objetivo**: Praticar interações dinâmicas com o usuário e trabalhar com loops.

## 🔧 Tecnologias Usadas

- Python 3.x
- Biblioteca `time` para contagem regressiva
- Biblioteca `platform` para detectar o sistema operacional
- `pygame.mixer` (Linux) e `winsound` (Windows) para emitir sons

## 💻 Como Rodar o Código

### Pré-requisitos:
- Python 3.x instalado no seu computador
- Instalação da biblioteca `pygame` (caso esteja no Linux)

```bash
pip install pygame
