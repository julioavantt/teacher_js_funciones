# 🦄 Teacher JS Funciones

¡Hola, dev del futuro! 👋

Bienvenida/o a **Teacher JS Funciones**, una guía detallada sobre funciones 🎨💻.

---

## 📘 Contenido

- Declaración de funciones.
- Invocación de funciones.
- return.
- Argumentos y Parámetros.
- Expresión de función anónima.
- Expresión de función de flecha (arrow).
- Scope.

---

## 🚀 Extras

- for.
- IIFE.

---

# Ejercicio 1: Simulador de Casa de Cambio 💱

Este pequeño programa simula una operación básica de compra y venta de dólares. Está escrito en JavaScript y funciona directamente en el navegador usando `prompt()` y `alert()`.

## 🧠 ¿Qué hace este programa?

Cuando lo ejecutás:

1. Te pregunta si querés **comprar** o **vender** dólares.
2. Según la opción que elijas:
   - Si comprás, te pide cuántos dólares querés y te muestra cuánto tenés que pagar.
   - Si vendés, te pide cuántos dólares querés vender y te muestra cuánto vas a recibir.

## 💸 Cotizaciones

El programa usa dos valores fijos:

- **Compra (valor al que comprás dólares)**: `$1235`
- **Venta (valor al que vendés dólares)**: `$1200`

## ⚙️ Cómo funciona

El código está dividido en funciones:

### `compra()`

- Pide al usuario cuántos dólares quiere comprar.
- Calcula el total a pagar usando la cotización de compra.
- Muestra el costo con un `alert`.

### `venta()`

- Pide al usuario cuántos dólares quiere vender.
- Calcula cuánto va a recibir usando la cotización de venta.
- Muestra el resultado con un `alert`.

### `operacion(op)`

- Recibe la opción elegida (`1` para compra o `2` para venta).
- Ejecuta la función correspondiente (`compra()` o `venta()`).
- Si se ingresa otra opción, vuelve al menú principal.

### `llamarAction()`

- Muestra el menú inicial con `prompt`:

# Ejercicio 2: Simulador de E-Commerce 🛒

# 🛒 E-Commerce Guachi Guau

Este proyecto es una simulación muy simple de un e-commerce básico hecha con HTML y JavaScript puro.  
Permite calcular el precio total al comprar **Coca-Cola** o **papitas**, dependiendo de la cantidad que elija el usuario.

## 🌟 ¿Qué hace este programa?

Cuando lo abrís en el navegador, aparece un título y, en segundo plano, se ejecuta un código JavaScript que:

1. Te pregunta qué querés comprar:
   - `1` para Coca-Cola
   - `2` para Papitas
2. Luego te pregunta **cuántas unidades** querés.
3. Finalmente, te muestra el **precio total** que tenés que pagar según el producto y la cantidad.

## 💰 Precios

- **Coca-Cola**: `$4100` cada una
- **Papitas**: `$4000` cada una

## 🧠 Cómo está organizado el código

El programa se basa en tres funciones principales:

### `calcular(que, cuanto)`

Recibe qué producto eligió el usuario y cuántas unidades quiere.  
Usa un `switch` para decidir qué precio multiplicar según el producto.  
Muestra el total con un `alert`.

### `queQuiereYcuanto()`

- Pide al usuario que elija entre Coca-Cola o Papitas.
- Si elige algo no válido, vuelve al menú.
- Luego pide la cantidad deseada.
- Llama a `calcular()` con esos datos.

### `principal()`

Es el punto de inicio del programa.  
Llama a `queQuiereYcuanto()`.

## ▶️ Cómo usarlo

1. Copiá el contenido en un archivo llamado `index.html`.
2. Abrilo con cualquier navegador.
3. Aparecerá el título **"E COMMERCE"** y se ejecutará el programa en segundo plano con ventanas emergentes (`prompt` y `alert`).

## 🧑‍💻 Ideal para practicar

Este ejemplo es excelente para principiantes que quieren practicar:

- Estructura básica de un archivo HTML.
- Uso de `prompt()` y `alert()`.
- Condicionales `switch`.
- Lógica básica de e-commerce: elegir producto + cantidad = total.

---
