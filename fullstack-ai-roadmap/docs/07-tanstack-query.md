# ⚡ TanStack Query - Gestión profesional de datos en aplicaciones Frontend

![TanStack Query](../assets/covers/tanstack-query.png)

> Ruta de aprendizaje para manejar datos remotos, caché y sincronización con APIs utilizando TanStack Query.

---

# 📌 Información del curso

| Información | Detalle |
|------------|---------|
| Tecnología | TanStack Query |
| Framework relacionado | Angular / React |
| Área | Frontend Development |
| Nivel | Intermedio |
| Estado | ⬜ Pendiente |

🔗 Curso:

https://www.youtube.com/watch?v=o79xZPy1cCk&list=PLCKuOXG0bPi3eW8TeqEuZzJ_v_Ur8Tpu4

---

# 🚀 Objetivo del curso

Aprender a gestionar información proveniente de servidores de manera eficiente utilizando TanStack Query.

El objetivo es mejorar la forma en que una aplicación frontend:

- Consume APIs.
- Guarda datos temporalmente.
- Actualiza información.
- Maneja estados de carga.
- Reduce peticiones innecesarias.

---

# 🎯 ¿Qué problema resuelve TanStack Query?

En una aplicación tradicional:

```
Component

    |

Service

    |

HTTP Request

    |

API
```

El desarrollador debe manejar manualmente:

- Loading.
- Errores.
- Caché.
- Actualizaciones.
- Reintentos.

Con TanStack Query:

```
Component

    |

TanStack Query

    |

API

```

La librería administra:

✅ Caché.

✅ Sincronización.

✅ Estados.

✅ Reintentos.

---

# 🧠 Conceptos fundamentales

# 1. Server State vs Client State

Una aplicación tiene diferentes tipos de información.

## Client State

Información interna de la aplicación:

Ejemplos:

- Menú abierto.
- Tema oscuro.
- Formulario temporal.

---

## Server State

Información que vive en un backend:

Ejemplos:

- Usuarios.
- Productos.
- Pedidos.
- Perfil.

TanStack Query está diseñado principalmente para Server State.

---

# 2. Queries

Una Query representa una consulta de información.

Ejemplo:

```
Obtener usuarios

Angular

   |

TanStack Query

   |

GET /users
```

Maneja automáticamente:

- Loading.
- Success.
- Error.
- Cache.

---

# 3. Mutations

Las mutations modifican información.

Ejemplos:

- Crear usuario.
- Actualizar producto.
- Eliminar registro.

Flujo:

```
Usuario

 |

Formulario

 |

Mutation

 |

API

 |

Actualizar cache
```

---

# 4. Caché inteligente

TanStack Query almacena temporalmente información.

Ejemplo:

Primera visita:

```
Angular

 |

API

 |

Datos
```

Segunda visita:

```
Angular

 |

Cache

 |

Respuesta inmediata
```

Beneficios:

- Mejor rendimiento.
- Menos tráfico.
- Mejor experiencia de usuario.

---

# 5. Estados de una petición

TanStack Query maneja estados como:

```text
idle

loading

success

error

refetching
```

Esto evita crear muchas variables manuales.

---

# 6. Revalidación automática

Los datos pueden actualizarse automáticamente.

Ejemplos:

- Al volver a abrir una pantalla.
- Cada cierto tiempo.
- Después de una modificación.

---

# 7. Manejo de errores

Permite controlar:

- Fallos de red.
- Errores del servidor.
- Reintentos.

Ejemplo:

```
API falla

    |

Retry automático

    |

Nueva petición
```

---

# 🏗️ Integración con Angular + NestJS

Arquitectura completa:

```
                 Angular

                    |

             TanStack Query

                    |

               HTTP Client

                    |

                 NestJS

                    |

              PostgreSQL
```

---

# 🛠️ Casos reales de uso

## Dashboard empresarial

Datos:

- Ventas.
- Usuarios.
- Reportes.

Necesidades:

- Actualización rápida.
- Caché.
- Gráficas.

---

## E-commerce

Productos:

```
Usuario entra

↓

Consulta productos

↓

Cache

↓

Navegación rápida
```

---

## Aplicaciones con IA

Ejemplo:

```
Usuario solicita análisis IA

        |

NestJS procesa

        |

OpenAI responde

        |

TanStack actualiza interfaz
```

---

# 📋 Checklist de aprendizaje

## Fundamentos

- [ ] Qué es Server State
- [ ] Queries
- [ ] Mutations
- [ ] Cache

## Aplicación

- [ ] Consultar APIs
- [ ] Actualizar datos
- [ ] Manejar errores
- [ ] Loading states

## Nivel profesional

- [ ] Invalidación de cache
- [ ] Refetch automático
- [ ] Optimistic Updates
- [ ] Persistencia

---

# 🔗 Recursos oficiales

## TanStack Query

https://tanstack.com/query/latest

## Angular

https://angular.dev/

---

# 🚀 Cómo se conecta con este roadmap

TanStack Query será utilizado junto con:

```
Angular

   +

NestJS

   +

OpenAI

   +

Aplicaciones empresariales
```

Ejemplos:

- Dashboards con IA.
- Sistemas SaaS.
- Paneles administrativos.
- Aplicaciones con datos en tiempo real.

---

# 🏆 Resultado esperado

Al finalizar podrás:

✅ Gestionar datos remotos profesionalmente.

✅ Crear aplicaciones frontend más rápidas.

✅ Reducir código repetitivo.

✅ Integrar APIs empresariales.

✅ Mejorar la experiencia del usuario.

---