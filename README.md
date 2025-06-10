# Practica-Barri
Practica para la actividad de barrientos

# 🕒 Sistema de Gestión de Horarios

## 📌 Descripción General

El **Sistema de Gestión de Horarios** es una plataforma web diseñada para facilitar la **planificación, organización y visualización de horarios** en instituciones educativas, empresas, hospitales u otras entidades que requieran gestionar múltiples recursos, usuarios y bloques temporales.

La aplicación permite a los usuarios interactuar con un entorno dinámico para registrar, modificar y consultar horarios de manera eficiente, evitando conflictos de asignación y reduciendo el tiempo dedicado a tareas manuales de planificación.

---

## 🎯 Objetivo del Proyecto

El objetivo principal del proyecto es **automatizar la gestión de horarios** mediante una interfaz web interactiva que permita:

- Registrar bloques de tiempo por usuario, sala, materia o actividad.
- Visualizar horarios en diferentes formatos (día, semana, usuario).
- Detectar y evitar conflictos de solapamiento.
- Facilitar la edición rápida y validada de horarios.
- Proporcionar una base de datos centralizada y segura.
- Servir la aplicación de forma confiable mediante un servidor Apache.

---

## 📚 Justificación

En muchas organizaciones, la programación de horarios se realiza de forma manual o con herramientas ofimáticas, lo cual:

- Es propenso a errores humanos.
- Dificulta el acceso en tiempo real y desde múltiples dispositivos.
- Limita la escalabilidad cuando se manejan muchos usuarios o recursos.

Este sistema está desarrollado para eliminar esos inconvenientes, promoviendo:

- La **digitalización de procesos administrativos**.
- El **acceso remoto** a la información.
- La **reducción de errores de asignación**.
- La **mejora en la productividad organizacional**.

---

## ⚙️ Funcionalidades Principales

- 👤 Gestión de usuarios con roles (Administrador, Coordinador, Usuario).
- 🗓️ Creación y edición de horarios por día, semana o mes.
- 🧠 Lógica de validación contra solapamientos de horarios.
- 📄 Exportación de horarios a PDF y CSV.
- 🔐 Autenticación con tokens JWT.
- 🔎 Búsqueda avanzada por nombre, materia, espacio o recurso.
- 📱 Interfaz responsiva adaptada a escritorio, tablet y móvil.
- 🌐 Soporte para despliegue en servidores Apache/Linux.

---

## 🛠️ Stack Tecnológico

| Componente | Descripción |
|-----------|-------------|
| **Frontend** | React, React Router, Axios, Bootstrap o Tailwind |
| **Backend** | Node.js, Express.js, JWT, Mongoose |
| **Base de Datos** | MongoDB |
| **Despliegue** | Apache HTTPD como proxy inverso + servidor de archivos estáticos |
| **Gestión de Procesos** | PM2 (opcional) |

---

## 🏗️ Arquitectura del Sistema

