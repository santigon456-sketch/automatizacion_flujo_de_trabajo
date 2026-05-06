# 🚀 Automatización de Carga de Pasantías - SIU Guaraní (FCM-UNL)

Este proyecto nace de la necesidad de resolver un desafío administrativo real mediante tecnología RPA (Robotic Process Automation). Representa no solo una solución técnica, sino un proceso de aprendizaje intensivo y superación de obstáculos en un entorno de gestión universitaria.

## 💡 El Problema: Una "Montaña" de Datos Manuales
En la **Facultad de Ciencias Médicas de la UNL**, se procesan aproximadamente **200 pasantías anuales**. Recientemente, se implementó la obligatoriedad de cargar estas actividades en el sistema **SIU Guaraní**, lo que generó un "backlog" o acumulación de tareas pendientes desde el año **2020**.

Realizar esta carga de forma manual era:
*   **Extremadamente tedioso:** Cientos de registros acumulados que requerían horas de atención repetitiva.
*   **Lento:** Un proceso que consumía tiempo valioso que podría dedicarse al análisis y mejora de procesos.
*   **Propenso a errores:** La transcripción manual de datos desde resoluciones y planillas siempre conlleva un riesgo.

## 🛠️ La Solución y el Desafío Técnico
Frente a esta situación, decidí buscar una alternativa eficiente. El resultado es un flujo desarrollado en **Power Automate Desktop** que automatiza el ciclo completo de carga.

### 🧠 Orgullo por el Proceso de Aprendizaje
Lo que más destaco de este proyecto es el esfuerzo detrás de su creación:
*   **Curva de aprendizaje:** Logré aprender y dominar los fundamentos de Power Automate en apenas **una semana** de trabajo intensivo.
*   **Venciendo al SIU Guaraní:** Este sistema es conocido por su complejidad técnica. Me enfrenté a una interfaz con **IDs dinámicos** que cambian en cada sesión y elementos que varían constantemente, lo que me obligó a diseñar una lógica de automatización robusta y adaptable.

## ⚙️ Capacidades Técnicas del Flujo
El flujo está diseñado para realizar las siguientes acciones de forma autónoma:
*   **Manejo de Excel:** Conexión y lectura de datos desde planillas de control (`ExcelInstance`).
*   **Procesamiento de PDF:** Extracción inteligente de texto de las Resoluciones del Consejo Directivo para validar la información.
*   **Automatización Web:** Navegación en Google Chrome, manejo de focos en ventanas y presión de botones en el portal de gestión académica.
*   **Lógica de Control:** Implementación de bucles (`For each`) y recortes de texto para asegurar que el dato correcto llegue al campo indicado.

## 📈 Impacto Real
*   **Ahorro Masivo de Tiempo:** Lo que antes tomaba días de trabajo manual, ahora se realiza de forma automática, permitiendo regularizar años de registros en una fracción del tiempo original.
*   **Precisión Total:** Se eliminó el factor de error humano en la carga de datos críticos de los alumnos.
*   **Satisfacción Personal:** Me siento muy orgulloso de haber transformado un proceso administrativo tradicional en una solución moderna y eficiente, demostrando que la tecnología es el mejor aliado de la gestión pública.

---
*Este proyecto es parte de mi camino hacia la Ciencia de Datos e IA, aplicando soluciones de automatización en entornos profesionales reales.*
