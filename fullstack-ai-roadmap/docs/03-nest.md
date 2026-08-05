# 🟣 NestJS: Desarrollo Backend Escalable con Node

![NestJS](../assets/covers/nest.png)

> Ruta de aprendizaje para construir aplicaciones backend profesionales utilizando NestJS, Node.js y TypeScript.

---

# 📌 Información del curso

| Información | Detalle |
|------------|---------|
| Tecnología | NestJS |
| Lenguaje | TypeScript |
| Plataforma | Udemy |
| Área | Backend Development |
| Nivel | Principiante → Avanzado |
| Estado | ⬜ Pendiente |

🔗 Curso:

https://www.udemy.com/course/nest-framework/

---

# 🚀 Objetivo del curso

Aprender a desarrollar aplicaciones backend modernas, escalables y mantenibles utilizando NestJS.

NestJS permite crear APIs profesionales utilizando una arquitectura organizada basada en:

- Módulos.
- Controladores.
- Servicios.
- Inyección de dependencias.
- Decoradores.
- Middleware.
- Guards.
- Interceptors.

---

# 🎯 ¿Por qué aprender NestJS?

Node.js permite crear aplicaciones backend rápidas, pero en proyectos grandes se necesita una estructura más organizada.

NestJS proporciona:

✅ Arquitectura empresarial.

✅ Código mantenible.

✅ Uso completo de TypeScript.

✅ Patrones de diseño.

✅ Integración con bases de datos.

✅ Preparación para microservicios.

---

# 📚 Fundamentos de NestJS

# 1. ¿Qué es NestJS?

NestJS es un framework backend construido sobre Node.js.

Su filosofía está inspirada en arquitecturas como:

- Angular.
- Spring Boot.
- .NET.

Utiliza conceptos como:

```
Module
 |
 ├── Controller
 |
 └── Service
```

---

# 2. Instalación y Nest CLI

Instalación:

```bash
npm install -g @nestjs/cli
```

Crear proyecto:

```bash
nest new api
```

Ejecutar:

```bash
npm run start:dev
```

---

# 3. Arquitectura de una aplicación NestJS

Ejemplo:

```
src

├── users
│
├── auth
│
├── products
│
├── database
│
└── app.module.ts
```

---

# 4. Módulos

Los módulos organizan la aplicación.

Ejemplo:

```typescript
@Module({
 controllers:[UsersController],
 providers:[UsersService]
})
export class UsersModule {}
```

Un módulo representa una funcionalidad.

Ejemplos:

- Usuarios.
- Productos.
- Autenticación.
- Pagos.

---

# 5. Controllers

Los controladores reciben las peticiones HTTP.

Ejemplo:

```typescript
@Controller('users')
export class UsersController {

@Get()
findAll(){
 return [];
}

}
```

Responsabilidades:

- Recibir requests.
- Validar datos.
- Devolver respuestas.

---

# 6. Services

Los servicios contienen la lógica de negocio.

Ejemplo:

```typescript
@Injectable()
export class UsersService {

findAll(){
 return users;
}

}
```

Ventajas:

- Código reutilizable.
- Separación de responsabilidades.
- Fácil testing.

---

# 7. Inyección de dependencias

NestJS utiliza Dependency Injection.

Ejemplo:

```typescript
constructor(
 private usersService: UsersService
){}
```

Permite crear aplicaciones más limpias y escalables.

---

# 8. APIs REST

Aprenderás a crear:

- GET.
- POST.
- PUT.
- PATCH.
- DELETE.

Ejemplo:

```
GET

/users

POST

/users

DELETE

/users/:id
```

---

# 9. DTOs y validaciones

Los DTOs permiten controlar la información recibida.

Ejemplo:

```typescript
export class CreateUserDto {

name:string;

email:string;

}
```

Validaciones:

- Campos obligatorios.
- Tipos.
- Formatos.
- Reglas de negocio.

---

# 10. Bases de datos

Integración con:

- PostgreSQL.
- MongoDB.
- TypeORM.
- Prisma.

Arquitectura:

```
Controller

    ↓

Service

    ↓

Repository

    ↓

Database
```

---

# 11. Autenticación

Creación de sistemas seguros:

- Registro.
- Login.
- JWT.
- Refresh Tokens.
- Guards.
- Roles.

Flujo:

```
Usuario

 ↓

Login

 ↓

JWT Token

 ↓

Request protegida

 ↓

API
```

---

# 12. Manejo profesional de errores

Aprenderás:

- Exception Filters.
- HTTP Exceptions.
- Manejo global de errores.

---

# 13. Configuración de aplicaciones

Uso de:

- Variables de entorno.
- Configuración por ambientes.
- Secretos.

Ejemplo:

```
.env

DATABASE_URL=
JWT_SECRET=
OPENAI_KEY=
```

---

# 🛠️ Proyectos que podrás construir

## API de usuarios

Incluye:

✅ CRUD

✅ Login

✅ JWT

✅ Roles

---

## Backend para aplicación empresarial

Arquitectura:

```
Angular

   |

NestJS API

   |

PostgreSQL
```

---

## API preparada para IA

Ejemplo:

```
Angular

   |

NestJS

   |

OpenAI API
```

---

# 📋 Checklist de aprendizaje

## Fundamentos

- [ ] Crear proyectos NestJS
- [ ] Módulos
- [ ] Controllers
- [ ] Services
- [ ] Dependency Injection

## Backend profesional

- [ ] APIs REST
- [ ] DTOs
- [ ] Validaciones
- [ ] Manejo de errores
- [ ] Configuración

## Seguridad

- [ ] JWT
- [ ] Guards
- [ ] Roles
- [ ] Protección de rutas

## Bases de datos

- [ ] PostgreSQL
- [ ] MongoDB
- [ ] ORM
- [ ] Migraciones

---

# 🔗 Recursos oficiales

## NestJS

https://nestjs.com/

## Documentación

https://docs.nestjs.com/

## Node.js

https://nodejs.org/

---

# 🚀 Después de NestJS

El siguiente paso será:

```
NestJS

   |

Microservicios

   |

Arquitecturas escalables

   |

Sistemas empresariales
```

---

# 🏆 Resultado esperado

Al finalizar este curso podrás:

✅ Crear APIs profesionales.

✅ Diseñar backends escalables.

✅ Trabajar con bases de datos.

✅ Implementar autenticación.

✅ Crear servicios listos para aplicaciones reales.

✅ Prepararte para arquitectura de microservicios.

---