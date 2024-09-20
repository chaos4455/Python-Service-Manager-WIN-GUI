# 🖥️ Python-Service-Manager-WIN-GUI

![Python](https://img.shields.io/badge/Python-3.9-blue)
![PyQt5](https://img.shields.io/badge/PyQt5-5.15.4-orange)
![PyInstaller](https://img.shields.io/badge/PyInstaller-4.7-yellowgreen)

## 🚀 Introdução

O **Python-Service-Manager-WIN-GUI** é um projeto que visa facilitar o gerenciamento de serviços no sistema operacional Windows através de uma interface gráfica desenvolvida com PyQt5. Este lançador permite que os usuários iniciem, parem e gerenciem serviços do Windows de maneira intuitiva e eficiente.

## 🔍 Objetivo do Projeto

O principal objetivo deste projeto é fornecer uma ferramenta amigável que simplifique o gerenciamento de serviços no Windows, permitindo que até mesmo usuários não técnicos possam realizar operações comuns sem necessidade de conhecimento em linha de comando.


## 🛠️ Tecnologias Utilizadas

- **Python**: Linguagem de programação principal para o desenvolvimento da aplicação.
- **PyQt5**: Biblioteca para a criação de interfaces gráficas que permite uma experiência de usuário rica e responsiva.
- **PyInstaller**: Ferramenta utilizada para empacotar a aplicação em um executável (.exe), facilitando a distribuição e uso em diferentes sistemas Windows.
- **Subprocess**: Módulo do Python que permite a execução de comandos do sistema, essencial para gerenciar serviços.
- 
![python_IOrwcnDQG2](https://github.com/user-attachments/assets/b67e6773-d8ce-436d-acd3-438279ab705c)
![servicestartwinV5_mqfqWwyDld](https://github.com/user-attachments/assets/dedee9c1-7864-46e6-8b2d-c3704a146450)

## 🔧 Funcionalidades

### ✔️ Gerenciamento de Serviços

- **Iniciar Serviço**: Permite ao usuário iniciar um serviço específico no Windows.
- **Parar Serviço**: Permite ao usuário parar um serviço em execução.
- **Reiniciar Serviço**: Função para reiniciar serviços facilmente.
- **Listar Serviços**: Exibe todos os serviços disponíveis, junto com seu status atual (em execução, parado, etc.).
- **Acesso Rápido**: Interface limpa e intuitiva que possibilita acesso rápido às funcionalidades desejadas.

## 📋 Estrutura do Código

O projeto é organizado em uma estrutura modular, onde cada funcionalidade é encapsulada em funções específicas. Aqui estão algumas partes principais:

1. **Interface Gráfica (GUI)**: Implementada com PyQt5, a GUI é responsável pela interação do usuário e apresenta botões para cada ação relacionada a serviços.
2. **Gerenciamento de Processos**: Utilizando o módulo `subprocess`, o código executa comandos como `sc start [nome_do_serviço]` e `sc stop [nome_do_serviço]` para gerenciar serviços.
3. **Compilação em Executável**: O uso do PyInstaller permite que o projeto seja compilado em um executável que pode ser facilmente distribuído e executado em qualquer sistema Windows.

