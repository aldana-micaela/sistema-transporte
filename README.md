# 🚚 Sistema de Gestión de Transporte

Este proyecto académico consiste en un sistema de gestión para una empresa de transporte. Permite simular el registro y envío de paquetes mediante diferentes tipos de transporte (camiones, mega trailers), controlando el estado de los envíos y el manejo de clientes, depósitos y fletes.

## 🧠 Tecnologías y conceptos aplicados

- **Java** – Lenguaje de programación.
- **POO (Programación Orientada a Objetos)** – Estructura por clases, encapsulamiento, atributos y métodos.
- **Herencia** – Uso de clases especializadas como `CamionTrailer` y `MegaTrailer` que extienden `Transporte`.
- **JUnit** – Pruebas unitarias para verificar el comportamiento de clases como Empresa.
- **Eclipse IDE** – Estructura lista para importar y ejecutar en Eclipse.

## 🎯 Funcionalidades principales

- Registro y gestión de clientes.
- Manejo de paquetes (envíos) con atributos como peso, destino, etc.
- Gestión de flota: transporte disponible y su capacidad.
- Control de depósitos para organizar entregas.
- Ejecución de pruebas unitarias con JUnit (`EmpresaTest.java`).

## 📂 Estructura del proyecto

```text
sistema-transporte/
│
├── src/tp/
│   ├── Cliente.java
│   ├── Deposito.java
│   ├── Empresa.java
│   ├── EmpresaTest.java      # Prueba unitaria (JUnit)
│   ├── Flete.java
│   ├── Paquete.java
│   ├── Transporte.java       # Clase base
│   ├── CamionTrailer.java    # Subclase de Transporte
│   └── MegaTrailer.java      # Subclase de Transporte
│
├── bin/                      # Clases compiladas
├── .project / .classpath     # Archivos de Eclipse
└── README.md
```

## 🔧 Cosas por mejorar
- Implementar persistencia (guardar datos en archivos o base de datos).
- Agregar una interfaz gráfica o consola interactiva para registrar entidades.
- Validaciones adicionales para entradas inválidas.
- Exportación de reportes (clientes, paquetes enviados, capacidad utilizada).
- Separar lógica en paquetes más modulares.

## 👩‍💻 Autoría
Aldana Filiberto, estudiante de Licenciatura en Sistemas.

---
Este proyecto fue desarrollado como parte de una actividad académica con el objetivo de aplicar los fundamentos de POO, herencia y pruebas automatizadas en el contexto de una empresa de transporte.
