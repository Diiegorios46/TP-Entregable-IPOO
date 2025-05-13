# ✈️ TP - Entregable IPOO

Este proyecto es una entrega para la materia **IPOO (Introducción a la Programación Orientada a Objetos)**.  
Consiste en la simulación de un sistema de **gestión de viajes** en PHP, ejecutado por consola. Se modelan pasajeros, responsables, y diferentes tipos de pasajero con características particulares.

---

## 🧩 Estructura del sistema

El sistema permite:

- Crear un viaje con destino, código y capacidad.
- Agregar diferentes tipos de pasajeros:
  - Común
  - VIP
  - Con necesidades especiales
- Asignar responsable del viaje.
- Testear el funcionamiento general con un script de consola.

---

## 📁 Archivos principales

| Archivo                          | Descripción |
|----------------------------------|-------------|
| `Persona.php`                    | Clase base para representar a cualquier persona. |
| `Responsable.php`                | Representa al responsable del viaje (nombre, apellido, número de empleado, etc.). |
| `pasajero.php`                   | Clase pasajero común. |
| `pasajeroVip.php`                | Pasajero con beneficios VIP. |
| `pasajeroNecesidadesEspeciales.php` | Pasajero con requerimientos especiales. |
| `viaje.php`                      | Clase principal que gestiona la información del viaje. |
| `testViaje.php`                  | Script de prueba que permite ejecutar el sistema desde consola. |

---

## 🛠️ Cómo ejecutar el proyecto

### Requisitos

- PHP 7.x o superior instalado en tu máquina
- Terminal de sistema operativo (CMD, Bash, PowerShell, etc.)

### Instrucciones

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/TP-Entregable-IPOO.git
   cd TP-Entregable-IPOO
