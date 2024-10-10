# Mi-Instapet
Este es el código fuente del trabajo Instapet
<!DOCTYPE html>
<html lang="es-AR">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Instapet</title>
  <link rel="stylesheet" href="estilaco.css">
</head>

<body>
  <h1>¡Bienvenidos a InstaPet!</h1>
  <hr>
  <p>En esta Página vas a encontrar distintos tipos de mascotas en donde conocerás cada una de sus características de acorde al género a tu gusto! asi que... ¿qué estás esperando? registrate y conoce lo que Instapet puede ofrecerte!
  </p>

<h2>Índice</h2>
  <nav>
  <ul>
    <li><a href="#form-prin">Ir al Formulario Principal</a></li>
    <li><a href="#vet-prin">Ir a la Veterinaria más Cercana de la Zona </a></li>
    <li><a href="#vid-inf">Ver Videos Informativos</a></li>
  </ul>
</nav>
  <h3 id="form-prin"><u>Formulario Principal</u></h2>
  <form action="https://formspree.io/f/xrgnnvob" method="POST">

    <fieldset id="datos">
      <legend><b>Datos Personales</b></legend>
      <div><label>Nombre: <input type="text" name="nombre" placeholder="Ingresá tu nombre" required /> </label></div>
      <div><label>Edad: </label><input type="number" name="edad" placeholder="Ingresa tu edad" required> </div>
      <div><label>Ingrese email: <input type="email" name="correo" placeholder="ingrese su correo electronico" required></label></div>
      <div><label>Contraseña: <input type="password" name="pass" placeholder="ingrese su contraseña" required></label>
      </div>
      <label for="term">Aceptar terminos y condiciones:</label>
      <input id="term" type="checkbox" name="term-condi" required>
    </fieldset>
    <br>
    <fieldset>
      <legend><b>Datos de tu mascota</b></legend>
      <div><label>Nombre:<input type="text" name="nombre" placeholder="Nombre de tu mascota" required></label></div>
      <div><label>Edad:</label><input type="number" name="edad" placeholder="Ingresa la edad de tu mascota"required></div>
      <div><p id="genre"><i> <u>Género:</u></i></p> </div>
      <div><label>Macho:<input type="radio" name="Genero" value="M"></label></div>
      <div><label>Hembra: <input type="radio" name="Genero" value="H"></label></div>
      <label for="especie">Especie:</label>
      <select id="raza" name="tipo_de_mascotas" required>
      <option value="canino">Canino (Perros) </option>
      <option value="felino">Felino (Gatos) </option>
      <option value="leporido">Lepórido (Conejos) </option>
      <option value="roedor">Roedor (hámster) </option></select>
      <br>
      <label for="consultas">Contanos de tu mascota:</label>
      <br>
      <textarea name="consulta" id="consultas" rows="20" cols="60"
      placeholder="Danos detalles acerca de tu mascota, Sin miedooo ;) "></textarea>
      <br>

    </fieldset>
    <input id="boton" type="submit" value="enviar informacion">
    <h3 id="vet-prin"><u>Veterinaria cercana de la zona</u></h3>
    <br>
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d978.0285774989616!2d-58.77338829037105!3d-34.46019652244244!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x95bc98da912c8069%3A0x553f6a35717a5ee4!2sveterinaria%20basht!5e0!3m2!1ses-419!2sar!4v1718657965831!5m2!1ses-419!2sar" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

    <h3 id="vid-inf"><u>Videos Informativos</u></h3>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/mZsyZp8pslE?si=Y7Xo0U8iGySNjJbi" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/3D3ftfiHxAs?si=KgYbGQEaL0Z3C7-R" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/OwLWG4Wq-Ys?si=TN15TPis0UappatU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
  </form>

</body>

</html>
