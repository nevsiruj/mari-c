<template>
  <div class="font-sans antialiased">
    <!-- Header -->
    <header class="bg-blue-600 text-white p-6">
      <div class="container mx-auto flex justify-between items-center">
        <h1 class="text-3xl font-bold">Yoga con [Nombre]</h1>
        <nav>
          <ul class="flex space-x-4">
            <li><a href="#home" class="hover:underline">Inicio</a></li>
            <li><a href="#about" class="hover:underline">Sobre mí</a></li>
            <li><a href="#classes" class="hover:underline">Clases</a></li>
            <li><a href="#contact" class="hover:underline">Contacto</a></li>
          </ul>
        </nav>
      </div>
    </header>

    <!-- Hero Section -->
    <section
      id="home"
      class="bg-cover bg-center h-screen flex items-center justify-center text-center text-white"
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
            <h3 class="text-xl font-bold mb-2">Clase de Vinyasa</h3>
            <p class="text-gray-700">
              Una práctica dinámica que fluye con la respiración.
            </p>
          </div>
          <div class="bg-white p-6 rounded shadow-lg">
            <h3 class="text-xl font-bold mb-2">Clase de Hatha</h3>
            <p class="text-gray-700">
              Enfoque en posturas y técnicas de respiración.
            </p>
          </div>
          <div class="bg-white p-6 rounded shadow-lg">
            <h3 class="text-xl font-bold mb-2">Clase de Meditación</h3>
            <p class="text-gray-700">
              Sesiones guiadas para encontrar calma y claridad.
            </p>
          </div>
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
