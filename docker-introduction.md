# ¡Conoce Docker! 🐳

¿Te ha pasado que tu aplicación funciona perfecto en tu PC pero falla en otro entorno? Docker está aquí para evitar ese dolor de cabeza. Es una plataforma que te permite *empaquetar tu aplicación con todo lo necesario* (código, librerías, dependencias) en algo llamado **contenedor**. Así, te aseguras de que siempre funcione igual, en cualquier lugar 🌍.

## ¿Qué es un Contenedor? ¿Y una Imagen? 🔍

- **Contenedor:** Es como una mini computadora virtual, que corre tu aplicación de manera rápida, ligera y aislada.
- **Imagen:** Es la plantilla que se usa para construir un contenedor. Define qué software, archivos y configuraciones necesita tu aplicación.

### ¿Cómo se conectan? Observa este esquema 🧠

```mermaid
graph TD
    Imagen[Imagen 🖼️] --> Contenedor[Contenedor 📦]
    Contenedor --> App[Tu app corriendo 🚀]
