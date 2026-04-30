<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Marina — Эксперт по недвижимости</title>

  <!-- Tailwind -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Lucide -->
  <script src="https://unpkg.com/lucide@latest"></script>

  <!-- Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            emeraldDark: '#004D40',
            gold: '#C5A059'
          },
          fontFamily: {
            serif: ['Playfair Display'],
            sans: ['Inter']
          }
        }
      }
    }
  </script>

  <style>
    .fade-in {
      animation: fadeIn 1.2s ease forwards;
      opacity: 0;
    }

    @keyframes fadeIn {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>

<body class="bg-black text-white font-sans">

<!-- HERO -->
<section class="min-h-screen flex items-center justify-center text-center px-6 bg-gradient-to-b from-black via-emeraldDark to-black">
  <div class="max-w-4xl fade-in">
    <h1 class="text-4xl md:text-6xl font-serif mb-6 leading-tight">
      Экспертная недвижимость<br>
      <span class="text-gold">с финансовой стратегией</span>
    </h1>

    <p class="text-gray-300 text-lg md:text-xl mb-8">
      20+ лет в банковской сфере. Помогаю покупать недвижимость как инвестицию, а не ошибку.
    </p>

    <div class="flex flex-col md:flex-row gap-4 justify-center">
      <a href="https://wa.me/79174387460"
         class="bg-gold text-black px-8 py-4 rounded-full font-medium text-lg hover:scale-105 transition">
         Написать в WhatsApp
      </a>

      <a href="#services"
         class="border border-gold px-8 py-4 rounded-full text-gold hover:bg-gold hover:text-black transition">
         Услуги
      </a>
    </div>
  </div>
</section>

<!-- TRUST -->
<section class="py-16 px-6 bg-black text-center">
  <div class="max-w-5xl mx-auto grid md:grid-cols-4 gap-8">
    <div>
      <h3 class="text-3xl text-gold font-semibold">20+</h3>
      <p class="text-gray-400">лет опыта</p>
    </div>
    <div>
      <h3 class="text-3xl text-gold font-semibold">100+</h3>
      <p class="text-gray-400">сделок</p>
    </div>
    <div>
      <h3 class="text-3xl text-gold font-semibold">0</h3>
      <p class="text-gray-400">рисков для клиента</p>
    </div>
    <div>
      <h3 class="text-3xl text-gold font-semibold">24/7</h3>
      <p class="text-gray-400">поддержка</p>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section class="py-20 px-6 bg-emeraldDark text-center">
  <div class="max-w-4xl mx-auto">
    <h2 class="text-3xl md:text-4xl font-serif mb-6 text-gold">
      Финансовый подход к недвижимости
    </h2>

    <p class="text-gray-200 text-lg leading-relaxed">
      Марина — эксперт с более чем 20-летним опытом в банковской сфере, бухгалтерии и страховании.
      Каждая сделка рассматривается не как покупка, а как финансовое решение.
      Главная цель — сохранить и приумножить ваши деньги.
    </p>
  </div>
</section>

<!-- SERVICES -->
<section id="services" class="py-20 px-6 bg-black">
  <div class="max-w-6xl mx-auto">

    <h2 class="text-3xl md:text-4xl text-center font-serif text-gold mb-12">
      Услуги
    </h2>

    <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">

      <div class="p-6 border border-gray-800 rounded-2xl hover:border-gold hover:shadow-xl transition">
        <i data-lucide="building" class="text-gold mb-4"></i>
        <h3 class="text-xl mb-2">Новостройки</h3>
        <p class="text-gray-400 text-sm">
          Помогу выбрать объект с реальной инвестиционной выгодой.
        </p>
      </div>

      <div class="p-6 border border-gray-800 rounded-2xl hover:border-gold hover:shadow-xl transition">
        <i data-lucide="banknote" class="text-gold mb-4"></i>
        <h3 class="text-xl mb-2">Ипотека</h3>
        <p class="text-gray-400 text-sm">
          Подбор выгодных условий и снижение переплаты.
        </p>
      </div>

      <div class="p-6 border border-gray-800 rounded-2xl hover:border-gold hover:shadow-xl transition">
        <i data-lucide="home" class="text-gold mb-4"></i>
        <h3 class="text-xl mb-2">Вторичный рынок</h3>
        <p class="text-gray-400 text-sm">
          Проверка рисков и безопасные сделки.
        </p>
      </div>

      <div class="p-6 border border-gray-800 rounded-2xl hover:border-gold hover:shadow-xl transition">
        <i data-lucide="calculator" class="text-gold mb-4"></i>
        <h3 class="text-xl mb-2">Бухгалтерия</h3>
        <p class="text-gray-400 text-sm">
          Оптимизация налогов и финансовая прозрачность.
        </p>
      </div>

    </div>
  </div>
</section>

<!-- CTA -->
<section class="py-20 px-6 bg-gradient-to-b from-black to-emeraldDark text-center">
  <div class="max-w-3xl mx-auto">

    <h2 class="text-3xl md:text-4xl font-serif mb-6">
      Готовы принять правильное финансовое решение?
    </h2>

    <p class="text-gray-300 mb-8">
      Напишите — разберём вашу ситуацию и подберём лучшее решение
    </p>

    <a href="https://wa.me/79174387460"
       class="inline-flex items-center gap-3 bg-gold text-black px-10 py-5 rounded-full text-xl font-medium hover:scale-105 transition shadow-lg">

      <i data-lucide="message-circle"></i>
      Написать в WhatsApp
    </a>

  </div>
</section>

<!-- FOOTER -->
<footer class="py-8 text-center text-gray-500 text-sm bg-black">
  © 2026 Marina. Все права защищены.
</footer>

<script>
  lucide.createIcons();
</script>

</body>
</html>
