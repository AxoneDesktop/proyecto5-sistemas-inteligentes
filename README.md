# Proyecto 5: Sistemas inteligentes y sus aplicaciones en la actualidad

## Fundamentos teóricos

### ¿Qué es un sistema inteligente?

Según la RAE, un **sistema inteligente** es aquel controlado por computadora capaz de responder a cambios del entorno para establecer las condiciones óptimas de funcionamiento sin intervención humana.

### Cuestiones fundacionales de la IA (Conferencia de Dartmouth, 1956)

En la conferencia de Dartmouth de 1956, considerada el nacimiento formal de la Inteligencia Artificial, los investigadores plantearon las siguientes cuestiones fundamentales:

- **¿Pueden las máquinas pensar?** — La cuestión más filosófica, que llevó al famoso Test de Turing.
- **¿Pueden las máquinas aprender de la experiencia?** — Base del aprendizaje automático actual.
- **¿Pueden las máquinas usar el lenguaje?** — Fundamento del procesamiento del lenguaje natural.
- **¿Pueden las máquinas resolver problemas de forma abstracta?** — Base de los sistemas de razonamiento y planificación.
- **¿Pueden las máquinas mejorarse a sí mismas?** — Precursora de las redes neuronales y el aprendizaje profundo.

### Características de un sistema inteligente

Para que un sistema informático pueda considerarse inteligente, debe cumplir (total o parcialmente) las siguientes capacidades:

| # | Característica | Descripción |
|---|---|---|
| 1 | **Percepción** | Capacidad de captar información del entorno mediante sensores, cámaras, micrófonos u otros dispositivos de entrada |
| 2 | **Procesamiento del lenguaje natural (PLN)** | Capacidad de comprender y generar lenguaje humano, tanto escrito como hablado |
| 3 | **Razonamiento** | Capacidad de inferir conclusiones a partir de datos, aplicar reglas lógicas y tomar decisiones fundamentadas |
| 4 | **Aprendizaje** | Capacidad de mejorar su rendimiento a partir de la experiencia y los datos, sin ser reprogramado explícitamente |
| 5 | **Planificación** | Capacidad de establecer secuencias de acciones para alcanzar objetivos futuros |
| 6 | **Autonomía** | Capacidad de operar de forma independiente sin intervención humana continua |
| 7 | **Adaptabilidad** | Capacidad de ajustar su comportamiento ante cambios en el entorno o en los datos de entrada |
| 8 | **Interacción social** | Capacidad de comunicarse e interactuar con humanos u otros sistemas de manera efectiva |

### Principios éticos de la IA

Al desarrollar sistemas inteligentes debemos tener en cuenta los siguientes principios éticos fundamentales:

- **Transparencia**: Los sistemas deben ser explicables; los usuarios deben entender cómo se toman las decisiones.
- **Equidad y no discriminación**: Los algoritmos no deben perpetuar ni amplificar sesgos existentes.
- **Privacidad**: Los datos personales deben ser protegidos y usados de forma responsable.
- **Seguridad**: Los sistemas deben ser robustos y seguros, sin causar daño.
- **Responsabilidad**: Debe existir un humano responsable de las decisiones que toma el sistema.
- **Beneficencia**: La IA debe estar diseñada para beneficiar a la humanidad.

---

## Aplicaciones actuales de la Inteligencia Artificial

A continuación se analizan tres aplicaciones actuales de IA en tres campos diferentes, identificando qué características de sistema inteligente cumple cada una.

---

### 1. Diagnóstico médico por imagen con IA — Campo: Sanidad

#### Descripción

Los sistemas de IA aplicados al diagnóstico por imagen médica utilizan redes neuronales convolucionales (CNN) y técnicas de deep learning para analizar radiografías, mamografías, tomografías y resonancias magnéticas. Estas herramientas asisten a los radiólogos detectando patologías como tumores, fracturas o enfermedades pulmonares con una precisión que en muchos casos iguala o supera a la de los especialistas humanos.

**Ejemplos reales**: Google Health (detección de cáncer de mama), DeepMind (predicción de estructura de proteínas con AlphaFold), Aidoc (análisis de tomografías en urgencias).

#### Análisis de características

| Característica | ¿Se cumple? | Justificación |
|---|---|---|
| **Percepción** | ✅ Sí | Capta imágenes médicas (radiografías, TAC, resonancias) como datos de entrada y extrae información visual relevante |
| **PLN** | ⚠️ Parcialmente | Algunos sistemas generan informes textuales automáticos, pero no es su función principal |
| **Razonamiento** | ✅ Sí | Realiza inferencias a partir de patrones en imágenes para detectar anomalías y clasificar patologías |
| **Aprendizaje** | ✅ Sí | Se entrena con miles de imágenes etiquetadas por especialistas y mejora con más datos |
| **Planificación** | ❌ No | No planifica acciones futuras; su función es analizar y diagnosticar, no definir tratamientos |
| **Autonomía** | ⚠️ Parcialmente | Puede funcionar de forma autónoma en el análisis, pero legalmente siempre requiere supervisión médica |
| **Adaptabilidad** | ✅ Sí | Se adapta a distintos tipos de imagen y puede reentrenarse con nuevos datos de poblaciones diferentes |
| **Interacción social** | ⚠️ Parcialmente | Interactúa con médicos a través de interfaces, pero no mantiene un diálogo natural |

---

### 2. Vehículos autónomos — Campo: Transporte

#### Descripción

Los vehículos autónomos representan una de las aplicaciones más complejas e integradoras de la IA. Combinan múltiples tecnologías: visión por computador, sensores LIDAR y radar, aprendizaje profundo, planificación de rutas y toma de decisiones en tiempo real. El objetivo es conducir un vehículo de forma segura sin intervención humana.

