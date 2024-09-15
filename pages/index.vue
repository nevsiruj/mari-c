<template>

  <div class="font-sans antialiased">
    <!-- Hero Section -->
    <section
      id="home"
      class="bg-cover bg-center h-screen flex items-center justify-center text-center text-white"
      style="background-image: url('https://source.unsplash.com/1600x900/?meditation')"
    >
      <div class="bg-yellow-500 bg-opacity-70 p-12 rounded">
        <h2 class="text-4xl font-bold mb-4">Curso de Terapias Holisticas</h2>
        <p class="text-lg mb-8">
          Únete a mi curso de Armonización de Chakras, Reiki Angelical y Registros Akashicos. Transforma tu vida y acompaña about otras personas.
        </p>
        <a
          href="#course"
          class="bg-pink-400 text-white py-2 px-6 rounded hover:bg-pink-300"
          >Descubre Más</a
        >
      </div>
    </section>

     <!-- Video Section -->
    <section id="video" class="py-12 bg-purple-100">
      <div class="container mx-auto text-center">
        <h2 class="text-3xl font-bold mb-4 text-purple-800">Mira Nuestro Video</h2>
        <div class="flex justify-center">
          <iframe
            width="560"
            height="315"
            src="https://www.youtube.com/embed/qXion5FVs5A"
            title="Video del Curso"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
            class="rounded"
          ></iframe>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-12 bg-purple-100">
      <div class="container mx-auto text-center">
        <h2 class="text-3xl font-bold mb-4 text-purple-800">Sobre Mí</h2>
        <p class="text-lg text-purple-700">
          Soy Mariel Cuevas, apasionada Profesora de Yoga, Terapeuta en Flores de Bach, Consteladora Familiar, 
          Master Reiki Usui y Angelical, Lectora de Registro Akashicos y Coach Ontologica. Mi misión es acompañarte en procesos de transformacion para lograr tu equilibrio
          y bienestar por medio de diferentes técnicas y terapias.
        </p>
      </div>
    </section>

    <!-- Course Section -->
    <section id="course" class="py-12 bg-purple-100">
      <div class="container mx-auto text-center">
        <h2 class="text-3xl font-bold mb-4 text-purple-800">Curso Especial</h2>
        <div class="bg-white p-6 rounded shadow-lg">
          <img src="https://source.unsplash.com/800x600/?course" alt="Curso" class="w-full h-64 object-cover rounded mb-4" />
          <h3 class="text-xl font-bold mb-2 text-purple-800">Armonización de Chakras, Reiki Angelical y Registros Akashicos</h3>
          <p class="text-lg mb-4 text-purple-700">
            <strong>Modalidad por Zoom:</strong> 4 Encuentros<br>
            <strong>Fechas:</strong> Jueves 10, 17, 24 y 31 de Octubre<br>
            <strong>Duración:</strong> 2 Horas<br>
            <strong>Horario:</strong> 20 hs<br>
            <strong>Material:</strong> Se envía material en PDF<br>
            <strong>Valor Total:</strong> $24,900 (pesos argentinos) / U$d 30,00 (pago por Western Union)
          </p>
          <a href="https://mpago.la/1JJUKba" class="bg-pink-400 text-white py-2 px-6 rounded hover:bg-pink-300" target="_blank">Link de Pago</a>
          <p class="text-purple-700 mt-4">Transferencia a CBU 1430001713015184340017 BRUBANK<br>
          Alias: cuerda.muelle.tiempo<br>
          Cuevas Mariel Ermelinda</p>
        </div>
        <h3 class="text-xl font-bold mt-8 mb-4 text-purple-800">Temario del Curso</h3>
        <div class="bg-white p-6 rounded shadow-lg mb-6">
          <h4 class="text-lg font-bold mb-2 text-purple-800">Clase 1: Armonización de Chakras</h4>
          <p class="text-gray-700">Qué son, la importancia de la armonización de los chakras en nuestra vida. Diferentes técnicas de armonización. Incluye audio de meditación para armonizar.</p>
          <img src="https://source.unsplash.com/800x600/?chakra" alt="Clase de Chakras" class="w-full h-40 object-cover rounded mt-4" />
        </div>
        <div class="bg-white p-6 rounded shadow-lg mb-6">
          <h4 class="text-lg font-bold mb-2 text-purple-800">Clase 2: Reiki Angelical</h4>
          <p class="text-gray-700">Sintonización en Reiki Angelical y Maestría. Este curso te permitirá dar Reiki y sintonizar a otras personas.</p>
          <img src="https://source.unsplash.com/800x600/?reiki" alt="Clase de Reiki Angelical" class="w-full h-40 object-cover rounded mt-4" />
        </div>
        <div class="bg-white p-6 rounded shadow-lg">
          <h4 class="text-lg font-bold mb-2 text-purple-800">Clases 3 y 4: Registros Akashicos</h4>
          <p class="text-gray-700">Nivel I: Lectura de Registros Akashicos, qué es el Akasha, cómo abrir nuestros propios registros, práctica en vivo.<br>
          Nivel II y III: Maestría en Lectura de Registros Akashicos, cómo abrir registros a otras personas, hogares, comercios, y sanación kármica. Incluye audio de meditación para conectar con el símbolo individual de cada uno.</p>
          <img src="https://source.unsplash.com/800x600/?akashic-records" alt="Clase de Registros Akashicos" class="w-full h-40 object-cover rounded mt-4" />
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-12 bg-purple-100">
      <div class="container mx-auto text-center">
        <h2 class="text-3xl font-bold mb-4 text-purple-800">Contacto</h2>
        <p class="text-lg mb-6 text-purple-700">
          Para más información o para inscribirte en nuestras clases, no dudes
          en contactarme.
        </p>
        <a
          href="wa.me/+5493544438308"
          class="bg-green-400 text-white py-2 px-6 rounded hover:bg-pink-300"
          >Enviar WhatsApp</a
        >
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-purple-800 text-white py-4 text-center">
      <p>&copy; 2024 Mariel Cuevas. Todos los derechos reservados.</p>
    </footer>
  </div>
</template>

<script setup>
// Puedes añadir lógica de Vue si es necesario
</script>

<style scoped>
/* Aquí puedes añadir estilos específicos si es necesario */
</style>
