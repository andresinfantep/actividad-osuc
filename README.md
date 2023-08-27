<!DOCTYPE html>
<!--
Aunque en este taller se utiliza HTML, CSS, y JS, no es necesario que sepas y que aprendas
nada de estos lenguajes. Si quieres aprender luego, te recomendamos ver lo siguiente:
- CS50W: https://cs50.harvard.edu/web/2020/
- HTML: https://developer.mozilla.org/es/docs/Learn/HTML
- CSS: https://developer.mozilla.org/es/docs/Learn/CSS
- JS: https://developer.mozilla.org/es/docs/Learn/JavaScript
-->
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Este es el título que se muestra en el navegador. -->
    <title>¡Hola Andres!</title>
    <!-- Este es el estilo de la página. ¡Puedes modificarlo como quieras! -->
    <style>
      :root {
        font-family: system-ui;
      }
      html,
      body {
        height: 100%;
        margin: 0;
      }
      body {
        /* Centrar */
        display: flex;
        justify-content: center;
        align-items: center;
        /* Colores */
        color: hsl(173, 100%, 10%);
        background-color: hsl(102, 100%, 97%);
      }
    </style>
    <!-- Dentro del head puedes agregar también otros scripts de librerías. -->
    <script src="node_modules/confetti-js/dist/index.min.js"></script>
    <script>
      var confettiSettings = { target: 'my-canvas' };
      var confetti = new ConfettiGenerator(confettiSettings);
      confetti.render();

      // Activa el confeti
      confetti.render();
    </script>

    <!-- Fin de head. -->
  </head>
  <script>
  </script>

  <!-- Dentro de body puedes añadir y modificar el contenido de la página. -->
  <body>
    <h1>¡Hola Andres!</h1>
    <canvas id="my-canvas"></canvas>
  </body>
  <script>
    // Aquí puedes dejar código JavaScript que se ejecutará cuando la página se cargue.
    // Importante: no debes importar ningún script externo aquí.
    // Para eso, utiliza script src dentro del head.
  </script>
</html>