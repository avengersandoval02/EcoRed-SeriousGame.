# EcoRed: El Desafío Sostenible 🌿💻

Prototipo funcional de Serious Game desarrollado en Unity para el **Previo 2** de la asignatura (Unidades Tecnológicas de Santander - UTS). El juego combina mecánicas de plataformas 2D con un enfoque educativo en **Green IT, ciberseguridad y eficiencia energética**.

---

## 👥 Autores / Desarrolladores
* **Miguel Angel Sandoval Cárdenas**
* **Institución:** Unidades Tecnológicas de Santander (UTS) - Bucaramanga
* **Proyecto:** Semillero de Investigación AZUL / Desarrollo de Contenidos Digitales y Multimediales

---

## 🎮 Características y Requisitos Implementados (Rúbrica Previo 2)
1. **Menú Principal Funcional:** Escena inicial con opciones de navegación (Jugar, Créditos emergentes y Salir).
2. **Sistema de Movimiento y Colisiones:** Desplazamiento fluido del personaje (`Player`) con colisionadores sólidos contra el entorno (*Tilemap*).
3. **Sistema de Diálogos con NPC:** Interacción mediante la tecla **E** con un personaje no jugable (Dra. Lin), mostrando narrativa introductoria sobre la crisis energética y los servidores globales mediante arreglos dinámicos en C#.
4. **Objetos Interactivos Educativos:** Terminales o carteles distribuidos en el mapa que muestran datos pedagógicos sobre optimización de código y consumo energético al presionar la tecla **E**.
5. **Sistema de Coleccionables:** 5 elementos interactivos distribuidos en el nivel que se recogen mediante *triggers* y suman progreso al inventario.
6. **HUD Funcional (Head-Up Display):** Interfaz permanente en pantalla que muestra el contador de coleccionables en tiempo real y el estado de la misión.

---

## 🛠️ Tecnologías y Herramientas Utilizadas
* **Motor de Juego:** Unity (Versión 6 / 6000)
* **Lenguaje de Programación:** C#
* **Interfaz Gráfica:** TextMeshPro (TMP)
* **Control de Versiones:** Git & GitHub

---

## 📂 Estructura del Repositorio
Para cumplir con los estándares de entrega y optimizar el peso del proyecto, este repositorio contiene estrictamente las carpetas esenciales:
* `Assets/` -> Contiene los scripts en C# (`NPCDialogue.cs`, `InteractableObject.cs`, `CollectibleItem.cs`, `GameHUDManager.cs`, `MainMenuManager.cs`), escenas (`MainMenu.unity`, `GameScene.unity`), sprites y materiales.
* `ProjectSettings/` -> Configuraciones globales del proyecto de Unity.

*(Nota: Las carpetas pesadas como `Library/`, `Logs/` y `Temp/` se encuentran excluidas mediante `.gitignore`).*

---

## 🚀 Cómo Ejecutar el Proyecto
1. Clona o descarga este repositorio en tu equipo.
2. Abre **Unity Hub** y selecciona **Add project from disk**.
3. Selecciona la carpeta raíz de este repositorio clonado.
4. Asegúrate de abrir la escena inicial en `Assets/Scenes/MainMenu.unity` y presiona **Play (▶️)**.
