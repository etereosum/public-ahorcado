# 🎯 Prueba Técnica – Desarrollador Frontend

## 🎮 Introducción al Juego del Ahorcado

El **ahorcado** es un juego clásico de adivinanza de palabras en el que un jugador debe descubrir una palabra secreta, letra por letra, antes de cometer un número máximo de errores.

### 🧠 ¿Cómo funciona?

- Se escoge una **palabra secreta** y se muestra como una serie de guiones (`_`), representando cada letra.
- El jugador debe ingresar una letra en cada intento.
- Si la letra está en la palabra, se revela en su(s) posición(es) correcta(s).
- Si la letra no está, se **suma un fallo** y se dibuja una parte del "muñeco ahorcado".
- El jugador **gana** si adivina toda la palabra antes de completar los 6 fallos.
- El jugador **pierde** si comete 6 errores antes de completar la palabra.

### 🧩 Reglas clave del juego

- Solo se permiten letras del alfabeto.
- No se distingue entre mayúsculas y minúsculas.
- Letras repetidas no deben penalizarse si ya fueron intentadas.
- El juego debe permitir reiniciar la partida en cualquier momento.

Este reto busca implementar esa lógica usando un framework moderno, aprovechando el manejo de estado, componentes y estilos personalizados.

---

## ✅ Requisitos

### 1. Framework Frontend

- Puede usarse **Vanilla Javascript**,**Vue.js 3**, **React**, **Angular**, u otro framework moderno basado en JavaScript.

### 2. Diseño

- Se permite el uso de frameworks de estilos como **Bootstrap**, **Tailwind**, **Material UI**, etc.
- También puede usarse **CSS puro** si se prefiere.

### 3. Componentes requeridos

#### 🅰️ Componente de Entrada de Texto

- Permitir que el usuario escriba una letra.
- Gestionar localmente la letra escrita.

#### 🅱️ Componente de Ahorcado

- Mostrar el avance del juego.
- Dibujar el ahorcado en función del número de errores cometidos.
- Mostrar letras acertadas y fallidas.

### 4. Lógica del juego

- Mostrar guiones bajos (`_`) representando las letras ocultas.
- Revelar letras correctas a medida que se adivinan.
- Dibujar el ahorcado en un máximo de **6 pasos**.
- Mostrar mensaje de victoria o derrota según el resultado.
- Aceptar únicamente letras (sin importar mayúscula o minúscula).
- Limpiar automáticamente el input después de cada intento.

### 5. Funcionalidades mínimas

- Debe existir la opción de **reiniciar el juego**.

---

## 📊 Criterios de evaluación

- Separación adecuada en componentes.
- Funcionalidad completa del juego.
- Código limpio y organizado.
- Buen uso de CSS o frameworks de estilos.

---

## 📤 Entregables

- Repositorio público en **GitHub** o **GitLab**.
- Archivo `README.md` con instrucciones para instalar y ejecutar el proyecto.

---

**¡Éxitos!** 💻🎮
