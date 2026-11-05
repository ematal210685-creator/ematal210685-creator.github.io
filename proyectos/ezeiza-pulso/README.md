# EZEIZA PULSO
## Sistema de Gestión del Bienestar

**Estado:** planificación inicial.  
**Responsable:** proyecto individual en etapa de aprendizaje y desarrollo.  
**Ámbito de referencia:** Municipio de Ezeiza, Buenos Aires, Argentina.

> EZEIZA PULSO es una propuesta en etapa de planificación. No es un sistema construido, probado, aprobado ni implementado por el Municipio de Ezeiza. La referencia visual del tótem es un concepto preliminar, no un prototipo físico validado.

## 1. Problema que buscamos abordar

La propuesta parte de una pregunta que todavía debe comprobarse mediante relevamiento:

**¿Cómo facilitar que las personas accedan, de manera sencilla y autónoma, a información general sobre bienestar y hábitos saludables en un espacio público?**

La hipótesis inicial es que una herramienta digital clara y accesible podría ayudar a acercar información introductoria sobre actividad física, alimentación y hábitos cotidianos, sin reemplazar la orientación de profesionales.

Antes de afirmar que existe una necesidad concreta o que la solución produce beneficios, será necesario conocer a las personas destinatarias, sus dificultades de acceso a información y la utilidad real de la herramienta.

## 2. Solución propuesta

Desarrollar primero un **prototipo de software local**, sencillo y accesible, que permita:

- Ingresar datos básicos como peso y altura.
- Validar que los datos ingresados tengan un formato y valores aceptables.
- Calcular y mostrar el índice de masa corporal (IMC) como referencia orientativa, con sus limitaciones claramente explicadas.
- Presentar información general y comprensible sobre hábitos saludables, actividad física y alimentación.
- Utilizar una interfaz simple, pensada para pantalla y manejo accesible.

El objetivo de la primera etapa no es fabricar un tótem: es comprobar si el software se entiende, funciona correctamente y resulta útil para las personas que lo prueben.

## 3. Alcance y límites

### Incluido en el planteo inicial

- Bienestar general y promoción de hábitos saludables.
- Prototipo de software local como primera versión.
- Interfaz accesible y fácil de utilizar.
- Contenido informativo general.
- Pruebas de funcionamiento y usabilidad.

### Fuera del alcance

- Diagnósticos médicos o recomendaciones clínicas personalizadas.
- Triaje, atención de urgencias o reemplazo de profesionales.
- Historias clínicas, turnos o gestión de pacientes.
- Uso como dispositivo médico o instalación en un ámbito sanitario.
- Sensores o mediciones biométricas automáticas en la primera versión.

El IMC no diagnostica el estado de salud de una persona y tiene limitaciones según edad y otras condiciones. La población destinataria y la forma de presentar este dato deberán definirse antes de probarlo con usuarios. La primera versión deberá evitar almacenar datos personales innecesarios.

## 4. Etapas de trabajo

| Etapa | Trabajo previsto | Resultado que permitirá avanzar |
|---|---|---|
| 1. Definición | Precisar usuarios, necesidad, funciones y límites | Documento de requisitos iniciales |
| 2. Diseño | Diseñar pantallas, navegación y mensajes | Boceto de interfaz revisable |
| 3. Desarrollo | Programar el prototipo local y sus validaciones | Primera versión ejecutable |
| 4. Pruebas técnicas | Comprobar cálculos, entradas inválidas y estabilidad | Registro de pruebas y errores |
| 5. Pruebas de uso | Observar si las personas comprenden y completan las tareas | Resultados de usabilidad |
| 6. Evaluación | Revisar resultados y decidir ajustes o continuidad | Informe de evaluación del MVP |

Solo después de validar el software tendría sentido estudiar una posible implementación física en un espacio público, empezando por un único equipo. En esa etapa se podría comparar la fabricación propia con la compra de un tótem comercial y evaluar infraestructura, mantenimiento, privacidad, costos y autorizaciones. No se presupone que esa implementación vaya a realizarse.

## 5. ¿Cómo vamos a medir si funciona?

No alcanza con que el programa abra o muestre una pantalla. Hay que comprobar si cumple su propósito. Para eso se proponen indicadores iniciales:

| Indicador | Cómo medirlo | Qué nos permite saber |
|---|---|---|
| Finalización de la consulta | Consultas completadas / consultas iniciadas × 100 | Si las personas pueden terminar el recorrido |
| Tiempo de uso | Tiempo desde el inicio hasta el resultado | Si el recorrido es razonablemente ágil |
| Errores de ingreso | Cantidad de entradas inválidas detectadas y tratadas correctamente | Si las validaciones funcionan |
| Exactitud del cálculo | Comparar resultados del sistema con casos de prueba calculados de forma independiente | Si el cálculo está implementado correctamente |
| Comprensión | Preguntar al participante qué significa el resultado y qué límites tiene | Si la información se entiende |
| Facilidad de uso | Encuesta breve al finalizar la prueba | Si la interfaz resulta sencilla |
| Estabilidad | Pruebas realizadas sin cierres, bloqueos ni fallos | Si el prototipo funciona de manera consistente |

**Importante:** todavía no hay resultados ni metas alcanzadas. Primero se definirá un protocolo de prueba y una línea de base. Los porcentajes, tiempos y criterios de aceptación se fijarán antes de evaluar el prototipo, no después de conocer los resultados.

No se utilizará como indicador de éxito una supuesta mejora de salud de las personas: el MVP no está diseñado ni validado para demostrar resultados clínicos.

## 6. Qué falta definir y validar

- A qué grupo de personas estará dirigida la primera prueba.
- Qué contenidos informativos se incluirán y cómo se revisará su calidad.
- Si corresponde incluir el IMC y para qué población, con qué advertencias.
- Qué requisitos de accesibilidad tendrá la interfaz.
- Qué datos se procesarán y cómo se evitará conservar información personal innecesaria.
- Cuántas personas participarán en las pruebas y bajo qué protocolo.
- Qué criterios objetivos determinarán si el MVP es suficientemente útil para continuar.

## 7. Estado actual

En esta etapa existe una idea de proyecto, una definición preliminar de alcance y una referencia visual conceptual del posible tótem. **Todavía no hay software desarrollado, pruebas realizadas ni resultados medidos.**

El siguiente paso concreto es convertir esta propuesta en requisitos funcionales y diseñar las primeras pantallas del prototipo.

## 8. Principio de trabajo

EZEIZA PULSO se desarrollará por etapas: definir, construir, probar, medir, documentar y corregir. Cada avance se presentará según su estado real, diferenciando ideas, diseños, funcionalidades implementadas y resultados comprobados.
