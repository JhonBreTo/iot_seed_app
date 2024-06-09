<template>
  <layout_auth class="container">
    <div class="centered">
      <h1>Política de Privacidad y Gestión de Datos</h1>
      <section>
        <h2>Introducción</h2>
        <p>
          Esta Política de Privacidad y Gestión de Datos describe el tratamiento, almacenamiento y uso de
          los datos recopilados a través de nuestra aplicación. Nos comprometemos a garantizar la
          transparencia y el cumplimiento de las normativas de protección de datos vigentes. Este
          documento está disponible para todos los usuarios y puede ser consultado en cualquier momento.
        </p>
      </section>
      <section>
        <h2>1. Recopilación de Datos</h2>
        <p>
          Recopilamos datos de los dispositivos IoT conectados a nuestra aplicación para proporcionar
          servicios eficientes y personalizados. Los tipos de datos que recopilamos incluyen, pero no se
          limitan a:
        </p>
        <ul>
          <li>Datos de sensores (temperatura, humedad, etc.)</li>
          <li>Datos de actuadores (estado, configuración, etc.)</li>
          <li>Datos de uso y rendimiento de dispositivos.</li>
        </ul>
      </section>
      <section>
        <h2>2. Tratamiento de Datos</h2>
        <p>El tratamiento de datos se realiza con el objetivo de:</p>
        <ul>
          <li>Mejorar la interacción entre estudiantes y dispositivos IoT.</li>
          <li>Analizar y visualizar datos para fines educativos y de investigación.</li>
          <li>Supervisar y controlar dispositivos IoT en tiempo real.</li>
        </ul>
      </section>
      <section>
        <h2>3. Almacenamiento de Datos</h2>
        <p>
          Los datos recopilados se almacenan de manera segura en servidores protegidos. Implementamos
          medidas de seguridad técnicas y organizativas para proteger los datos contra el acceso no
          autorizado, la alteración, la divulgación o la destrucción.
        </p>
      </section>
      <section>
        <h2>4. Uso de Datos</h2>
        <p>Los datos recopilados se utilizan para:</p>
        <ul>
          <li>Proveer funcionalidades de la aplicación y mejorar la experiencia del usuario</li>
          <li>Realizar análisis y reportes para fines educativos y de investigación</li>
          <li>Supervisar y mantener el rendimiento y la seguridad de los dispositivos IoT</li>
        </ul>
      </section>
      <section>
        <h2>5. Transparencia y Derechos del Usuario</h2>
        <p>Nos comprometemos a ser transparentes con nuestros usuarios sobre cómo se utilizan sus datos.</p>
        <p>Los usuarios tienen los siguientes derechos:</p>
        <ul>
          <li>Acceder a sus datos personales</li>
          <li>Solicitar la eliminación de sus datos</li>
          <li>Oponerse al procesamiento de sus datos personales</li>
        </ul>
      </section>
      <section>
        <h2>6. Cumplimiento de Normativas</h2>
        <p>
          Cumplimos con las normativas de protección de datos aplicables, incluyendo, pero no limitado a:
        </p>
        <ul>
          <li>Reglamento General de Protección de Datos (GDPR)</li>
          <li>Ley de Protección de Datos Personales (Colombia)</li>
        </ul>
      </section>
      <section>
        <h2>7. Accesibilidad del Documento</h2>
        <p>
          Esta Política de Privacidad y Gestión de Datos está accesible para todos los usuarios a través
          de nuestra aplicación.
        </p>
      </section>
      <section>
        <h2>8. Actualizaciones de la Política</h2>
        <p>
          Nos reservamos el derecho de actualizar esta política periódicamente para reflejar cambios en
          nuestras prácticas de privacidad y gestión de datos. Las actualizaciones se comunicarán a los
          usuarios a través de la aplicación y entrarán en vigor inmediatamente después de su publicación.
        </p>
      </section>
    </div>
  </layout_auth>
</template>

<script>
export default {
  layout: 'auth'
};
</script>

<style scoped>
.container {
  padding: 20px;
  margin: 20px;
  max-width: 800px;
  margin: 0 auto;
  font-family: Arial, sans-serif;
}

.centered {
  text-align: left;
}

h1 {
  font-size: 2em;
  margin-bottom: 20px;
}

h2 {
  font-size: 1.5em;
  margin-top: 20px;
}

p {
  margin: 10px 0;
  line-height: 1.6;
}

ul {
  margin: 10px 0;
  padding-left: 20px;
}

li {
  margin: 5px 0;
}
</style>
