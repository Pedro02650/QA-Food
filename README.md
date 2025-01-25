# Maestro 🎹

Maestro is the easiest way to automate UI testing for your mobile app.

> **Note**
> **Full documentation for Maestro can be found at [maestro.mobile.dev](https://maestro.mobile.dev)**


<img src="https://user-images.githubusercontent.com/847683/187275009-ddbdf963-ce1d-4e07-ac08-b10f145e8894.gif" />



# Maestro samples

`maestro download-samples` provides a set of flows and apps so that users can quickly set up a maestro test, without having to create an app.

download-samples downloads these files and apps from storage.googleapis.com.

# Como executar o projeto na sua máquina 

Este projeto utiliza **Maestro Studio** para automação de testes de aplicativos móveis. Siga os passos abaixo para rodar os testes **localmente** e no **modo headless**.

## Pré-requisitos

- **Node.js**:(https://nodejs.org)
- **Maestro Studio**: (https://maestro.app)
- **Dispositivo móvel ou emulador/simulador** configurado (https://developer.android.com)

## Passo 1: Clonar o repositório

Clone este repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git

## Passo 2: Instalar dependências

Instale as dependências com o npm:

npm install

## Passo 3: Configurar o ambiente

Configure o ambiente dependendo do seu sistema operacional.

Para macOS ou Linux:

export ANDROID_HOME=/caminho/para/android/sdk
export PATH=$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools:$PATH

Para Windows:

Configure as variáveis de ambiente no painel de Sistema > Variáveis de Ambiente:

ANDROID_HOME = C:\caminho\para\android\sdk
Adicione C:\caminho\para\android\sdk\platform-tools no Path.

## Passo 4: Rodar os testes localmente

macOS / Linux / Windows:

Para rodar os testes localmente em um dispositivo ou emulador, execute o comando:

npx maestro test

## Passo 5: Rodar os testes em modo headless

macOS / Linux / Windows:

Para rodar os testes em modo headless (sem interface gráfica), use o comando:

npx maestro test --headless

## Contatos

<a href="https://www.linkedin.com/in/pedro-cisne/">
    <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" />
     <a href = "mailto:pedrohpcisne@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank">
  </a>
