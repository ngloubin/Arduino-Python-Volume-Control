# Mixer de Volume com Arduino e Python no Windows

Este projeto implementa um mixer de volume que controla o volume geral do sistema operacional Windows utilizando um Arduino e Python. O valor de um potenciômetro conectado ao Arduino é lido via porta serial e convertido para ajustes de volume no sistema, utilizando a biblioteca [PyCaw](https://github.com/AndreMiras/pycaw).

---

## 🚀 Funcionalidades

- Controle de volume do sistema operacional em tempo real.
- Comunicação entre Arduino e computador via porta serial.
- Conversão suave do valor do potenciômetro para níveis de volume (0% a 100%).

---

## 🛠️ Requisitos

- **Hardware**:
  - Arduino (ex.: Uno, Nano, etc.).
  - Potenciômetro conectado a um dos pinos analógicos do Arduino.
  - Cabo USB para conectar o Arduino ao computador.

- **Software**:
  - Python 3.x.
  - Biblioteca `pycaw` e suas dependências.

---

## 📦 Instalação

1. Clone este repositório ou copie os arquivos do projeto.
2. Instale as dependências Python executando:
   ```bash
   pip install pycaw comtypes # só para windows 
   pip install serial