**Ejemplos reales**: Waymo (Google), Tesla Autopilot/FSD, Cruise (GM), Apollo (Baidu).

#### Análisis de características

| Característica | ¿Se cumple? | Justificación |
|---|---|---|
| **Percepción** | ✅ Sí | Utiliza cámaras, LIDAR, radar y ultrasonidos para percibir el entorno en 360° y en tiempo real |
| **PLN** | ⚠️ Parcialmente | Algunos vehículos aceptan comandos de voz, pero no es esencial para la conducción |
| **Razonamiento** | ✅ Sí | Toma decisiones complejas en fracciones de segundo: ceder el paso, esquivar obstáculos, interpretar señales |
| **Aprendizaje** | ✅ Sí | Se entrena con millones de kilómetros de datos de conducción y mejora con cada actualización del modelo |
| **Planificación** | ✅ Sí | Planifica rutas óptimas, anticipa movimientos de otros vehículos y peatones, y define trayectorias |
| **Autonomía** | ✅ Sí | Objetivo principal: conducir sin intervención humana (niveles SAE 4-5) |
| **Adaptabilidad** | ✅ Sí | Se adapta a condiciones meteorológicas, tráfico variable, obras en carreteras y situaciones imprevistas |
| **Interacción social** | ⚠️ Parcialmente | Interactúa con pasajeros y otros vehículos, pero la comunicación con peatones y otros conductores es limitada |

---

### 3. Modelos de lenguaje generativos (LLMs) — Campo: Tecnología y comunicación

#### Descripción

Los modelos de lenguaje de gran tamaño (Large Language Models o LLMs) como ChatGPT, Claude o Gemini representan un avance enorme en el procesamiento del lenguaje natural. Estos modelos, basados en la arquitectura Transformer, son capaces de generar texto coherente, responder preguntas, traducir idiomas, escribir código, resumir documentos y mantener conversaciones complejas.

**Ejemplos reales**: ChatGPT (OpenAI), Claude (Anthropic), Gemini (Google), LLaMA (Meta).

#### Análisis de características

| Característica | ¿Se cumple? | Justificación |
|---|---|---|
| **Percepción** | ⚠️ Parcialmente | Los modelos multimodales (GPT-4o, Gemini) pueden procesar imágenes y audio, pero no perciben el entorno físico directamente |
| **PLN** | ✅ Sí | Es su capacidad principal: comprenden y generan lenguaje natural con fluidez en múltiples idiomas |
| **Razonamiento** | ✅ Sí | Realizan razonamiento lógico, matemático y analítico, aunque con limitaciones en razonamiento formal |
| **Aprendizaje** | ✅ Sí | Se entrenan con enormes cantidades de texto y aprenden patrones lingüísticos, semánticos y de conocimiento |
| **Planificación** | ⚠️ Parcialmente | Pueden estructurar respuestas paso a paso y descomponer problemas, pero no planifican acciones en el mundo real |
| **Autonomía** | ⚠️ Parcialmente | Operan de forma autónoma respondiendo consultas, pero necesitan un prompt humano para activarse |
| **Adaptabilidad** | ✅ Sí | Se adaptan a diferentes contextos, tonos y tipos de tarea dentro de una conversación |
| **Interacción social** | ✅ Sí | Están diseñados específicamente para interactuar de forma natural y conversacional con humanos |

---

## Tabla comparativa resumen

| Característica | Diagnóstico médico por IA | Vehículos autónomos | LLMs (ChatGPT, etc.) |
|---|---|---|---|
| Percepción | ✅ | ✅ | ⚠️ |
| PLN | ⚠️ | ⚠️ | ✅ |
| Razonamiento | ✅ | ✅ | ✅ |
| Aprendizaje | ✅ | ✅ | ✅ |
| Planificación | ❌ | ✅ | ⚠️ |
| Autonomía | ⚠️ | ✅ | ⚠️ |
| Adaptabilidad | ✅ | ✅ | ✅ |
| Interacción social | ⚠️ | ⚠️ | ✅ |

**Leyenda**: ✅ Se cumple — ⚠️ Se cumple parcialmente — ❌ No se cumple

---

## Conclusiones

- **Los vehículos autónomos** son la aplicación que más características de sistema inteligente cumple (6 completas, 2 parciales), ya que integran percepción, razonamiento, aprendizaje, planificación, autonomía y adaptabilidad.
- **Cada campo aplica las capacidades de forma diferente**: la sanidad prioriza la percepción y el razonamiento, el transporte la autonomía y la planificación, y la comunicación el PLN y la interacción social.
- **Ninguna aplicación cumple todas las características al 100%**, lo que demuestra que la IA general (AGI) sigue siendo un objetivo a largo plazo.
- Es fundamental aplicar los **principios éticos** (transparencia, equidad, privacidad, seguridad, responsabilidad) en todos estos campos.

---

## Presentación

La presentación de la aplicación más interesante (Vehículos autónomos) se encuentra en el archivo `presentacion.pptx` de este repositorio.

---

## Referencias

- Russell, S. & Norvig, P. (2021). *Artificial Intelligence: A Modern Approach* (4th ed.). Pearson.
- Wikipedia: [Sistema inteligente](https://es.wikipedia.org/wiki/Sistema_inteligente)
- UNESCO: [Recomendación sobre la ética de la IA](https://www.unesco.org/es/artificial-intelligence/recommendation-ethics)
- SAE International: [Niveles de automatización de vehículos](https://www.sae.org/standards/content/j3016_202104/)
