¡Por supuesto! A continuación, te presento un **README** listo para usar en tu repositorio de GitHub. Este documento incluye un **meta-prompt universal** para mejorar otros prompts, adaptado a las mejores prácticas de los modelos Claude, DeepSeek y Gemini. Además, se proporciona una sección de referencias para respaldar las estrategias mencionadas.

---

# 🧠 Meta-Prompt Universal para Mejorar Prompts (según chatgpt)

> **Instrucciones para el modelo:**
>
> 1. **Perfil experto:** Según el contexto del prompt proporcionado, adopta el perfil de un experto relevante (por ejemplo, diseñador UX, desarrollador backend, redactor técnico, etc.).
> 2. **Evaluación del prompt original:**
>
>    * **Fortalezas:** Identifica los aspectos bien definidos o efectivos.
>    * **Debilidades:** Señala ambigüedades, falta de contexto o instrucciones poco claras.
> 3. **Mejora del prompt:**
>
>    * Reescribe el prompt para que sea más claro, específico y eficaz.
>    * Asegúrate de que incluya:
>
>      * Objetivo bien definido.
>      * Contexto suficiente.
>      * Instrucciones claras y sin ambigüedades.
>      * Formato de salida esperado.
> 4. **Versión optimizada (opcional):** Si es pertinente, proporciona una versión aún más refinada del prompt para obtener mayor precisión o creatividad.
>
> **Prompt original a evaluar:**
>
> ```
> [Inserta aquí el prompt original]
> ```

---

## 🛠️ Adaptaciones Específicas por Modelo

### Claude (Anthropic)

Claude responde eficazmente a prompts estructurados con etiquetas XML. Utiliza las siguientes etiquetas para organizar tu prompt:

```xml
<task>Describe la tarea que debe realizar el modelo.</task>
<context>Proporciona el contexto necesario para entender la tarea.</context>
<instructions>Instrucciones claras y específicas para completar la tarea.</instructions>
<output_format>Especifica el formato esperado de la respuesta.</output_format>
<example>Incluye ejemplos si es necesario para ilustrar la tarea.</example>
```

*Ejemplo:*

```xml
<task>Mejorar un prompt existente.</task>
<context>El prompt actual carece de claridad y especificidad.</context>
<instructions>Reescribe el prompt para que sea claro, específico y eficaz, siguiendo las mejores prácticas de ingeniería de prompts.</instructions>
<output_format>Proporciona el nuevo prompt en formato de texto plano.</output_format>
<example>Prompt original: "Escribe sobre el clima."</example>
```

**Referencias:**

* [Prompt engineering overview - Anthropic API](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)
* [Claude 4 prompt engineering best practices - Anthropic API](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/claude-4-best-practices)

---

### DeepSeek

DeepSeek se beneficia de prompts claros, concisos y estructurados. Sigue estas pautas:

* **Claridad:** Define claramente la tarea o pregunta.
* **Brevedad:** Usa un lenguaje conciso para evitar sobrecargar de información.
* **Especificidad:** Indica directamente el formato de salida o detalles deseados.
* **Enfoque paso a paso:** Instruye al modelo para que siga una secuencia lógica en su razonamiento.

*Ejemplo:*

```
Actúa como un experto en ingeniería de prompts. Evalúa el siguiente prompt y proporciona una versión mejorada que sea clara, específica y eficaz. Sigue los siguientes pasos:

1. Analiza el prompt original y señala sus fortalezas y debilidades.
2. Reescribe el prompt para mejorar su claridad y especificidad.
3. (Opcional) Proporciona una versión aún más optimizada si es necesario.

Prompt original:
"Escribe sobre el clima."
```

**Referencias:**

* [Prompting DeepSeek-R1 - Introduction - Together AI](https://docs.together.ai/docs/prompting-deepseek-r1)
* [Tips for Prompting deepseek-R1 to Improve Accuracy and ... - Reddit](https://www.reddit.com/r/DeepSeek/comments/1ia6bcg/tips_for_prompting_deepseekr1_to_improve_accuracy/)

---

### Gemini (Google)

Gemini responde mejor a prompts que incluyen instrucciones claras, contexto adicional y ejemplos. Utiliza las siguientes estrategias:

* **Instrucciones claras y específicas:** Define claramente lo que se espera del modelo.
* **Información contextual:** Proporciona detalles adicionales que ayuden al modelo a entender la tarea.
* **Ejemplos:** Incluye ejemplos que ilustren el tipo de respuesta esperada.
* **Prefijos:** Usa prefijos para guiar al modelo en la generación de la respuesta.

*Ejemplo:*

```
Eres un experto en ingeniería de prompts. Tu tarea es mejorar el siguiente prompt para que sea más claro y específico.

Prompt original:
"Escribe sobre el clima."

Ejemplo de prompt mejorado:
"Redacta un artículo de 500 palabras que describa las condiciones climáticas actuales en la Ciudad de México, incluyendo temperatura, humedad y pronóstico para los próximos tres días."
```

**Referencias:**

* [Prompt design strategies | Gemini API | Google AI for Developers](https://ai.google.dev/gemini-api/docs/prompting-strategies)
* [Tips to write prompts for Gemini - Google Workspace Learning Center](https://support.google.com/a/users/answer/14200040?hl=en)

---

## 📚 Referencias Generales

* [Prompt engineering overview - Anthropic API](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)
* [Prompting DeepSeek-R1 - Introduction - Together AI](https://docs.together.ai/docs/prompting-deepseek-r1)
* [Prompt design strategies | Gemini API | Google AI for Developers](https://ai.google.dev/gemini-api/docs/prompting-strategies)

---

Este README está diseñado para ayudarte a implementar prácticas efectivas de ingeniería de prompts en tus proyectos. Si deseas aplicar este meta-prompt a un caso específico o necesitas asistencia adicional, no dudes en solicitarlo.
