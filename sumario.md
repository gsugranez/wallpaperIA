# Wallpaper IA

## Objetivo

Wallpaper IA es un proyecto personal para investigar y desarrollar, de forma
progresiva, un mundo 3D vivo que pueda visualizarse como fondo de escritorio de
Windows. La idea es observar una pequeña escena que permanece en ejecución y
evoluciona con el tiempo, con espacio para añadir comportamientos e interacción
en fases futuras.

## Primer prototipo previsto

El primer prototipo, que todavía no se ha comenzado, será deliberadamente
pequeño: una isla o mundo 3D de estética low-poly o voxel, una cámara fija o casi
fija y un personaje que se desplaza automáticamente con una lógica local
sencilla. El flujo que se quiere demostrar es ejecutar la simulación, renderizar
la escena en tiempo real, mostrarla como wallpaper de Windows y poder iniciar
esa visualización con Windows. Esta descripción es un objetivo futuro; este
repositorio inicial no contiene código, escenas ni recursos del juego.

## Entorno de trabajo

- **Perfil de VS Code `Wallpaper IA`:** perfil independiente para mantener la
  apariencia y los atajos de este proyecto separados del perfil habitual y del
  perfil `Administrador`. Se busca el tema Monokai y los atajos de Sublime Text
  3, sin extensiones adicionales salvo las imprescindibles para esta base.
- **`wallpaperIA.code-workspace`:** punto de entrada principal y versionado del
  proyecto. Mantiene ajustes generales y selecciona PowerShell 7 como terminal
  predeterminada en Windows. No presupone un motor, lenguaje ni framework.
- **Plataforma inicial:** el resultado está orientado a Windows por su destino
  como fondo de escritorio y su posible inicio automático. PowerShell 7 será la
  terminal inicial en Windows; esto no impide evaluar otras herramientas si
  existe una razón técnica.

## Decisiones técnicas pendientes

1. **Ejecución y renderizado 3D:** comparar Godot, Unity, Three.js/WebGL y otras
   alternativas ligeras, sin elegir todavía.
2. **Visualización como wallpaper en Windows:** comparar Wallpaper Engine,
   Lively Wallpaper, una integración propia con Windows y otras opciones, sin
   elegir todavía.
3. **Arquitectura de ejecución y arranque:** determinar cómo mantener la
   simulación funcionando, cómo integrarla con el wallpaper elegido y cómo
   habilitar el inicio automático.
4. **Necesidades de interacción y evolución:** revisar más adelante la
   interacción, persistencia, comportamientos autónomos e IA local según el
   alcance que se decida.

La comparación deberá considerar facilidad de desarrollo, consumo de
CPU/GPU/RAM, ejecución continua, integración con Windows, compatibilidad con
wallpapers, arranque automático, gráficos 3D, capacidad futura de interacción e
IA local, mantenimiento y portabilidad.

## Evolución del proyecto

El proyecto comienza con el entorno y el repositorio preparados, sin una
tecnología gráfica o de wallpaper seleccionada. Esta sección recogerá en futuros
commits las decisiones y avances técnicos relevantes, no un registro de
comandos.
