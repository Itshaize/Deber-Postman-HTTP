# 🌐 Práctica de Laboratorio - Métodos HTTP con Postman

**Repositorio:** https://github.com/Itshaize/Deber-Postman-HTTP.git  
**Estudiante:** Ismael Cornejo  
**API utilizada:** [JSONPlaceholder](https://jsonplaceholder.typicode.com) - Repositorio online de datos JSON gratuito para pruebas.

---

## 📋 Objetivos

- Comprender el funcionamiento de los métodos HTTP (POST, GET, PUT, DELETE) utilizando la herramienta Postman.
- Consumir un repositorio online de datos en formato JSON mediante peticiones HTTP.
- Identificar las diferencias entre cada método HTTP y los códigos de respuesta del servidor.
- Aplicar los conceptos de APIs REST en un entorno práctico de laboratorio.

---

## 🛠️ Herramientas utilizadas

| Herramienta | Descripción |
|---|---|
| **Postman** | Plataforma para probar y ejecutar peticiones HTTP |
| **JSONPlaceholder** | API REST falsa y gratuita para pruebas (`https://jsonplaceholder.typicode.com`) |
| **JSON** | Formato de datos utilizado en las peticiones y respuestas |

---

## 🚀 Métodos HTTP Ejecutados

### 1. ✅ Método POST — Crear un recurso

**URL:** `https://jsonplaceholder.typicode.com/posts`  
**Código de respuesta esperado:** `201 Created`

**Body enviado:**
```json
{
  "title": "Mi Nuevo Post",
  "body": "Este es el contenido de mi post de prueba para el deber.",
  "userId": 1
}
```

**Captura de pantalla:**

> 📸 *(Insertar captura de pantalla del método POST aquí)*

---

### 2. ✅ Método GET — Obtener un recurso

**URL:** `https://jsonplaceholder.typicode.com/posts/1`  
**Código de respuesta esperado:** `200 OK`

**Captura de pantalla:**

> 📸 *(Insertar captura de pantalla del método GET aquí)*

---

### 3. ✅ Método PUT — Actualizar un recurso

**URL:** `https://jsonplaceholder.typicode.com/posts/1`  
**Código de respuesta esperado:** `200 OK`

**Body enviado:**
```json
{
  "id": 1,
  "title": "Título Actualizado",
  "body": "He actualizado el contenido mediante el método PUT.",
  "userId": 1
}
```

**Captura de pantalla:**

> 📸 *(Insertar captura de pantalla del método PUT aquí)*

---

### 4. ✅ Método DELETE — Eliminar un recurso

**URL:** `https://jsonplaceholder.typicode.com/posts/1`  
**Código de respuesta esperado:** `200 OK`

**Captura de pantalla:**

> 📸 *(Insertar captura de pantalla del método DELETE aquí)*

---

## 📊 Tabla de Resumen de Resultados

| # | Método HTTP | URL | Código de Respuesta | Acción |
|---|---|---|---|---|
| 1 | POST | `/posts` | 201 Created | Crear nuevo recurso |
| 2 | GET | `/posts/1` | 200 OK | Leer recurso existente |
| 3 | PUT | `/posts/1` | 200 OK | Actualizar recurso existente |
| 4 | DELETE | `/posts/1` | 200 OK | Eliminar recurso existente |

---

## 📁 Archivos del repositorio

- `README.md` — Este documento con objetivos, capturas y conclusiones.
- `Coleccion_Postman_Deber.json` — Colección de Postman lista para importar con los 4 métodos configurados.

---

## 📝 Conclusiones

1. **Los métodos HTTP son fundamentales** para la comunicación entre clientes y servidores en las aplicaciones web modernas. Cada método tiene un propósito específico y bien definido dentro de la arquitectura REST.

2. **Postman es una herramienta muy útil** para probar y depurar APIs sin necesidad de escribir código, ya que permite enviar peticiones de cualquier tipo de forma sencilla y visualizar las respuestas en tiempo real.

3. **El método POST** permite enviar datos al servidor para crear nuevos recursos. El servidor responde con el código `201 Created` confirmando la creación exitosa.

4. **El método GET** es el más utilizado y permite obtener información del servidor sin modificar ningún dato. Es la base de la navegación web.

5. **El método PUT** reemplaza completamente un recurso existente con los nuevos datos enviados, siendo clave para las operaciones de actualización en aplicaciones REST.

6. **El método DELETE** elimina un recurso del servidor de forma permanente. El servidor confirma la operación con un código `200 OK` y generalmente retorna un cuerpo vacío `{}`.

7. El uso de APIs públicas como **JSONPlaceholder** facilita enormemente el aprendizaje y las pruebas de integración, ya que simula un servidor real sin necesidad de infraestructura propia.

---

*Práctica de Laboratorio — Universidad | 2026*
