# 🧠 LangChain + LangGraph + Agentes de IA

![LangChain](../assets/covers/langchain.png)

> Ruta de aprendizaje para construir aplicaciones con Inteligencia Artificial Generativa, agentes inteligentes y flujos avanzados utilizando LangChain, LangGraph y Python.

---

# 📌 Información del curso

| Información | Detalle |
|------------|---------|
| Tecnología | LangChain + LangGraph |
| Lenguaje | Python |
| Área | Inteligencia Artificial Generativa |
| Nivel | Intermedio → Avanzado |
| Plataforma | Udemy |
| Estado | ⬜ Pendiente |

🔗 Curso:

https://www.udemy.com/course/curso-completo-langchain-langgraph-y-agentes-ia-con-python/

---

# 🚀 Objetivo del curso

Aprender a desarrollar aplicaciones modernas basadas en modelos de lenguaje (LLM), utilizando frameworks especializados para crear:

- Aplicaciones con contexto.
- Sistemas RAG.
- Agentes inteligentes.
- Automatizaciones con IA.
- Flujos de trabajo autónomos.

---

# 🎯 ¿Por qué aprender LangChain?

Un modelo como OpenAI puede responder preguntas, pero una aplicación real necesita más capacidades.

Ejemplo:

Un chatbot básico:

```
Usuario

  |

Pregunta

  |

LLM

  |

Respuesta
```

Un agente inteligente:

```
Usuario

  |

Agente IA

  |

Decide qué hacer

  |

Usa herramientas

  |

Consulta información

  |

Genera respuesta
```

---

# 🧠 Conceptos fundamentales de LLM

## Large Language Models

Los LLM son modelos entrenados con grandes cantidades de información capaces de:

- Comprender texto.
- Generar respuestas.
- Resumir información.
- Analizar contenido.
- Crear código.

Ejemplos:

- GPT.
- Claude.
- Gemini.
- Llama.

---

# 🔗 LangChain

LangChain es un framework para construir aplicaciones alrededor de modelos de lenguaje.

Permite integrar:

- Modelos IA.
- Bases de datos.
- APIs.
- Herramientas.
- Memoria.
- Documentos.

Arquitectura:

```
Aplicación

   |

LangChain

   |

LLM

   |

Herramientas externas
```

---

# 📚 Componentes principales de LangChain

## 1. Modelos

Permite trabajar con diferentes proveedores:

- OpenAI.
- Anthropic.
- Google.
- Modelos locales.

---

## 2. Prompts

Los prompts definen cómo interactúa la IA.

Ejemplo:

```
Eres un asistente experto en programación.

Explica el siguiente código:
```

Aprenderás:

- Plantillas.
- Variables.
- Roles.
- Contexto.

---

# 3. Chains

Las cadenas permiten combinar pasos.

Ejemplo:

```
Pregunta

 ↓

Buscar información

 ↓

Procesar datos

 ↓

Generar respuesta
```

---

# 4. Memory

Permite que una aplicación recuerde información.

Ejemplo:

```
Usuario:

Mi nombre es Ricardo


IA:

Hola Ricardo
```

Tipos:

- Conversational Memory.
- Buffer Memory.
- Persistent Memory.

---

# 5. Embeddings

Los embeddings convierten información en vectores.

Ejemplo:

```
Texto

   ↓

Embedding

   ↓

Vector

   ↓

Búsqueda semántica
```

Se utilizan para:

- Buscar documentos.
- Crear RAG.
- Recuperar información.

---

# 📚 RAG (Retrieval Augmented Generation)

RAG permite que una IA consulte información externa.

Ejemplo:

```
Documento empresarial

        |

Vector Database

        |

Usuario pregunta

        |

IA responde usando documentos
```

Aplicaciones:

- Chat con PDFs.
- Asistentes empresariales.
- Bases de conocimiento.

---

# 🕸️ LangGraph

LangGraph permite crear flujos de agentes complejos.

Mientras LangChain conecta componentes:

```
LangChain

A → B → C
```

LangGraph permite crear grafos:

```
        Inicio

          |

      Analizar

      /      \

 Buscar    Responder

      \      /

        Final
```

---

# 🤖 Agentes de IA

Un agente puede:

1. Recibir una tarea.
2. Analizar la situación.
3. Elegir herramientas.
4. Ejecutar acciones.
5. Entregar resultados.

Ejemplo:

```
Usuario:

"Busca ventas del mes y genera reporte"


Agente:

1. Consulta base de datos

2. Analiza información

3. Genera documento

4. Envía resultado
```

---

# 🛠️ Herramientas (Tools)

Los agentes pueden utilizar herramientas externas:

Ejemplos:

- APIs.
- Bases de datos.
- Calculadoras.
- Buscadores.
- Sistemas internos.

Arquitectura:

```
Agente IA

    |

Tools

 ┌───────┬────────┐
 API   DB    Files
```

---

# 🏗️ Proyectos que podrás construir

## Chat con documentos

Características:

✅ Subir PDF

✅ Crear embeddings

✅ Buscar información

✅ Responder preguntas

---

## Asistente empresarial

Ejemplo:

```
Empleado

 |

Agente IA

 |

Documentación interna
```

---

## Agente de análisis

Puede:

- Consultar datos.
- Crear reportes.
- Generar conclusiones.

---

# 📋 Checklist de aprendizaje

## Fundamentos IA

- [ ] LLM
- [ ] Tokens
- [ ] Prompts
- [ ] Contexto

## LangChain

- [ ] Models
- [ ] Chains
- [ ] Prompts
- [ ] Memory
- [ ] Embeddings

## RAG

- [ ] Vector databases
- [ ] Retrieval
- [ ] Document loaders
- [ ] Context augmentation

## Agentes

- [ ] Tools
- [ ] Agents
- [ ] LangGraph
- [ ] Workflows
- [ ] Autonomous systems

---

# 🔗 Recursos oficiales

## LangChain

https://python.langchain.com/

## LangGraph

https://langchain-ai.github.io/langgraph/

## OpenAI

https://platform.openai.com/docs

---

# 🚀 Después de LangChain

Continuaremos con:

```
LangChain

      |

Agentes IA

      |

Automatización

      |

n8n + MCP
```

---

# 🏆 Resultado esperado

Al finalizar podrás:

✅ Crear aplicaciones con LLM.

✅ Implementar RAG.

✅ Crear agentes inteligentes.

✅ Diseñar flujos con LangGraph.

✅ Integrar IA con aplicaciones reales.

---