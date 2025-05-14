# SimuladorCajero

# Proyecto en Java: Cajero Automático (ATM)

## Objetivo

Desarrollar un sistema de Cajero Automático en Java utilizando el paradigma de **Programación Orientada a Objetos (POO)**, que permita a los usuarios realizar operaciones básicas como consultar saldo, retirar dinero, depositar dinero y cambiar su clave.

## Alcance

Este sistema funcionará a nivel de consola (modo texto) y simulará el funcionamiento de un cajero automático bancario para una o varias cuentas de usuario.

---

## Funcionalidades Principales

- Iniciar sesión con número de cuenta y clave.
- Consultar saldo.
- Depositar dinero.
- Retirar dinero (validando el saldo disponible).
- Cambiar clave de acceso.
- Salir de la sesión.

---

## Enfoque de Desarrollo

### Paradigma: Programación Orientada a Objetos (POO)

Se utilizarán los siguientes principios:

- **Encapsulamiento:** para proteger los datos de las cuentas.
- **Abstracción:** para modelar el cajero y las cuentas como objetos.
- **Herencia (si se requiere):** para extender funcionalidades, por ejemplo, usuarios especiales.
- **Polimorfismo (opcional):** para manejar diferentes tipos de cuentas, si se amplía el proyecto.

---

## Clases Principales

### 1. `Cuenta`
- Atributos: número de cuenta, nombre del titular, saldo, clave.
- Métodos:
  - `consultarSaldo()`
  - `depositar(double cantidad)`
  - `retirar(double cantidad)`
  - `validarClave(String claveIngresada)`
  - `cambiarClave(String nuevaClave)`

### 2. `Cajero`
- Atributos: lista de cuentas disponibles.
- Métodos:
  - `iniciarSesion(String numeroCuenta, String clave)`
  - `mostrarMenu()`
  - `manejarOperacion(int opcion)`
  - `cerrarSesion()`

### 3. `Main` o `App`
- Clase que contiene el `main` para ejecutar el programa.
- Muestra el menú inicial y gestiona el flujo principal.

---

## Flujo del Programa

1. El sistema solicita número de cuenta y clave.
2. Si las credenciales son correctas, muestra el menú con opciones.
3. El usuario elige una operación (consultar, retirar, depositar, cambiar clave, salir).
4. Se realiza la operación y se vuelve al menú hasta que el usuario decida salir.
5. El programa vuelve al inicio o termina.

---

## Requisitos Técnicos

- **Lenguaje:** Java 8 o superior.
- **IDE sugerido:** IntelliJ IDEA, Eclipse o NetBeans.
- **Entrada/Salida:** Consola (modo texto).
- **Persistencia (opcional):** Se puede agregar un archivo `.txt` para guardar las cuentas si se desea guardar el estado entre ejecuciones.

---

## Posibles Extensiones Futuras

- Manejo de múltiples tipos de cuenta (Ahorros, Corriente).
- Registro de transacciones.
- Interfaz gráfica con JavaFX o Swing.
- Persistencia en archivos o base de datos.

---

## Estructura del Proyecto

