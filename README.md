# 🚂 Proyecto Java - Sistema de Vehículos con Herencia, Composición y Menú Interactivo

Este proyecto en Java modela un sistema de transporte mediante una jerarquía de clases que simula distintos tipos de vehículos, con un enfoque en **POO (Programación Orientada a Objetos)**, uso de **interfaces**, **herencia**, **composición**, **enum**, y un menú interactivo en consola para probar los comportamientos.

---
🚘 Vehículos Soportados
Coche: siempre tiene 4 ruedas.

Camion: 10 ruedas.

Bicicleta: 2 ruedas.

Locomotora: 8 ruedas (obligatoria en cualquier tren).

Vagon: puede tener 4 o 6 ruedas, y un número aleatorio de asientos (0-100).

Tren: compuesto por 1 locomotora obligatoria y 0 o más vagones.

🎮 Menú Interactivo
El programa incluye un menú por consola que permite:

📋 Ver todos los vehículos

➕ Añadir vagón a un tren

❌ Eliminar un vagón aleatorio

🧹 Eliminar todos los vagones de un tren

🔍 Buscar vagones por número de asientos

🚪 Salir del programa

🧠 Objetivos Didácticos
Aplicar herencia y polimorfismo

Implementar interfaces

Usar enum para control de atributos

Aplicar composición (Tren → Locomotora + Vagones)

Manipular colecciones (ArrayList)

Desarrollar menús interactivos con Scanner

🛠 Requisitos Técnicos
Java 8 o superior

IDE recomendado: IntelliJ IDEA o VSCode con extensión de Java

No requiere dependencias externas

🧪 Vehículos preconfigurados
Se cargan al inicio 6 vehículos de ejemplo:

✅ Coche rojo

✅ Camión verde

✅ Bicicleta azul

✅ Tren sin vagones

✅ Tren con 2 vagones de distintos colores

✅ Tren con un vagón especial (6 ruedas) y uno normal (4 ruedas), cada uno con su color

🧾 Ejemplo de salida
text
Copiar
Editar
--- MENÚ VEHÍCULOS ---
1. Mostrar todos los vehículos
2. Añadir vagón a un tren
3. Eliminar vagón aleatorio de un tren
4. Eliminar todos los vagones de un tren
5. Buscar vagones por número de asientos
0. Salir
Seleccione una opción:
✨ ¿Siguientes pasos?
Añadir persistencia (guardar/cargar vehículos desde archivo)

Añadir nuevos tipos de vagones o trenes

Crear una interfaz gráfica (Swing/JavaFX)

Implementar validaciones de entrada más robustas

🧑‍💻 Autor
Desarrollado por Dani — proyecto educativo de POO en Java.


## 🧱 Estructura de Clases

```text
Vehiculo (abstracto)
├── Coche
├── Camion
├── Bicicleta
├── Tren
│   ├── Locomotora
│   └── Vagon

