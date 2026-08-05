# 🏗️ NestJS Microservicios: Aplicaciones escalables y modulares

![Microservices](../assets/covers/microservices.png)

> Ruta de aprendizaje para diseñar aplicaciones distribuidas utilizando NestJS, microservicios y patrones arquitectónicos modernos.

---

# 📌 Información del curso

| Información | Detalle |
|------------|---------|
| Tecnología | NestJS Microservices |
| Lenguaje | TypeScript |
| Área | Backend / Arquitectura |
| Nivel | Intermedio → Avanzado |
| Plataforma | Udemy |
| Estado | ⬜ Pendiente |

🔗 Curso:

https://www.udemy.com/course/nestjs-microservicios/

---

# 🚀 Objetivo del curso

Aprender a diseñar aplicaciones backend escalables utilizando arquitectura basada en microservicios.

Al finalizar entenderás cómo dividir aplicaciones grandes en servicios independientes capaces de:

- Escalar individualmente.
- Comunicarse entre sí.
- Mantener responsabilidades separadas.
- Desplegarse de forma independiente.

---

# 🎯 ¿Por qué aprender Microservicios?

Los sistemas pequeños pueden funcionar con un único backend.

Ejemplo:

```
Angular

   |

NestJS

   |

Database
```

Pero en sistemas empresariales aparecen necesidades como:

- Miles de usuarios.
- Diferentes equipos trabajando.
- Escalamiento independiente.
- Alta disponibilidad.

Entonces evolucionamos hacia:

```
Frontend

   |

Gateway

   |

Microservicios

   |

Databases
```

---

# 📚 Conceptos fundamentales

# 1. Arquitectura Monolítica vs Microservicios

## Monolito

Una aplicación contiene todo:

```
Backend

├── Usuarios
├── Productos
├── Pagos
├── Reportes

Database única
```

Ventajas:

✅ Fácil de iniciar.

Desventajas:

❌ Difícil escalar.

❌ Mucha dependencia entre módulos.

---

## Microservicios

Cada funcionalidad es independiente:

```
Users Service

Products Service

Payments Service

Notifications Service
```

Ventajas:

✅ Escalamiento independiente.

✅ Equipos independientes.

✅ Mejor mantenimiento.

---

# 2. Principios de microservicios

Aprenderás:

- Responsabilidad única.
- Bajo acoplamiento.
- Alta cohesión.
- Comunicación entre servicios.
- Independencia de despliegue.

---

# 3. NestJS Microservices

NestJS permite crear diferentes tipos de comunicación:

- TCP.
- Redis.
- RabbitMQ.
- Kafka.
- NATS.

Ejemplo:

```
Servicio A

     |
     |
 Mensaje

     |
     |

Servicio B
```

---

# 4. Comunicación entre servicios

Existen dos tipos principales:

## Comunicación síncrona

Un servicio espera respuesta.

Ejemplo:

```
Frontend

   |

API Gateway

   |

Users Service

   |

Response
```

---

## Comunicación asíncrona

Los servicios envían eventos.

Ejemplo:

```
Order Service

      |

EVENT:
ORDER_CREATED

      |

Notification Service
```

---

# 5. Message Brokers

Los brokers permiten comunicación desacoplada.

Ejemplos:

- RabbitMQ.
- Kafka.
- Redis.
- NATS.

Arquitectura:

```
Servicio A

     |

Message Broker

     |

Servicio B
```

---

# 6. API Gateway

El Gateway funciona como punto de entrada.

Ejemplo:

```
Cliente

   |

API Gateway

   |
 ┌───────────────┐
 │       │       │
Auth   Users   Orders
```

Responsabilidades:

- Routing.
- Seguridad.
- Validaciones.
- Autenticación.

---

# 7. Autenticación distribuida

Aprenderás cómo manejar:

- JWT.
- Tokens.
- Servicios protegidos.
- Roles.

Ejemplo:

```
Auth Service

      |

JWT Token

      |

Otros servicios
```

---

# 8. Docker y Microservicios

Docker permite ejecutar cada servicio separado.

Ejemplo:

```
docker-compose.yml


services:

 auth-service

 users-service

 orders-service

 database

 redis
```

---

# 9. Variables de entorno

Cada servicio puede tener configuración independiente.

Ejemplo:

```
AUTH_PORT=3001

USERS_PORT=3002

DATABASE_URL=
```

---

# 🛠️ Proyectos que podrás construir

# Sistema empresarial modular

Arquitectura:

```
Angular

    |

API Gateway

    |

--------------------------------

Auth Service

Users Service

Products Service

Orders Service

Notifications

--------------------------------

Databases
```

---

# Sistema de comercio electrónico

Servicios:

- Usuarios.
- Productos.
- Inventario.
- Pagos.
- Correos.

---

# Plataforma SaaS

Ejemplo:

```
Tenant Service

Billing Service

User Service

AI Service
```

---

# 📋 Checklist de aprendizaje

## Arquitectura

- [ ] Monolitos
- [ ] Microservicios
- [ ] Responsabilidades
- [ ] Comunicación

## NestJS

- [ ] Crear microservicios
- [ ] Configuración
- [ ] Transporters
- [ ] Eventos

## Comunicación

- [ ] TCP
- [ ] Redis
- [ ] RabbitMQ
- [ ] Kafka

## Producción

- [ ] Docker Compose
- [ ] Variables de entorno
- [ ] Escalabilidad
- [ ] Deployment

---

# 🔗 Recursos oficiales

## NestJS Microservices

https://docs.nestjs.com/microservices/basics

## Docker

https://docs.docker.com/

---

# 🚀 Después de Microservicios

Continuaremos con:

```
Microservicios

      |

Angular + NestJS + OpenAI

      |

Aplicaciones inteligentes con IA
```

Aquí comenzaremos a integrar:

- APIs de inteligencia artificial.
- Chatbots.
- Asistentes.
- Automatización.
- Agentes inteligentes.

---

# 🏆 Resultado esperado

Al finalizar podrás:

✅ Diseñar sistemas distribuidos.

✅ Crear servicios independientes.

✅ Comunicar aplicaciones backend.

✅ Preparar arquitecturas empresariales.

✅ Crear bases para aplicaciones con IA.

---