<!DOCTYPE html><html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Profil Adrian</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }@keyframes pop {
  from { transform: scale(0.8); opacity: 0; }
  to { transform: scale(1); opacity: 1; }
}

.fade-up {
  animation: fadeUp 0.8s ease forwards;
}

.pop {
  animation: pop 0.5s ease forwards;
}

  </style>
</head>
<body class="bg-gradient-to-br from-gray-900 via-gray-800 to-gray-900 text-white flex items-center justify-center min-h-screen">
  <div class="backdrop-blur-lg bg-white/5 p-8 rounded-3xl shadow-2xl max-w-md w-full text-center fade-up">
    <img src="https://via.placeholder.com/120" class="w-28 h-28 rounded-full mx-auto mb-4 border-4 border-white/20 pop" />
    <h1 class="text-2xl font-bold mb-1 fade-up" style="animation-delay:0.2s">Adrian</h1>
    <p class="text-gray-300 text-sm mb-4 fade-up" style="animation-delay:0.3s">Editor foto • Suka aesthetic • Lagi belajar web 🚀</p><div class="flex justify-center gap-3 mb-5 fade-up" style="animation-delay:0.4s">
  <a href="#" class="px-4 py-2 bg-indigo-500 rounded-xl hover:bg-indigo-600 transition hover:scale-105">Instagram</a>
  <a href="#" class="px-4 py-2 bg-pink-500 rounded-xl hover:bg-pink-600 transition hover:scale-105">TikTok</a>
</div>

<div class="grid grid-cols-2 gap-3 fade-up" style="animation-delay:0.5s">
  <div class="bg-white/5 p-3 rounded-xl hover:scale-105 transition">✨ Aesthetic Edit</div>
  <div class="bg-white/5 p-3 rounded-xl hover:scale-105 transition">📸 Photo Retouch</div>
  <div class="bg-white/5 p-3 rounded-xl hover:scale-105 transition">🎨 Design</div>
  <div class="bg-white/5 p-3 rounded-xl hover:scale-105 transition">💻 Web Beginner</div>
</div>

<div class="mt-6 fade-up" style="animation-delay:0.6s">
  <a href="#" class="block w-full py-3 rounded-xl bg-gradient-to-r from-indigo-500 to-purple-500 hover:opacity-90 transition hover:scale-105">Kontak Gue</a>
</div>

  </div>
</body>
</html>
