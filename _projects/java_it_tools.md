---
layout: page
title: IT Tools
description: program with various IT tools that I've made for my team
img: assets/img/projects/tools-project.png
importance: 1
category: java
related_publications: true
github: https://github.com/Marchinner/FerramentasTI
---

<hr>

## Description

This is the public version of the program developed entirely by me to meet and optimize some demands in the sector
of the company Grupo Dok.
It was developed entirely in Java and I used two Maven plugins for some features, namely:

- JPowerShell, for executing PowerShell commands
- Javax Mail, for sending emails

During the development of this program, I put into practice concepts of OOP, uploading and sending files,
sending emails, executing PowerShell commands and scripts and creating windows with Java Swing.

## Screenshots

![App Screenshot](https://github.com/Marchinner/FerramentasTI/raw/master/src/main/resources/telaUtilitarios.png)

![App Screenshot](https://github.com/Marchinner/FerramentasTI/raw/master/src/main/resources/telaUsuarios.png)

![App Screenshot](https://github.com/Marchinner/FerramentasTI/raw/master/src/main/resources/telaComputadores.png)

![App Screenshot](https://github.com/Marchinner/FerramentasTI/raw/master/src/main/resources/telaPatrimonio.png)

![App Screenshot](https://github.com/Marchinner/FerramentasTI/raw/master/src/main/resources/telaCredenciais.png)

## Functionalities

- Commands for quick Active Directory security/organization and health checks
- Search and edit user information, move, activate, change email and computer released for logon
- Search and enable/disable computers on the network
- Send an automatic message according to the form to inform the movement of an asset item
- Send an automatic message for a new heritage item and attach the necessary photos for registration
- Send an automatic "welcome" message that informs the new employee about their credentials and access

## Technologies

- Java JDK 21
- Java Swing
- Maven
- JPowerShell Maven Plugin
- Javax Mail Maven Plugin

## Observations

This is a version with source code modified to become public, therefore, the features that require PowerShell and sending emails will not work as they depend on information and access that is private.

You can run the application and view its entire frontend and its logic used in the backend, but the functionalities are not with the data.
