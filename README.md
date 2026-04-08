#  Quebrada del Vino - 2026
### TFI Proyecto Grupal - TUP - UTNFRA

![Estado](https://img.shields.io/badge/estado-en%20desarrollo-yellow)
![Plataforma](https://img.shields.io/badge/plataforma-mobile-blue)

---

## Descripción

Este repositorio tiene la aplicación mobile, front-end y back-end para el restaurante 'Quebrada del Vino'

---

## 📚 Índice

- [Descripción](#descripción)
- [Autores](#autores)
- [Módulos](#testing)
- [Tareas](#tareas)
- [Branches](#branches)
- [Arquitectura](#️🏗️-arquitectura)
- [Stack Tecnológico](#🧩-stack-tecnológico)
- [Instalación](#️instalación)


---

## Autores

![Dev](https://img.shields.io/badge/Dev-Salamone_Sol_M_Constanza-7a3e4a?style=flat-square) [@cosalamone](https://github.com/cosalamone) 

![PO](https://img.shields.io/badge/PO-Schiaffino_Quiroga_Maria-800000?style=flat-square) [@SMNoah](https://github.com/SMNoah) 

![Dev](https://img.shields.io/badge/Dev-Rivera_Mendes_Maximiliano_A-8B4513?style=flat-square) [@Minipomy](https://github.com/Minipomy)

---

## Módulos
- [ ] Autenticación y usuarios
  - [ ] Sub-task 1
- [ ] Gestion Clientes
  - [ ] Sub-task 1
- [ ] Gestion Empleados
  - [ ] Sub-task 1
- [ ] Menu Productos
  - [ ] Sub-task 1
- [ ] Gestion Mesas y Salon
  - [ ] Sub-task 1
- [ ] Gestion Pedidos
  - [ ] Sub-task 1
- [ ] Comunicacion (interna/externa)
  - [ ] Sub-task 1
- [ ] Juegos
  - [ ] Sub-task 1
- [ ] Encuestas y Estadisticas
  - [ ] Sub-task 1
- [ ] Pagos
  - [ ] Sub-task 1

---

## Tareas
- Creacion de proyecto (07/04/2026) - ![PO](https://img.shields.io/badge/PO-Schiaffino_Quiroga_Maria-800000?style=flat-square)

- Diseño de ícono de la aplicacion (07/04/2026) - ![Dev](https://img.shields.io/badge/Dev-Salamone_Sol_M_Constanza-7a3e4a?style=flat-square)

---

## Branches
- Main

---

## 🏗️ Arquitectura
```mermaid
graph LR
    Cliente -->|QR| App
    App --> Backend
    Backend --> DB[(Base de Datos)]
    Backend --> Push[Push Notifications]
    Backend --> Email[Email Service]
```

---

## 🧩 Stack Tecnológico
### 🎨 Client

> ![Angular](https://img.shields.io/badge/Angular-DD0031?logo=angular&logoColor=white)
>
> 🎛️ **PrimeNG**
>
> ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?logo=tailwindcss&logoColor=white)
>
> ![Ionic](https://img.shields.io/badge/Ionic-3880FF?logo=ionic&logoColor=white)
>
> 🧪 **Zod**


### ⚙️ Server

> ![NestJS](https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white)
>
> ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white)
>
> 🔐 **SSO (Auth Providers)**

---

## Instalación

Clone the project

```bash
  git clone https://github.com/SMNoah/quebrada-del-vino-2026.git
```

Go to the project directory

```bash
  cd quebrada-del-vino-2026
```

Install dependencies

```bash
  npm install 
```

Start the server

```bash
  npm run start
```

---
