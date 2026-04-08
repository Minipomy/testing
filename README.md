# testing


> [!IMPORTANT]
> algo123algo123algo123algo123algo123algo123algo123

# 🍽️ App Restaurante - TP Final

![Estado](https://img.shields.io/badge/estado-en%20desarrollo-yellow)
![Plataforma](https://img.shields.io/badge/plataforma-mobile-blue)
![Stack](https://img.shields.io/badge/stack-Ionic%20%2B%20Angular-red)

---

## 📚 Índice

- [Descripción](#-descripción)
- [Arquitectura](#️-arquitectura)
- [Perfiles del sistema](#-perfiles-del-sistema)
- [Funcionalidades](#-funcionalidades-principales)
- [Flujos principales](#-flujos-principales)
- [Métricas](#-métricas--simulación)
- [Stack Tecnológico](#-stack-tecnológico)
- [Instalación](#️-instalación)
- [Testing](#-testing)
- [Roadmap](#-roadmap)
- [Notas finales](#-notas-finales)

---

## 👨‍💻 Integrantes

- Maximiliano Rivera Mendes  
- Alejandro Constanzo  
- Octavio Villegas  

---

## 📱 Descripción

Aplicación mobile para la **gestión integral de un restaurante**, enfocada en:

- 🧑‍🍳 Operación interna (empleados)
- 🍽️ Experiencia del cliente
- 📊 Análisis de datos y encuestas
- 📲 Interacción mediante códigos QR

---

## 🏗️ Arquitectura

```mermaid
graph LR
    Cliente -->|QR| App
    App --> Backend
    Backend --> DB[(Base de Datos)]
    Backend --> Push[Push Notifications]
    Backend --> Email[Email Service]
