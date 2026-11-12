# Taller de desarrollo de videojuegos 2D · DrawFight

**Proyecto práctico en Unity y C# utilizado para apoyar el taller «Crea tu primer juego 2D en Unity» que impartí.** El prototipo de plataformas permite enseñar mecánicas fundamentales mediante un proyecto editable.

![Vista del juego DrawFight](https://i.postimg.cc/BbcByPyn/game1.jpg)

## Objetivos de aprendizaje

- Organizar escenas, objetos y componentes en Unity 2D.
- Programar desplazamiento horizontal, salto y orientación del personaje.
- Implementar seguimiento de cámara y límites de desplazamiento.
- Detectar interacciones con objetos recolectables, obstáculos y meta.
- Controlar puntuación, menús, victoria y derrota.

## Componentes del proyecto

| Script | Concepto |
| --- | --- |
| [PlayerMovement.cs](Assets/Scripts/PlayerMovement.cs) | Movimiento, física 2D, salto y cambio de orientación |
| [CameraFollow.cs](Assets/Scripts/CameraFollow.cs) | Seguimiento suavizado de cámara y límites |
| [objectCollect.cs](Assets/Scripts/objectCollect.cs) | Triggers, recolección, obstáculos y condición de victoria |
| [GameManager.cs](Assets/Scripts/GameManager.cs) | Puntuación, reinicio y estados de victoria/derrota |
| [MainMenu.cs](Assets/Scripts/MainMenu.cs) | Menú, pausa y persistencia básica con PlayerPrefs |

## Capturas históricas

| Pantalla de inicio | Vista del nivel |
| --- | --- |
| ![Inicio de DrawFight](https://i.postimg.cc/gkmDh4XX/Start.jpg) | ![Nivel de DrawFight](https://i.postimg.cc/BbcByPyn/game1.jpg) |

*Imágenes alojadas externamente; su disponibilidad depende del proveedor.*

## Cómo abrirlo

1. Instala Unity Hub y **Unity 2023.2.20f1**, según [ProjectVersion.txt](ProjectSettings/ProjectVersion.txt).
2. Clona el repositorio: `git clone https://github.com/isaiassolis/unity-2d-platformer-workshop.git`.
3. Abre el proyecto en Unity Hub.
4. Carga `Assets/Scenes/SampleScene.unity` y presiona **Play**.
5. El código utiliza los ejes **Horizontal** y **Jump** del sistema de entrada de Unity.

El repositorio también contiene un ejecutable histórico en `Ejecutable/`; no se ha verificado su ejecución ni su compatibilidad actual. No se realizaron compilaciones ni pruebas del juego durante esta actualización del README.

## Alcance educativo

Este repositorio conserva un **prototipo de aprendizaje**, no un producto comercial terminado. Las mecánicas pueden servir como punto de partida para ejercicios de programación, diseño de niveles y ampliaciones guiadas. Antes de reutilizar recursos de terceros, revisa sus licencias específicas.

**Proyecto relacionado:** [Taller Chrome Dino en Unity](https://github.com/isaiassolis/unity-2d-chrome-dino-workshop).

---

[Perfil profesional y otros proyectos de formación](https://github.com/isaiassolis)
