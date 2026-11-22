# My Little Netflix

Aplicación web cliente para gestionar una lista de películas, hecha con HTML, CSS y JavaScript siguiendo el patrón **MVC**. Los datos se guardan en el `localStorage` del navegador y se pueden buscar películas y palabras clave en la API de **The Movie Database (TMDb)**.

Práctica de la asignatura **Tecnologías Web**.

🔗 **Web publicada:** https://danielhernaizz.github.io/Netflix2_completo/

## Funcionalidades

- Ver, añadir, editar y eliminar películas (con confirmación al borrar) y restablecer la lista inicial.
- Buscar películas en TMDb y añadirlas a tu lista, evitando duplicados.
- Ver las palabras clave de una película y guardarlas en una lista personalizada.
- Arrastrar y soltar palabras clave para añadirlas o borrarlas.
- Transiciones y animaciones CSS, y diseño adaptable a móvil.
- SEO: metaetiquetas, HTML semántico, migas de pan, `robots.txt` y `sitemap.xml`.

## Cómo usarlo

1. Descarga o clona el repositorio y abre `index.html` en Chrome o Firefox.
2. Para la búsqueda necesitas un token de TMDb:
   - Crea una cuenta en [themoviedb.org](https://www.themoviedb.org) y solicita una clave de API.
   - Copia el **API Read Access Token**.
   - En la aplicación, pulsa **Search TMDb**, pega el token y pulsa **Save key**.

El token se guarda solo en tu navegador, nunca en el código.

## Estructura

```
Netflix/
├── index.html          # HTML, CSS y JavaScript (MVC)
├── robots.txt          # Reglas para los buscadores
├── sitemap.xml         # Mapa del sitio
├── config.example.js   # Plantilla opcional para el token
├── files/              # Portadas de las películas
└── tests/              # Tests de la práctica
```

## Tecnologías

HTML5 · CSS3 · JavaScript · localStorage · API de TMDb

---
Datos de películas proporcionados por [TMDb](https://www.themoviedb.org). Este producto utiliza la API de TMDb pero no está avalado ni certificado por TMDb.
