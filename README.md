<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>L e L Variedades</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            primario: '#3ABEFF',
          }
        }
      }
    }
  </script>
</head>
<body class="bg-primario text-white font-sans min-h-screen">

  <header class="bg-white text-primario p-4 shadow-md">
    <h1 class="text-3xl font-bold text-center">L e L Variedades</h1>
  </header>

  <main class="p-6 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
    
    <!-- Luminária Panda -->
    <div class="bg-white text-black rounded-2xl shadow-lg p-4">
      <img src="26a0d75eb10c74688a2fe7f089c6b2083.webp" alt="Luminária Panda" class="rounded-xl w-full h-48 object-contain mb-4">
      <h2 class="text-xl font-semibold mb-2">Luminária Panda</h2>
      <p class="mb-2">Abajur noturno com toque fofo e recarregável. Ideal para decorar e iluminar com estilo.</p>
      <span class="font-bold text-primario">R$ 65,00</span>
    </div>
  </main>

  <footer class="bg-white text-center text-primario p-4 mt-8">
    &copy; 2025 L e L Variedades. Todos os direitos reservados.
    <div class="mt-2">
      <a href="https://wa.me/554188098381" target="_blank" class="inline-block mt-2 px-4 py-2 bg-primario text-white rounded-full shadow hover:bg-blue-400 transition">
        Fale conosco no WhatsApp
      </a>
    </div>
  </footer>

</body>
</html>
