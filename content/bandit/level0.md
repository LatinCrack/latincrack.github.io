---
title: "Level0"
date: 2026-01-04T23:37:35-05:00
draft: false
---

### 📝 Enunciado del Reto
> El objetivo de este nivel es que te conectes al juego mediante SSH. El servidor está escuchando en el puerto 2220.

### 🎯 Objetivo
Establecer la primera conexión exitosa al servidor para comenzar el wargame y obtener acceso a la shell inicial.

### 🛠️ Condiciones y Datos
- **Host:** `bandit.labs.overthewire.org`
- **Puerto:** `2220`
- **Usuario:** `bandit0`
- **Password:** `bandit0`

### 🚀 Solución
Para resolver este nivel, utilizamos el cliente de SSH nativo de Linux. Ejecutamos el siguiente comando en la terminal:

```bash
# Conectando al servidor por primera vez
ssh bandit0@bandit.labs.overthewire.org -p 2220
```
Al solicitar la contraseña, ingresamos: bandit0.

Una vez dentro, podemos confirmar nuestra identidad con el comando whoami o listar los archivos iniciales con ls.

### 💡 Recomendaciones / Conceptos Clave
- **SSH (Secure Shell):** Protocolo utilizado para administrar máquinas de forma remota de manera segura.

- **Parámetro -p:** Se utiliza para especificar un puerto distinto al puerto por defecto (22).

- **Fingerprint:** La primera vez que te conectes, verás un mensaje sobre la autenticidad del host; escribe yes para continuar