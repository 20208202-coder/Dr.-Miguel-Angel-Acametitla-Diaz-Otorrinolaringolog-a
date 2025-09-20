[index.html](https://github.com/user-attachments/files/22436635/index.html)
<!DOCTYPE html>
<html lang="es" class="transition-colors duration-500">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> Dr. Miguel Angel Acametitla Diaz </title>
  <subtitle>Otorrinolaringología</subtitle>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <!-- Tipografía elegante -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    body, header, section, footer {
      transition: all 0.4s ease-in-out;
    }
    body {
      font-family: 'Playfair Display', serif;
    }
  </style>
  <script>
    function toggleDarkMode() {
      document.documentElement.classList.toggle('dark');
    }
  </script>
</head>
<body class="bg-gray-50 text-gray-900 dark:bg-black dark:text-gray-100">
  <!-- Header -->
  <header class="bg-black text-white p-6 shadow-lg">
    <div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-center">
      <!-- Logo -->
      <div class="flex items-center gap-3">
        <img src="https://drive.google.com/uc?export=view&id=10okANm_OF7GfGJLh7xJkXxUQj1MVn75m" 
             alt="Logo Dr. Miguel Angel Acametitla Diaz" width="100" height="100" class="drop-shadow-lg">
        <h1 class="text-3xl font-bold">Dr. Miguel Angel Acametitla Diaz</h1>
      </div>
      <!-- Menú -->
      <nav class="mt-4 md:mt-0 flex items-center gap-6">
        <ul class="flex flex-wrap gap-6 text-lg">
          <li><a href="#inicio" class="hover:text-gray-300">Inicio</a></li>
          <li><a href="#medico" class="hover:text-gray-300">Médico</a></li>
          <li><a href="#servicios" class="hover:text-gray-300">Servicios</a></li>
          <li><a href="#horarios" class="hover:text-gray-300">Horarios</a></li>
          <li><a href="#ubicacion" class="hover:text-gray-300">Ubicación</a></li>
          <li><a href="#contacto" class="hover:text-gray-300">Contacto</a></li>
        </ul>
        <!-- Botón dark mode -->
        <button onclick="toggleDarkMode()" class="ml-4 bg-gray-800 text-white px-3 py-2 rounded-lg hover:bg-gray-600 dark:bg-white dark:text-black dark:hover:bg-gray-200 transition">
          🌙 / ☀️
        </button>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section id="inicio" class="bg-gray-100 dark:bg-gray-900 py-20 text-center">
    <h2 class="text-4xl font-bold text-gray-900 dark:text-gray-200">Dr. Miguel Angel Acametitla Diaz</h2>
    <p class="mt-4 text-lg text-gray-700 dark:text-gray-300 max-w-2xl mx-auto">
      Otorrinolaringología: atención integral.
    </p>
  </section>

  <!-- Datos del Médico -->
  <section id="medico" class="max-w-6xl mx-auto py-16 px-6">
    <h2 class="text-3xl font-bold text-gray-900 dark:text-gray-200 mb-6 border-b-4 border-gray-400 pb-2">Datos del Médico</h2>
    <div class="bg-white dark:bg-gray-900 rounded-2xl shadow-lg p-8">
      <p class="text-lg"><b>Dr. Miguel Angel Acametitla Diaz</b></p>
      <p>Médico Cirujano y Partero – BUAP- Cédula Profesional: 11459403</p>
      <p>Especialista en Otorrinolaringología – Cédula Profesional: 13577594</p>
      <p>Avalado por la Benemérita Universidad Autónoma de Puebla</p>
      <p>Certificado por el Consejo Mexicano de Otorrinolaringología y Cirugía de Cabeza y Cuello</p>
    </div>
  </section>

  <!-- Servicios -->
  <section id="servicios" class="bg-gray-50 dark:bg-gray-950 py-16 px-6">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-3xl font-bold text-gray-900 dark:text-gray-200 mb-6 border-b-4 border-gray-400 pb-2">Servicios</h2>
      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="bg-white dark:bg-gray-900 p-6 rounded-xl shadow hover:shadow-xl transition">
          <h3 class="text-xl font-semibold mb-2">Atención en</h3>
          <p>Oído - Naríz - Garganta.</p>
        </div>
        <div class="bg-white dark:bg-gray-900 p-6 rounded-xl shadow hover:shadow-xl transition">
          <h3 class="text-xl font-semibold mb-2">Cirugía de mínima invasión</h3>
          <p>Naríz - Senos paranasales - Laringe.</p>
        </div>
        <div class="bg-white dark:bg-gray-900 p-6 rounded-xl shadow hover:shadow-xl transition">
          <h3 class="text-xl font-semibold mb-2">Atención médica y seguimiento.</h3>
          <p>Vértigo - Sordera.</p>
        </div>
        <!-- Imagen independiente -->
        <div class="bg-white dark:bg-gray-900 p-6 rounded-xl shadow hover:shadow-xl transition flex justify-center items-center">
          <img src="https://drive.google.com/uc?export=view&id=1GUxeWcPK2NRcp77H-RORZFtK2pFt0MuZ" 
               alt="Imagen Servicios Otorrinolaringología" class="rounded-lg shadow-lg max-h-64 object-contain">
        </div>
      </div>
    </div>
  </section>

  <!-- Horarios -->
  <section id="horarios" class="max-w-6xl mx-auto py-16 px-6">
    <h2 class="text-3xl font-bold text-gray-900 dark:text-gray-200 mb-6 border-b-4 border-gray-400 pb-2">Horarios</h2>
    <div class="bg-white dark:bg-gray-900 rounded-2xl shadow-lg p-8 text-lg">
      <p><b>Lunes a Viernes:</b> 17:00 hrs - 20:00 hrs</p>
      <p><b>Sábados:</b> 11:00 hrs - 14:00 hrs</p>
    </div>
  </section>

  <!-- Ubicación Santé Hospital de Especialidades -->
  <section id="ubicacion" class="bg-gray-100 dark:bg-gray-950 py-16 px-6">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-3xl font-bold text-gray-900 dark:text-gray-200 mb-6 border-b-4 border-gray-400 pb-2">Ubicación</h2>
      <p class="mb-4 text-lg">Av. Democracia No.162, Santo Toribio Xicohtzinco, Tlaxcala.</p>
      <iframe src="https://www.google.com/maps/embed?pb=!1m18..." 
              width="100%" height="300" style="border:0;" 
              allowfullscreen="" loading="lazy" class="rounded-lg shadow"></iframe>
    </div>
  </section>

  <!-- Ubicación CEMZA Centro de Especialidades Médicas -->
  <section id="ubicacion2" class="bg-gray-100 dark:bg-gray-950 py-16 px-6">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-3xl font-bold text-gray-900 dark:text-gray-200 mb-6 border-b-4 border-gray-400 pb-2">Ubicación</h2>
      <p class="mb-4 text-lg">Lerdo de Tejada No.27, Zactelco, Tlaxcala.</p>
      <iframe src="https://www.google.com/maps/embed?pb=!1m18..." 
              width="100%" height="300" style="border:0;" 
              allowfullscreen="" loading="lazy" class="rounded-lg shadow"></iframe>
    </div>
  </section>

  <!-- Contacto -->
  <section id="contacto" class="max-w-6xl mx-auto py-16 px-6">
    <h2 class="text-3xl font-bold text-gray-900 dark:text-gray-200 mb-6 border-b-4 border-gray-400 pb-2">Contacto</h2>
    <div class="grid md:grid-cols-2 gap-8">
      <div class="bg-white dark:bg-gray-900 rounded-2xl shadow-lg p-8 text-lg">
        <p><b>Teléfono Santé Hospital de especialidades:</b> 2221133267</p>
        <p><b>Teléfono CEMZA Centro de Especialidades Médicas:</b> 2461205519</p>
        <p><b>WhatsApp:</b> 2222991702</p>
        <p><b>Correo:</b> migueadz@gmail.com</p>
      </div>
      <form class="bg-white dark:bg-gray-900 rounded-2xl shadow-lg p-8 space-y-4">
        <input type="text" placeholder="Nombre" class="w-full border p-3 rounded-lg focus:outline-none focus:ring-2 focus:ring-gray-400 dark:bg-gray-800 dark:border-gray-700">
        <input type="email" placeholder="Correo" class="w-full border p-3 rounded-lg focus:outline-none focus:ring-2 focus:ring-gray-400 dark:bg-gray-800 dark:border-gray-700">
        <textarea placeholder="Mensaje" class="w-full border p-3 rounded-lg focus:outline-none focus:ring-2 focus:ring-gray-400 dark:bg-gray-800 dark:border-gray-700"></textarea>
        <button class="bg-black text-white px-6 py-3 rounded-lg hover:bg-gray-700 transition">Enviar</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-black text-white text-center p-6 mt-12">
    © 2025 Dr. Miguel Angel Acametitla Diaz Otorrinolaringología | Todos los derechos reservados
  </footer>

  <!-- Botón flotante de WhatsApp -->
  <a href="https://wa.me/522229876543" target="_blank" 
     class="fixed bottom-6 right-6 bg-green-500 text-white p-4 rounded-full shadow-lg hover:bg-green-600 transition">
    <i class="fab fa-whatsapp text-3xl"></i>
  </a>
</body>
</html>
