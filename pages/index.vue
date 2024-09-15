<template>
  <div class="font-sans antialiased">
    <!-- Header -->
    <header class="bg-blue-600 text-white p-6">
      <div class="container mx-auto flex justify-between items-center">
        <h1 class="text-3xl font-bold">Yoga con Mariel</h1>
        <nav>
          <ul class="flex space-x-4">
            <li><a href="#home" class="hover:underline">Inicio</a></li>
            <li><a href="#about" class="hover:underline">Sobre mí</a></li>
            <li><a href="#classes" class="hover:underline">Clases</a></li>
            <li><a href="#contact" class="hover:underline">Contacto</a></li>
            <li><a href="#course" class="hover:underline">Curso</a></li>
          </ul>
        </nav>
      </div>
    </header>

    <!-- Hero Section -->
    <section
      id="home"
      class="bg-cover bg-center h-screen flex items-center justify-center text-center text-white"
      style="background-image: url('https://source.unsplash.com/1600x900/?yoga')"
    >
      <div class="bg-black bg-opacity-50 p-12 rounded">
        <h2 class="text-4xl font-bold mb-4">Encuentra la Paz Interior</h2>
        <p class="text-lg mb-8">
          Únete a nuestras clases de yoga y mejora tu bienestar físico y mental.
        </p>
        <a
          href="#contact"
          class="bg-yellow-500 text-black py-2 px-6 rounded hover:bg-yellow-400"
          >Contáctame</a
        >
      </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-12 bg-gray-100">
      <div class="container mx-auto text-center">
        <h2 class="text-3xl font-bold mb-4">Sobre Mí</h2>
        <p class="text-lg">
          Soy [Nombre], una apasionada instructora de yoga con [X] años de
          experiencia. Mi misión es ayudarte a encontrar equilibrio y bienestar
          a través de la práctica del yoga.
        </p>
      </div>
    </section>

    <!-- Classes Section -->
    <section id="classes" class="py-12">
      <div class="container mx-auto text-center">
        <h2 class="text-3xl font-bold mb-4">Clases</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
          <div class="bg-white p-6 rounded shadow-lg">
            <img src="https://source.unsplash.com/800x600/?yoga,vinyasa" alt="Clase de Vinyasa" class="w-full h-40 object-cover rounded mb-4" />
            <h3 class="text-xl font-bold mb-2">Clase de Vinyasa</h3>
            <p class="text-gray-700">
              Una práctica dinámica que fluye con la respiración.
            </p>
          </div>
          <div class="bg-white p-6 rounded shadow-lg">
            <img src="https://source.unsplash.com/800x600/?yoga,hatha" alt="Clase de Hatha" class="w-full h-40 object-cover rounded mb-4" />
            <h3 class="text-xl font-bold mb-2">Clase de Hatha</h3>
            <p class="text-gray-700">
              Enfoque en posturas y técnicas de respiración.
            </p>
          </div>
          <div class="bg-white p-6 rounded shadow-lg">
            <img src="https://source.unsplash.com/800x600/?meditation" alt="Clase de Meditación" class="w-full h-40 object-cover rounded mb-4" />
            <h3 class="text-xl font-bold mb-2">Clase de Meditación</h3>
            <p class="text-gray-700">
              Sesiones guiadas para encontrar calma y claridad.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- Course Section -->
    <section id="course" class="py-12 bg-gray-100">
      <div class="container mx-auto text-center">
        <h2 class="text-3xl font-bold mb-4">Curso Especial</h2>
        <div class="bg-white p-6 rounded shadow-lg">
          <img src="https://source.unsplash.com/800x600/?course" alt="Curso" class="w-full h-64 object-cover rounded mb-4" />
          <h3 class="text-xl font-bold mb-2">Armonización de Chakras, Reiki Angelical y Registros Akashicos</h3>
          <p class="text-lg mb-4">
            <strong>Modalidad por Zoom:</strong> 4 Encuentros<br>
            <strong>Fechas:</strong> Jueves 10, 17, 24 y 31 de Octubre<br>
            <strong>Duración:</strong> 2 Horas<br>
            <strong>Horario:</strong> 20 hs<br>
            <strong>Material:</strong> Se envía material en PDF<br>
            <strong>Valor Total:</strong> $24,900 (pesos argentinos) / U$d 30,00 (pago por Western Union)
          </p>
          <a href="https://mpago.la/1JJUKba" class="bg-yellow-500 text-black py-2 px-6 rounded hover:bg-yellow-400" target="_blank">Link de Pago</a>
          <p class="text-gray-700 mt-4">Transferencia a CBU 1430001713015184340017 BRUBANK<br>
          Alias: cuerda.muelle.tiempo<br>
          Cuevas Mariel Ermelinda</p>
        </div>
        <h3 class="text-xl font-bold mt-8 mb-4">Temario del Curso</h3>
        <div class="bg-white p-6 rounded shadow-lg mb-6">
          <h4 class="text-lg font-bold mb-2">Clase 1: Armonización de Chakras</h4>
          <p class="text-gray-700">Qué son, la importancia de la armonización de los chakras en nuestra vida. Diferentes técnicas de armonización. Incluye audio de meditación para armonizar.</p>
          <img src="https://source.unsplash.com/800x600/?chakra" alt="Clase de Chakras" class="w-full h-40 object-cover rounded mt-4" />
        </div>
        <div class="bg-white p-6 rounded shadow-lg mb-6">
          <h4 class="text-lg font-bold mb-2">Clase 2: Reiki Angelical</h4>
          <p class="text-gray-700">Sintonización en Reiki Angelical y Maestría. Este curso te permitirá dar Reiki y sintonizar a otras personas.</p>
          <img src="https://source.unsplash.com/800x600/?reiki" alt="Clase de Reiki Angelical" class="w-full h-40 object-cover rounded mt-4" />
        </div>
        <div class="bg-white p-6 rounded shadow-lg">
          <h4 class="text-lg font-bold mb-2">Clases 3 y 4: Registros Akashicos</h4>
          <p class="text-gray-700">Nivel I: Lectura de Registros Akashicos, qué es el Akasha, cómo abrir nuestros propios registros, práctica en vivo.<br>
          Nivel II y III: Maestría en Lectura de Registros Akashicos, cómo abrir registros a otras personas, hogares, comercios, y sanación kármica. Incluye audio de meditación para conectar con el símbolo individual de cada uno.</p>
          <img src="https://source.unsplash.com/800x600/?akashic-records" alt="Clase de Registros Akashicos" class="w-full h-40 object-cover rounded mt-4" />
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-12 bg-gray-100">
      <div class="container mx-auto text-center">
        <h2 class="text-3xl font-bold mb-4">Contacto</h2>
        <p class="text-lg mb-6">
          Para más información o para inscribirte en nuestras clases, no dudes
          en contactarme.
        </p>
        <a
          href="mailto:info@yoga.com"
          class="bg-yellow-500 text-black py-2 px-6 rounded hover:bg-yellow-400"
          >Enviar Correo</a
        >
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-blue-600 text-white py-4 text-center">
      <p>&copy; 2024 Yoga con [Nombre]. Todos los derechos reservados.</p>
    </footer>
  </div>
</template>

<script setup>
// Puedes añadir lógica de Vue si es necesario
</script>

<style scoped>
/* Aquí puedes añadir estilos específicos si es necesario */
</style>
