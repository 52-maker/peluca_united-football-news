# peluca_united-football-news
git init
git add .
git commit -m "Primer commit - Subida de mi sitio de fútbol"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/mi-sitio-futbol.git
git push -u origin main
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Fútbol Total</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <header>
        <h1>Fútbol Total</h1>
    </header>

    <main>
        <section class="upload-section">
            <h2>Sube tu video</h2>
            <input type="file" id="videoUploader" accept="video/*">
            <button onclick="subirVideo()">Subir</button>
        </section>

        <section class="video-list">
            <h2>Videos recientes</h2>
            <div id="videosContainer"></div>
        </section>

        <section class="news-section">
            <h2>Publicar Noticia</h2>
            <textarea id="newsInput" placeholder="Escribe una noticia..."></textarea>
            <button onclick="publicarNoticia()">Publicar</button>
        </section>

        <section class="news-list">
            <h2>Últimas noticias</h2>
            <div id="noticiasContainer"></div>
        </section>
    </main>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    background-color: #f5f5f5;
    margin: 0;
    padding: 0;
    color: #333;
}

header {
    background-color: #1e90ff;
    color: white;
    padding: 20px;
    text-align: center;
}

main {
    padding: 20px;
    max-width: 800px;
    margin: auto;
}

section {
    margin-bottom: 30px;
    background-color: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

input[type="file"], textarea {
    width: 100%;
    margin: 10px 0;
}

button {
    padding: 10px 20px;
    background-color: #1e90ff;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

.video-item video {
    width: 100%;
    max-height: 300px;
    margin-top: 10px;
}
function subirVideo() {
    const input = document.getElementById('videoUploader');
    const container = document.getElementById('videosContainer');
    const file = input.files[0];

    if (file) {
        const url = URL.createObjectURL(file);
        const videoDiv = document.createElement('div');
        videoDiv.className = 'video-item';
        videoDiv.innerHTML = `<p>${file.name}</p><video controls src="${url}"></video>`;
        container.prepend(videoDiv); // aparece primero
        input.value = ''; // limpia el input
    }
}

function publicarNoticia() {
    const input = document.getElementById('newsInput');
    const container = document.getElementById('noticiasContainer');
    const texto = input.value.trim();

    if (texto) {
        const noticia = document.createElement('div');
        noticia.className = 'noticia-item';
        noticia.innerHTML = `<p>${texto}</p>`;
        container.prepend(noticia);
        input.value = '';
    }
}
<!-- Esto va en index.html -->
[🔽 Ya te lo dejé en la respuesta anterior. Pega todo el HTML aquí]
/* Esto va en style.css */
[🔽 Pega el CSS que te di aquí]// Esto va en script.js
[🔽 Pega el JavaScript que te di aquí]
git init
git add .
git commit -m "Primer commit - Subida de mi sitio de fútbol"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/mi-sitio-futbol.git
git push -u origin main

cv
