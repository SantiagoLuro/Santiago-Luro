# Hola, soy Santiago 👋

Estudiante de 2.º año de **Ingeniería en Sistemas en UADE** y fundador de **[Melvox](https://melvox.net)**,
una suite de productos con IA para pymes argentinas.
Busco mi **primera experiencia como desarrollador** para aprender en equipo y crecer.
Me interesan el backend y la IA.

📍 Buenos Aires · 🌎 Inglés C1

## 🚀 Proyecto principal: Melvox
Suite de productos con IA para pymes · [melvox.net](https://melvox.net) · código privado ([descripción y arquitectura](LINK_REPO_MELVOX))

### Control de Precios · en producción
Lee facturas de proveedores (foto o PDF) con IA y las compara contra la lista de
precios para detectar cobros de más. Lo usa una distribuidora de bebidas.

- **Probar antes de publicar:** antes de cada deploy corren tests con facturas y listas
  reales de cada proveedor del cliente. Si un cambio altera un resultado, el deploy no sale.
- **Los datos reales son desordenados:** cada proveedor arma sus listas a su manera, así que
  el sistema tiene un motor común y una configuración por proveedor.
- **Trabajar con un usuario real:** soporte, errores en producción y mejoras a partir de su feedback.

`TypeScript` `Node.js` `PostgreSQL` `API de Claude` `Vercel`

### Base de conocimiento con RAG · en desarrollo
Cada empresa carga su documentación interna y la consulta por Web.
Fue el primer producto de Melvox.

- **Multitenant:** cada empresa tiene sus propios documentos y su plan, y nunca ve los de otra.
- **Una sola fuente de verdad:** el bot hacía RAG por su cuenta; lo refactoricé
  para que llame a la API central, que maneja búsqueda, cuotas por plan y métricas de uso.
- **Embeddings multilingües** (Cohere), elegidos porque los documentos están en español.

`TypeScript` `Node.js` `SQLite` `Cohere` `PM2` `Linux`

## 📂 Otros proyectos
**[Adivina Quién]** · Java
TP grupal de Programación III (en curso). Clases, herencia, colecciones y lógica de juego.

**[Ejercicios de SQL]** · SQL Server
Consultas y modelado de bases de datos de Ingeniería de Datos I.

## 🛠️ Tecnologías
**Uso en proyectos propios:** TypeScript, JavaScript, Node.js, PostgreSQL, SQLite, Git
**Estoy aprendiendo en la facultad:** Java (POO), SQL Server
**Deploy:** servidor Linux con PM2, Vercel, Netlify
**IA:** API de Claude, RAG con embeddings (Cohere)

## 🧑‍💻 Cómo llegué acá
Arranqué programando por mi cuenta. De ahí pasé a proyectos más grandes, hasta empezar Melvox.
Con la carrera estoy sumando las bases que me faltaban: orientación a objetos, bases de
datos y buenas prácticas.

## 📫 Contacto
[LinkedIn]([LINK](https://www.linkedin.com/in/santiago-luro-463395367/?isSelfProfile=true)) · [Portfolio](LINK) · EMAIL
