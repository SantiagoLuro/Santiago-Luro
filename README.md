<h1 align="center">Hola, soy Santiago Luro 👋</h1>

<p align="center">
  Estudiante de 2.º año de <b>Ingeniería en Sistemas en UADE</b> y fundador de <b><a href="https://melvox.net">Melvox</a></b>,<br>
  una suite de productos con IA para pymes argentinas.
</p>

<p align="center">
  <a href="https://santiago.melvox.net"><img src="https://img.shields.io/badge/Portfolio-0A0F1E?style=for-the-badge&logo=googlechrome&logoColor=00FFB2" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/santiago-luro-463395367/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:santiagoluro006@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

Busco mi **primera experiencia como desarrollador** para aprender en equipo y crecer.
Me interesan el backend y la IA.

📍 Buenos Aires · 🌎 Inglés C1

## 🚀 Proyecto principal: Melvox
Suite de productos con IA para pymes · [melvox.net](https://melvox.net) · código privado ([descripción y arquitectura](https://github.com/SantiagoLuro/melvox))

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
Cada empresa carga su documentación interna y la consulta desde la web.
Fue el primer producto de Melvox.

- **Multitenant:** cada empresa tiene sus propios documentos y su plan, y nunca ve los de otra.
- **Una sola fuente de verdad:** el bot hacía RAG por su cuenta; lo refactoricé
  para que llame a la API central, que maneja búsqueda, cuotas por plan y métricas de uso.
- **Embeddings multilingües** (Cohere), elegidos porque los documentos están en español.

`TypeScript` `Node.js` `SQLite` `Cohere` `PM2` `Linux`

## 📂 Otros proyectos
**[Adivina Quién](https://github.com/SantiagoLuro/adivina-quien)** · Java
TP grupal de Programación III (en curso). Clases, herencia, colecciones y lógica de juego.

**[Ejercicios de SQL](https://github.com/SantiagoLuro/ejercicios-sql)** · SQL Server
Consultas y modelado de bases de datos de Ingeniería de Datos I.

**[Portfolio](https://github.com/SantiagoLuro/portfolio)** · HTML · CSS
Mi sitio personal, sin frameworks. Online en [santiago.melvox.net](https://santiago.melvox.net).

## 🛠️ Tecnologías

**Uso en proyectos propios**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**IA**

![Claude](https://img.shields.io/badge/API_de_Claude-D97757?style=for-the-badge&logo=claude&logoColor=white)
![Cohere](https://img.shields.io/badge/Cohere_(RAG)-39594D?style=for-the-badge&logoColor=white)

**Deploy**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=for-the-badge&logo=pm2&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)

**Aprendiendo en la facultad**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)

## 🧑‍💻 Cómo llegué acá
Arranqué programando por mi cuenta. De ahí pasé a proyectos más grandes, hasta empezar Melvox.
Con la carrera estoy sumando las bases que me faltaban: orientación a objetos, bases de
datos y buenas prácticas.

## 📫 Contacto
[Portfolio](https://santiago.melvox.net) · [LinkedIn](https://www.linkedin.com/in/santiago-luro-463395367/) · santiagoluro006@gmail.com
