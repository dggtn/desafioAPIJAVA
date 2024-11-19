  <h1>DesafioAPIJava - Proyecto Oracle 2024</h1>
  <p><strong>Descripción:</strong> Proyecto para aprender a realizar llamadas a una API REST en el contexto de un backend desarrollado en <strong>Java</strong>, como parte del programa de formación <strong>Oracle 2024</strong>.</p>

  <h2>Descripción del Proyecto</h2>
  <p>Este proyecto tiene como objetivo enseñar cómo realizar llamadas a una API REST desde una aplicación backend desarrollada en <strong>Java</strong>. La aplicación se enfoca en consumir datos de una API externa y procesarlos para ser utilizados dentro del sistema backend.</p>
  <p>A través de este desafío, el enfoque principal es entender cómo interactuar con servicios RESTful utilizando tecnologías como <strong>Java</strong> y <strong>Spring Boot</strong>, así como manejar las respuestas obtenidas de una API de manera eficiente.</p>

  <h2>Funcionalidades</h2>
  <p>Las funcionalidades del proyecto incluyen:</p>
  <ul>
      <li><strong>Realizar solicitudes HTTP:</strong> La aplicación es capaz de hacer solicitudes GET, POST, PUT y DELETE a una API REST externa.</li>
      <li><strong>Manejo de respuestas:</strong> Se procesan las respuestas de la API, como JSON, para extraer información relevante.</li>
      <li><strong>Integración con Backend:</strong> Los datos obtenidos de la API se utilizan dentro de la aplicación backend, permitiendo su posterior uso o almacenamiento.</li>
      <li><strong>Gestión de errores:</strong> Se manejan errores como fallos en la conexión a la API o respuestas inesperadas con un manejo adecuado de excepciones.</li>
  </ul>

  <h2>Tecnologías Utilizadas</h2>
  <ul>
      <li><strong>Java</strong>: Lenguaje de programación utilizado para desarrollar la lógica de backend.</li>
      <li><strong>Spring Boot</strong>: Framework utilizado para construir la aplicación backend de manera rápida y sencilla.</li>
      <li><strong>RestTemplate</strong>: Utilizado para realizar solicitudes HTTP a la API externa.</li>
      <li><strong>Jackson</strong>: Biblioteca para procesar y convertir las respuestas JSON de la API.</li>
      <li><strong>JUnit</strong>: Para realizar pruebas unitarias y asegurar que el código funcione correctamente.</li>
      <li><strong>Postman</strong>: Utilizado para probar y verificar las solicitudes a la API.</li>
  </ul>

  <h2>Instrucciones para Ejecutar el Proyecto</h2>
  <p>Para ejecutar este proyecto, sigue estos pasos:</p>
  <ol>
      <li><strong>Clonar el repositorio</strong>:
          <pre><code>git clone https://github.com/tu-usuario/desafio-api-java.git</code></pre>
      </li>
      <li><strong>Acceder al directorio del proyecto</strong>:
          <pre><code>cd desafio-api-java</code></pre>
      </li>
      <li><strong>Instalar las dependencias</strong>:
          <pre><code>mvn install</code></pre>
      </li>
      <li><strong>Ejecutar la aplicación</strong>:
          <pre><code>mvn spring-boot:run</code></pre>
      </li>
      <li>La aplicación estará disponible en <a href="http://localhost:8080" target="_blank">http://localhost:8080</a>.</li>
  </ol>

  <h2>Uso de la API</h2>
  <p>A continuación, se presentan los endpoints de la API que pueden ser utilizados:</p>

  <h3>1. Realizar una solicitud GET a la API</h3>
  <p>Este endpoint realiza una solicitud GET a una API externa y devuelve los datos obtenidos.</p>
  <pre><code>GET /api/obtenerDatos</code></pre>
  <h4>Ejemplo de respuesta:</h4>
  <pre><code>
  {
      "status": "success",
      "data": {
          "id": 1,
          "nombre": "Juan Pérez",
          "email": "juan.perez@example.com"
      }
  }
  </code></pre>

  <h3>2. Realizar una solicitud POST a la API</h3>
  <p>Este endpoint envía datos a una API externa mediante una solicitud POST.</p>
  <pre><code>POST /api/enviarDatos</code></pre>
  <h4>Ejemplo de solicitud:</h4>
  <pre><code>
  {
      "nombre": "Ana Gómez",
      "email": "ana.gomez@example.com"
  }
  </code></pre>

  <h3>3. Manejo de errores</h3>
  <p>En caso de error, la API responde con un código de error y un mensaje descriptivo.</p>
  <pre><code>
  {
      "status": "error",
      "message": "Error al realizar la solicitud"
  }
  </code></pre>

  <h2>Pruebas</h2>
  <p>El proyecto incluye pruebas unitarias utilizando <strong>JUnit</strong> para validar que las solicitudes y respuestas de la API se manejen correctamente.</p>
  <p>Para ejecutar las pruebas, utiliza el siguiente comando:</p>
  <pre><code>mvn test</code></pre>

  <h2>Contribución</h2>
  <p>Si deseas contribuir a este proyecto, sigue estos pasos:</p>
  <ol>
      <li>Haz un fork del repositorio.</li>
      <li>Crea una nueva rama para la funcionalidad o corrección de errores que deseas agregar (<code>git checkout -b feature/nueva-funcionalidad</code>).</li>
      <li>Realiza tus cambios y haz commits adecuados.</li>
      <li>Abre un pull request describiendo tus cambios y su propósito.</li>
  </ol>

  <h2>Licencia</h2>
  <p>Este proyecto está bajo la licencia <strong>MIT</strong>. Consulta el archivo LICENSE para más detalles.</p>

</body>
</html>
