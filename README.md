# 📱 Aplicativo Flutter — Sistema de Login

## 👩‍💻 Autora

**Mirela Marques de Faria**

## 📌 Sobre o projeto

Este projeto foi desenvolvido em **Flutter/Dart** com o objetivo de praticar a criação de interfaces, navegação entre telas e utilização de componentes básicos do Flutter.

O aplicativo possui um fluxo simples de navegação:

**Login → Home → Principal → Logout → Login**

## 🚀 Funcionalidades

* 🔐 Tela de Login
* 📧 Campo para digitação do e-mail
* 🔑 Campo para digitação da senha
* ➡️ Botão **Entrar**
* 🏠 Tela **Home**
* 📋 Tela **Principal**
* 🚪 Botão **Logout**
* 🔄 Navegação entre as telas utilizando `Navigator.push`

## 🖥️ Telas do aplicativo

### 1. Tela de Login

A tela inicial permite que o usuário informe:

* E-mail
* Senha

Ao clicar em **Entrar**, o usuário é direcionado para a tela Home.

### 2. Tela Home

A tela apresenta uma mensagem de boas-vindas:

> Sejam Bem-vindos!!!

Também possui o botão **Principal**, que leva o usuário para a próxima tela.

### 3. Tela Principal

Apresenta o título **Tela Principal** e possui o botão **Logout**.

Ao clicar em Logout, o usuário retorna para a tela de Login.

## 📂 Estrutura do projeto

```text
lib/
├── main.dart
├── home.dart
└── principal.dart
```

### `main.dart`

Responsável por iniciar o aplicativo e apresentar a tela de Login.

Também contém a classe `Login`, responsável pela interface de autenticação.

### `home.dart`

Responsável pela tela Home, exibida após o usuário clicar em **Entrar**.

### `principal.dart`

Responsável pela tela Principal e pelo botão de Logout.

## 🛠️ Tecnologias utilizadas

* **Flutter**
* **Dart**
* **Visual Studio Code**
* **Material Design**

## 🧩 Componentes utilizados

O projeto utiliza alguns componentes básicos do Flutter:

* `MaterialApp`
* `Scaffold`
* `AppBar`
* `Text`
* `TextField`
* `ElevatedButton`
* `Column`
* `Center`
* `Padding`
* `SizedBox`
* `Navigator`
* `MaterialPageRoute`

## ▶️ Como executar o projeto

### 1. Clone o repositório

```bash
git clone URL_DO_SEU_REPOSITORIO
```

### 2. Entre na pasta do projeto

```bash
cd nome-do-projeto
```

### 3. Instale as dependências

```bash
flutter pub get
```

### 4. Execute o aplicativo

```bash
flutter run
```

## 🔄 Fluxo de navegação

```text
       ┌─────────────┐
       │    Login    │
       └──────┬──────┘
              │ Entrar
              ↓
       ┌─────────────┐
       │    Home     │
       └──────┬──────┘
              │ Principal
              ↓
       ┌─────────────┐
       │  Principal  │
       └──────┬──────┘
              │ Logout
              ↓
       ┌─────────────┐
       │    Login    │
       └─────────────┘
```

## 📚 Objetivo acadêmico

O projeto tem como objetivo desenvolver conhecimentos básicos de desenvolvimento de aplicativos utilizando Flutter, principalmente:

* Criação de telas;
* Organização de arquivos;
* Navegação entre páginas;
* Criação de formulários simples;
* Utilização de widgets;
* Manipulação de botões e eventos.

## 📄 Status do projeto

**Concluído — Projeto acadêmico.**
