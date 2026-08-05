# 🐳 Docker - Guía práctica de uso para desarrolladores

![Docker](../assets/covers/docker.png)

> Ruta de aprendizaje para dominar Docker y utilizar contenedores en proyectos modernos de desarrollo.

---

# 📌 Información del curso

| Información | Detalle |
|------------|---------|
| Tecnología | Docker |
| Área | DevOps / Desarrollo |
| Nivel | Principiante → Intermedio |
| Plataforma | Udemy |
| Estado | ⬜ Pendiente |

🔗 Curso:

https://www.udemy.com/course/docker-guia-practica/

---

# 🚀 Objetivo del curso

Aprender a utilizar Docker para crear ambientes de desarrollo profesionales, empaquetar aplicaciones y ejecutar servicios de manera consistente sin importar el sistema operativo.

Docker permite que equipos completos trabajen con exactamente las mismas versiones de:

- Aplicaciones.
- Dependencias.
- Bases de datos.
- Servicios.
- Herramientas.

---

# 🎯 ¿Por qué aprender Docker?

En proyectos reales aparecen problemas como:

> "En mi máquina funciona"

Docker ayuda a solucionar esto creando ambientes aislados y reproducibles.

Ejemplo:

```
Desarrollador
     |
     |
     ▼
Contenedor Docker
     |
     |
     ▼
Aplicación funcionando igual
```

---

# 📚 Conceptos fundamentales

# 1. ¿Qué es Docker?

Docker es una plataforma para crear y ejecutar contenedores.

Un contenedor contiene:

- Código.
- Dependencias.
- Configuración.
- Runtime.
- Herramientas necesarias.

---

# 2. Imágenes y contenedores

## Imagen

Una imagen es una plantilla para crear contenedores.

Ejemplo:

```
Node.js Image

        |
        |
        ▼

Container

Aplicación ejecutándose
```

---

## Contenedor

Es una instancia ejecutándose de una imagen.

Ejemplo:

```
Imagen:

node:20

        ↓

Contenedor:

API NestJS funcionando
```

---

# 3. Docker CLI

Comandos principales:

## Ver versión

```bash
docker --version
```

---

## Ver contenedores

```bash
docker ps
```

---

## Descargar una imagen

```bash
docker pull nginx
```

---

## Ejecutar un contenedor

```bash
docker run nginx
```

---

# 4. Docker Hub

Docker Hub es el repositorio donde se almacenan imágenes.

Ejemplos:

- Node.
- PostgreSQL.
- MongoDB.
- Redis.
- Nginx.

---

# 5. Dockerfile

El Dockerfile define cómo construir una imagen.

Ejemplo:

```dockerfile
FROM node:20

WORKDIR /app

COPY package*.json .

RUN npm install

COPY . .

CMD ["npm","start"]
```

Flujo:

```
Dockerfile

    ↓

docker build

    ↓

Imagen

    ↓

Contenedor
```

---

# 6. Volúmenes

Los volúmenes permiten guardar información fuera del contenedor.

Ejemplo:

```
Contenedor PostgreSQL

        |
        |
        ▼

Volumen Docker

        |
        |
        ▼

Datos persistentes
```

---

# 7. Redes Docker

Los contenedores pueden comunicarse entre ellos.

Ejemplo aplicación completa:

```
Angular
   |
   |
NestJS
   |
   |
PostgreSQL
```

Todos dentro de una red Docker.

---

# 8. Docker Compose

Docker Compose permite levantar múltiples servicios.

Ejemplo:

```
Proyecto Full Stack

├── Angular
├── NestJS
├── PostgreSQL
└── Redis
```

Archivo:

```yaml
docker-compose.yml
```

Ejemplo:

```yaml
services:

  database:
    image: postgres

  api:
    image: nest-app

  frontend:
    image: angular-app
```

---

# 🛠️ Aplicaciones prácticas

Después de este curso podrás crear ambientes como:

## Proyecto Angular + NestJS

```
Frontend
Angular

       |
       |

Backend
NestJS

       |
       |

Database
PostgreSQL
```

Todo ejecutándose con Docker.

---

# 💼 Casos reales donde usar Docker

## Desarrollo local

Todos trabajan con la misma configuración.

---

## Testing

Crear ambientes temporales.

---

## Producción

Desplegar aplicaciones utilizando contenedores.

---

## Microservicios

Cada servicio puede vivir en su propio contenedor.

---

# 📋 Checklist de aprendizaje

## Fundamentos

- [ ] Qué es Docker
- [ ] Imágenes
- [ ] Contenedores
- [ ] Docker Hub
- [ ] Docker CLI

## Desarrollo

- [ ] Dockerfile
- [ ] Variables de entorno
- [ ] Volúmenes
- [ ] Redes
- [ ] Docker Compose

## Nivel profesional

- [ ] Multi-container apps
- [ ] Optimización de imágenes
- [ ] Deploy con Docker
- [ ] Integración CI/CD

---

# 🔗 Recursos oficiales

## Docker Documentation

https://docs.docker.com/

## Docker Hub

https://hub.docker.com/

---

# 🚀 Después de Docker

El siguiente paso será:

```
Docker
   |
   ▼
NestJS Backend
   |
   ▼
APIs REST
   |
   ▼
Aplicaciones Full Stack
```

Docker será la base para ejecutar:

- NestJS.
- Bases de datos.
- Microservicios.
- Aplicaciones con IA.

---

# 🏆 Resultado esperado

Al terminar este curso podrás:

✅ Crear imágenes Docker.

✅ Ejecutar contenedores.

✅ Configurar ambientes profesionales.

✅ Trabajar con Docker Compose.

✅ Preparar proyectos para producción.

---