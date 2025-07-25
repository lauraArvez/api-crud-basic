# API CRUD Básica

Este proyecto implementa una API REST sencilla con operaciones **CRUD (Create, Read, Update, Delete)** usando Java y Spring Boot. 
---

## 🎯 Objetivo

Crear una API funcional con endpoints REST que permita manejar entidades (como usuarios, productos o tareas) conectada a una base de datos.

---

## 🛠️ Tecnologías utilizadas

- ☕ Java
- 🌱 Spring Boot
- 💾 MySQL o H2 (según configuración)
- 🧪 Postman (para pruebas)
- 🛠️ Maven

---

## 🔍 Endpoints principales

> Ejemplos orientativos, ajústalos a tus entidades:

| Método | Endpoint           | Descripción            |
|--------|--------------------|------------------------|
| GET    | `/api/items`       | Obtener todos          |
| POST   | `/api/items`       | Crear nuevo            |
| PUT    | `/api/items/{id}`  | Actualizar por ID      |
| DELETE | `/api/items/{id}`  | Eliminar por ID        |

---

## ⚙️ Cómo ejecutar el proyecto

1. Clona el repositorio:
```bash
git clone https://github.com/LauraArvez/api-crud-basic.git
2. Configura la conexión a base de datos en application.properties.
3. Ejecuta con tu IDE (IntelliJ o VSCode) o por terminal: ./mvnw spring-boot:run

🧩 Estructura del proyecto

api-crud-basic/
 ┣ controller/
 ┣ service/
 ┣ repository/
 ┣ model/
 ┗ application.properties

