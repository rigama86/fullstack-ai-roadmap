# 🅰️ Angular: De cero a experto

![Angular](../assets/covers/angular.png)

> Ruta de aprendizaje basada en el curso **Angular: De cero a experto** de Fernando Herrera.

---

# 📌 Información del curso

| Información | Detalle |
|------------|---------|
| Tecnología | Angular |
| Lenguaje | TypeScript |
| Nivel | Principiante → Avanzado |
| Área | Frontend Development |
| Instructor | Fernando Herrera |
| Plataforma | Udemy |
| Estado | ⬜ Pendiente |

🔗 Curso:

https://www.udemy.com/course/angular-fernando-herrera/

---

# 🚀 Objetivo del curso

Aprender Angular desde sus fundamentos hasta construir aplicaciones profesionales utilizando las mejores prácticas del ecosistema moderno.

Al finalizar este curso tendrás las bases necesarias para crear aplicaciones frontend escalables, consumir APIs, manejar autenticación, crear componentes reutilizables y trabajar con arquitecturas utilizadas en proyectos empresariales.

---

# 🎯 ¿Por qué aprender Angular?

Angular es uno de los frameworks frontend más utilizados en aplicaciones empresariales debido a:

- Arquitectura organizada.
- Uso de TypeScript.
- Excelente escalabilidad.
- Herramientas oficiales integradas.
- Comunidad madura.
- Soporte para aplicaciones grandes.

Angular es especialmente utilizado en:

- Sistemas administrativos.
- Plataformas financieras.
- Aplicaciones empresariales.
- Dashboards.
- Sistemas internos.
- Aplicaciones SaaS.

---

# 📚 Conocimientos que aprenderás

## 1. Fundamentos de TypeScript

Antes de trabajar con Angular es importante dominar TypeScript.

Aprenderás:

- Tipos de datos.
- Interfaces.
- Clases.
- Decoradores.
- Generics.
- Módulos.
- Programación orientada a objetos.

---

# 2. Fundamentos de Angular

Conceptos principales:

- ¿Qué es Angular?
- Angular CLI.
- Estructura de proyectos.
- Componentes.
- Templates.
- Data Binding.
- Directivas.
- Pipes.

Ejemplo de arquitectura:

```
src
│
├── app
│   ├── components
│   ├── services
│   ├── interfaces
│   └── pages
│
├── assets
│
└── environments
```

---

# 3. Componentes

Los componentes son la base de Angular.

Aprenderás:

- Crear componentes.
- Comunicación entre componentes.
- Inputs.
- Outputs.
- Ciclo de vida.
- Reutilización de código.

Ejemplo:

```typescript
@Component({
  selector: 'app-user',
  templateUrl: './user.component.html'
})
export class UserComponent {

}
```

---

# 4. Servicios e Inyección de Dependencias

Angular utiliza servicios para separar responsabilidades.

Aprenderás:

- Crear servicios.
- Inyección de dependencias.
- Comunicación entre componentes.
- Reutilización de lógica.

Ejemplo:

```typescript
@Injectable({
 providedIn:'root'
})
export class UserService {

}
```

---

# 5. Routing

Aprenderás a crear aplicaciones SPA.

Conceptos:

- Rutas.
- Parámetros.
- Lazy Loading.
- Guards.
- Navegación.
- Protección de páginas.

Ejemplo:

```typescript
{
 path:'users',
 component: UsersComponent
}
```

---

# 6. Formularios

Angular permite crear formularios profesionales.

Aprenderás:

- Template Forms.
- Reactive Forms.
- Validaciones.
- Formularios dinámicos.
- Manejo de errores.

---

# 7. RxJS

Una de las partes más importantes de Angular.

Aprenderás:

- Observables.
- Subscribers.
- Operadores.
- Streams.
- Manejo de eventos.

Ejemplo:

```typescript
users$
  .pipe(
     map(users => users.length)
  )
```

---

# 8. Comunicación con APIs

Aprenderás a conectar Angular con backend.

Conceptos:

- HttpClient.
- Interceptors.
- Manejo de errores.
- Headers.
- Tokens JWT.

Ejemplo:

```
Angular
   |
   |
 HTTP
   |
   |
NestJS API
```

---

# 9. Autenticación

Implementación de sistemas reales:

- Login.
- Registro.
- JWT.
- Guards.
- Manejo de sesión.
- Roles y permisos.

---

# 10. Angular moderno

Conceptos actuales:

- Standalone Components.
- Signals.
- Nueva sintaxis de templates.
- Mejoras de rendimiento.
- Arquitecturas modernas.

---

# 🛠️ Proyectos que podrás construir

Al terminar este curso podrás desarrollar:

## Dashboard administrativo

Características:

✅ Login

✅ Menús dinámicos

✅ Gráficas

✅ Tablas

✅ Formularios

---

## Aplicación CRUD

Ejemplo:

Sistema de usuarios:

- Crear usuarios.
- Editar usuarios.
- Eliminar usuarios.
- Buscar información.

---

## Aplicación consumiendo APIs

Ejemplo:

```
Angular
   |
   |
REST API
   |
   |
Base de datos
```

---

# 📋 Checklist de aprendizaje

## Fundamentos

- [ ] TypeScript
- [ ] Angular CLI
- [ ] Componentes
- [ ] Templates
- [ ] Directivas
- [ ] Pipes

## Aplicaciones reales

- [ ] Routing
- [ ] Servicios
- [ ] HTTP
- [ ] Formularios
- [ ] Validaciones
- [ ] JWT

## Angular avanzado

- [ ] RxJS
- [ ] Signals
- [ ] Lazy Loading
- [ ] Guards
- [ ] Optimización

---

# 🔗 Recursos oficiales

## Angular

https://angular.dev/

## TypeScript

https://www.typescriptlang.org/

## RxJS

https://rxjs.dev/

---

# 🚀 Después de Angular

Una vez terminado este curso, el siguiente paso recomendado es:

```
Angular
   |
   ▼
Docker
   |
   ▼
NestJS Backend
   |
   ▼
Aplicaciones Full Stack
```

Angular será la base frontend que utilizaremos posteriormente para:

- Consumir APIs creadas con NestJS.
- Integrar OpenAI.
- Crear aplicaciones con IA.
- Construir productos SaaS completos.

---

# 🏆 Resultado esperado

Al completar este curso deberás ser capaz de:

✅ Crear aplicaciones Angular profesionales.

✅ Diseñar componentes reutilizables.

✅ Consumir APIs REST.

✅ Implementar autenticación.

✅ Trabajar con proyectos empresariales.

✅ Continuar hacia desarrollo Full Stack con NestJS.

---