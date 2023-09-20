
<!DOCTYPE html>
<html>
<head>
  <title>Librería de gustos - Página de Inicio</title>
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
    <h1>Librería de gustos</h1>
  </header>

  <p>Bienvenido a la librería gustos, tu destino para descubrir y explorar nuevos libros.</p>

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
  <p>"Reseñas de libros populares": Crea una sección donde puedas incluir reseñas de libros populares y de éxito. Puedes escribir tus propias opiniones sobre los libros o invitar a otros escritores o lectores apasionados a contribuir con sus reseñas. Asegúrate de incluir una variedad de géneros y estilos literarios para atraer a diferentes tipos de lectores.</p>

  <h2 id="seccion3">Sección 3</h2>
  <p>"Consejos de lectura": En esta sección, puedes ofrecer consejos prácticos y útiles para los amantes de la lectura. Puedes incluir temas como cómo elegir un libro adecuado, cómo organizar una biblioteca en casa, cómo crear un club de lectura, o incluso recomendaciones sobre cómo aprovechar al máximo la experiencia de lectura. También puedes incluir contenido adicional, como una lista de libros clásicos que todos deberían leer en su vida o una guía sobre cómo iniciarse en un género literario específico..</p>

  <table>
    <thead>
      <tr>
        <th>Orgullo y prejuicio</th>
        <th>Jane Austen</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Divina comedia</td>
        <td>Dante Aligieri</td>
      </tr>
      <tr>
        <td>El extranjero</td>
        <td>Albert Camus</td>
      </tr>
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
