# 🏥 Sistema de Gestión de Emergencias Médicas Concurrente

Este proyecto simula un sistema concurrente y multihilo para la atención de emergencias médicas, utilizando programación en Java. Fue desarrollado como parte de un caso de estudio académico para la Institución Universitaria Digital de Antioquia.

---

## 🚀 Características principales

- Recepción de llamadas simultáneas desde un centro de emergencia.
- Algoritmo de priorización basado en gravedad, tiempo de espera y ubicación.
- Gestión de recursos limitados (ambulancias, médicos) con sincronización segura.
- Simulación de atención médica concurrente mediante hilos (`Thread`).
- Monitoreo en tiempo real de los recursos disponibles y emergencias en curso.
- Comunicación simulada entre operadores, despachadores y ambulancias.

---

## 🛠️ Tecnologías utilizadas

- Lenguaje: **Java 8 o superior**
- Concurrencia: `Thread`, `Runnable`
- Estructuras de datos seguras: `PriorityBlockingQueue`, `Semaphore`, `ReentrantLock`
- Herramientas sugeridas: Replit, IntelliJ, Eclipse o terminal Java local

---

## 📦 Estructura del proyecto
EmergencyManagementSystem/
├── src/
│ └── Main.java # Código fuente principal
├── README.md # Instrucciones de uso

---

## 📋 Requisitos

- Java JDK 8 o superior
- Conexión a internet (si se usa en Replit)

---

## 💻 Instrucciones de ejecución

### ✅ Opción 1: Ejecutar en Replit (recomendado para pruebas rápidas)

1. Ve a [https://replit.com](https://replit.com) y crea un nuevo Repl con lenguaje **Java**.
2. Reemplaza todo el contenido de `Main.java` por el contenido del archivo `src/Main.java` de este repositorio.
3. Haz clic en **Run** y observa la simulación en tiempo real en la consola.

### ✅ Opción 2: Ejecutar localmente

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/EmergencyManagementSystem.git
   cd EmergencyManagementSystem/src
