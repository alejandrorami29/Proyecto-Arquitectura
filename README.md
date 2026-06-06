AUTOGREEN

AutoGreen es un proyecto desarrollado en Arduino que simula el funcionamiento de un invernadero inteligente mediante el monitoreo de variables ambientales y la activación automática de diferentes actuadores.

El sistema evalúa continuamente condiciones de temperatura, humedad del suelo y luminosidad, tomando decisiones automáticas para mantener un ambiente adecuado para el crecimiento de las plantas.

Este proyecto fue desarrollado como parte del curso de Arquitectura de Computadoras I.

Objetivos:

Automatizar el monitoreo de variables ambientales.
Simular el comportamiento de un invernadero inteligente.
Implementar reglas de control utilizando Arduino.
Visualizar información en tiempo real mediante una pantalla LCD.
Demostrar el funcionamiento de actuadores según las condiciones del entorno.

Tecnologías implementadas:
Arduino UNO
Wokwi Simulator
C++
LCD 16x2 con interfaz I2C

Componentes del Sistema:
Entrada de Datos (Simulados)

El sistema utiliza valores simulados para representar:

Temperatura (°C)
Humedad del suelo (%)
Luminosidad (lux)

Los valores cambian automáticamente cada 10 segundos para demostrar distintos escenarios de funcionamiento.

Actuadores
Actuador	Función
Ventilador	Reduce la temperatura cuando existe exceso de calor
Bomba de Riego	Humedece el suelo cuando detecta sequedad
Calefactor	Incrementa la temperatura cuando hace frío
Luz Auxiliar	Proporciona iluminación cuando la luminosidad es baja
📺 Pantalla LCD

La pantalla LCD muestra:

Temperatura actual
Estado de la bomba de riego

Ejecución:
En Wokwi
Abrir el proyecto en Wokwi.
Ejecutar la simulación.
Observar los cambios automáticos cada 10 segundos.
Verificar el comportamiento de los actuadores.
Monitorear la información mostrada en la pantalla LCD.

Conclusión
AutoGreen demuestra cómo la automatización puede aplicarse al sector agrícola mediante el uso de microcontroladores. A través de reglas simples de control, el sistema es capaz de monitorear condiciones ambientales y responder automáticamente para mantener un entorno adecuado para el crecimiento de las plantas.

Integrantes
René Alejandro Ramírez Mendoza
José Antonio Ortega Lorenzo
