
<!DOCTYPE html>
<html>
<head>
  <title>Librería Terra - Página de Inicio</title>
  <style>
    /* Estilos CSS para personalizar la página */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      background-color: #f2f2f2;
    }

    header {
      text-align: center;
      padding: 10px;
      background-color: #333;
      color: #fff;
    }

    h1 {
      margin: 0;
      font-size: 24px;
    }

    p {
      font-size: 16px;
    }

    nav {
      margin-top: 20px;
    }

    nav ul {
      list-style-type: none;
      padding: 0;
      display: flex;
      justify-content: center;
    }

    nav a {
      text-decoration: none;
      margin: 0 10px;
      color: #333;
      font-weight: bold;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }

    th, td {
      padding: 10px;
      text-align: left;
      border-bottom: 1px solid #ccc;
    }

    form {
      margin-top: 20px;
    }

    label {
      display: block;
      margin-bottom: 5px;
    }

    input[type="text"], input[type="email"], textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
    }

    input[type="submit"] {
      background-color: #333;
      color: #fff;
      border: none;
      padding: 10px 20px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>Librería Terra</h1>
  </header>

  <p>Bienvenido a la librería Terra, tu destino para descubrir y explorar nuevos libros.</p>

  <nav>
    <ul>
      <li><a href="#seccion1">Sección 1</a></li>
      <li><a href="#seccion2">Sección 2</a></li>
      <li><a href="#seccion3">Sección 3</a></li>
    </ul>
  </nav>

  <h2 id="seccion1">Sección 1</h2>
  <p>"Libro recomendado del mes": En esta sección, puedes destacar un libro diferente cada mes. Proporciona una breve reseña del libro, su género y el autor, junto con una imagen llamativa de la portada. También puedes incluir enlaces de compra en línea para aquellos que estén interesados en adquirirlo.</p>

  <h2 id="seccion2">Sección 2</h2>
  <p>"Reseñas de libros populares": Es una sección donde puedas incluir reseñas de libros populares y de éxito. Puedes escribir tus propias opiniones sobre los libros o invitar a otros escritores o lectores apasionados a contribuir con sus reseñas. Asegúrate de incluir una variedad de géneros y estilos literarios para atraer a diferentes tipos de lectores.</p>

  <head>
    <title>Reseñas de Libros Populares</title>
</head>
<body>
    <h1>Reseñas de Libros Populares</h1>
    <div>
        <h2>Mis Reseñas</h2>
        <div>
            <h3>Título del Libro 1</h3>
            <p>Opinión: Esta es mi opinión sobre el libro 1. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
        <div>
            <h3>Título del Libro 2</h3>
            <p>Opinión: Esta es mi opinión sobre el libro 2. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
    </div>
    <div>
        <h2>Reseñas de Otros</h2>
        <div>
            <h3>Reseña de Escritor/Editor 1</h3>
            <p>Opinión: Esta es la reseña del escritor/editor 1 sobre el libro. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
        <div>
            <h3>Reseña de Lector Apasionado 1</h3>
            <p>Opinión: Esta es la reseña del lector apasionado 1 sobre el libro. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
    </div>
    <div>
        <h2>Libros por Género</h2>
        <h3>Género de aventura</h3>
        <ul>
            <li>La isla del tesoro</li>
            <li>El prisionero de Zenda</li>
            <li>El faro del fin del mundo</li>
        </ul>
        <h3>Género de misterio</h3>
        <ul>
            <li>El juego del alma</li>
            <li>El codigo da vinci</li>
            <li>El visitante</li>
        </ul>
    </div>

  <h2 id="seccion3">Sección 3</h2>
  <p>"Consejos de lectura": En esta sección, puedes ofrecer consejos prácticos y útiles para los amantes de la lectura. Puedes incluir temas como cómo elegir un libro adecuado, cómo organizar una biblioteca en casa, cómo crear un club de lectura, o incluso recomendaciones sobre cómo aprovechar al máximo la experiencia de lectura. También puedes incluir contenido adicional, como una lista de libros clásicos que todos deberían leer en su vida o una guía sobre cómo iniciarse en un género literario específico..</p>

  <table>
    <tbody>
      <tr>
        <td>Divina comedia</td>
        <td>Dante Aligieri</td>
      </tr>
      <tr>
        <td>El extranjero</td>
        <td>Albert Camus</td>
      </tr>
      <thead>
      <tr>
        <th>Orgullo y prejuicio</th>
        <th>Jane Austen</th>
      </tr>
    </thead>
    </tbody>
  </table>

  <h2>Formulario de Contacto</h2>
  <form>
    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" required>

    <label for="email">Email:</label>
    <input type="email" id="email" required>

    <label for="mensaje">Mensaje:</label>
    <textarea id="mensaje" required></textarea>

    <input type="submit" value="Enviar">
  </form>
</body>
</html>
