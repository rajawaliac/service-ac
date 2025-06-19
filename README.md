<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Service AC Profesional</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          animation: {
            pulseSlow: 'pulse 2s infinite',
          }
        }
      }
    }
  </script>
</head>
<body class="bg-gray-50 text-gray-800">

  <!-- Header -->
  <header class="bg-blue-600 text-white p-6">
    <div class="container mx-auto flex justify-between items-center">
      <h1 class="text-2xl font-bold">Service AC Profesional</h1>
      <a href="#kontak" class="bg-white text-blue-600 px-4 py-2 rounded hover:bg-gray-100 transition">Hubungi Kami</a>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="text-center py-16 bg-white">
    <h2 class="text-4xl font-bold mb-4">Layanan Service AC Cepat & Terpercaya</h2>
    <p class="text-lg mb-6">Perbaikan, perawatan, dan instalasi AC dengan teknisi berpengalaman.</p>
    <a href="#layanan" class="bg-blue-600 text-white px-6 py-3 rounded hover:bg-blue-700 transition">Lihat Layanan</a>
  </section>

  <!-- Layanan -->
  <section id="layanan" class="py-16 bg-gray-100">
    <div class="container mx-auto text-center">
      <h3 class="text-3xl font-bold mb-8">Layanan Kami</h3>
      <div class="grid md:grid-cols-3 gap-6">
        <div class="bg-white p-6 rounded shadow">
          <h4 class="text-xl font-semibold mb-2">Cuci AC</h4>
          <p>Pembersihan AC secara menyeluruh untuk performa maksimal.</p>
        </div>
        <div class="bg-white p-6 rounded shadow">
          <h4 class="text-xl font-semibold mb-2">Isi Freon</h4>
          <p>Isi ulang freon dengan cepat dan aman.</p>
        </div>
        <div class="bg-white p-6 rounded shadow">
          <h4 class="text-xl font-semibold mb-2">Perbaikan AC</h4>
          <p>Perbaikan AC rusak oleh teknisi profesional dan berpengalaman.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimoni -->
  <section class="py-16 bg-white">
    <div class="container mx-auto text-center">
      <h3 class="text-3xl font-bold mb-8">Apa Kata Pelanggan</h3>
      <div class="grid md:grid-cols-2 gap-6">
        <div class="p-6 bg-gray-100 rounded shadow">
          <p>"Teknisi datang tepat waktu dan AC saya dingin kembali!"</p>
          <span class="block mt-2 font-semibold">– Budi, Jakarta</span>
        </div>
        <div class="p-6 bg-gray-100 rounded shadow">
          <p>"Layanan cepat dan harga terjangkau. Sangat puas!"</p>
          <span class="block mt-2 font-semibold">– Sari, Tangerang</span>
        </div>
      </div>
    </div>
  </section>

  <!-- Kontak -->
  <section id="kontak" class="py-16 bg-blue-600 text-white">
    <div class="container mx-auto text-center">
      <h3 class="text-3xl font-bold mb-6">Hubungi Kami Sekarang</h3>
      <p class="mb-4">WA / Telepon: <a href="tel:081234567890" class="underline">0812-3456-7890</a></p>
      <p>Email: <a href="mailto:serviceac@example.com" class="underline">serviceac@example.com</a></p>
    </div>
  </section>

  <!-- Floating WhatsApp Button -->
  <a href="https://wa.me/6285222241144?text=Halo%2C%20Pak%20Kiki%20saya%20ingin%20tanya%20mengenai%20AC"
     target="_blank"
     class="fixed bottom-6 right-6 bg-green-500 text-white px-5 py-3 rounded-full shadow-lg hover:bg-green-600 transition z-50 animate-pulseSlow">
     📱 Chat WhatsApp
  </a>

  <!-- Footer -->
  <footer class="bg-gray-800 text-white text-center p-4">
    © 2025 Service cAC Profesional. All rights reserved.
  </footer>

</body>
</html>
