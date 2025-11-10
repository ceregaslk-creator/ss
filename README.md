<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Russo+One&family=PT+Serif:wght@400;700&display=swap" rel="stylesheet" />
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
  <style>
    html { font-family: 'PT Serif', serif; } /* Основной шрифт */
    .font-russo { font-family: 'Russo One', sans-serif; }
  </style>
  <title>Перетяжка мебели SS</title>
</head>
<body class="bg-gray-100 text-gray-800">

  <!-- Header with logo -->
  <header class="bg-white shadow-md">
    <div class="container mx-auto flex items-center justify-between p-4">
      <h1 class="font-russo text-3xl text-blue-600">
        Перетяжка&nbsp;мебели&nbsp;<span class="text-red-600">SS</span>
      </h1>
      <!-- Здесь могут быть контакты или меню -->
      <nav class="hidden md:flex space-x-4">
        <a href="#services" class="hover:text-blue-600">Услуги</a>
        <a href="#portfolio" class="hover:text-blue-600">Портфолио</a>
        <a href="#contact" class="hover:text-blue-600">Контакты</a>
      </nav>
    </div>
  </header>

  <!-- Hero section -->
  <section class="relative bg-cover bg-center h-96 text-white flex items-center" style="background-image: url('https://images.pexels.com/photos/3757055/pexels-photo-3757055.jpeg');">
    <div class="absolute inset-0 bg-black opacity-50"></div>
    <div class="relative container mx-auto text-center px-4">
      <h2 class="text-3xl sm:text-4xl md:text-5xl font-russo font-bold">Обновляем вашу мягкую мебель</h2>
      <p class="mt-4 text-lg sm:text-xl">Профессиональная перетяжка диванов, кресел и стульев</p>
      <button class="mt-6 px-6 py-3 bg-blue-600 hover:bg-blue-700 rounded-lg font-semibold">
        Заказать консультацию
      </button>
    </div>
  </section>

  <!-- Services -->
  <section id="services" class="py-12 bg-white">
    <div class="container mx-auto px-4">
      <h3 class="text-2xl font-semibold mb-6 text-center">Наши услуги</h3>
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-6">
        <!-- Card 1: Перетяжка диванов -->
        <div class="bg-gray-50 p-4 rounded-lg text-center">
          <img src="https://images.pexels.com/photos/5942737/pexels-photo-5942737.jpeg" alt="Диван" class="w-full h-40 object-cover rounded-md mb-4">
          <h4 class="font-semibold mb-2">Перетяжка диванов</h4>
          <p>Обновим обивку вашего дивана любой конфигурации.</p>
        </div>
        <!-- Card 2: Перетяжка кресел -->
        <div class="bg-gray-50 p-4 rounded-lg text-center">
          <img src="https://images.pexels.com/photos/2766975/pexels-photo-2766975.jpeg" alt="Кресла" class="w-full h-40 object-cover rounded-md mb-4">
          <h4 class="font-semibold mb-2">Перетяжка кресел</h4>
          <p>Беру кресла в любой стиль и сделаем их как новые.</p>
        </div>
        <!-- Card 3: Перетяжка стульев -->
        <div class="bg-gray-50 p-4 rounded-lg text-center">
          <img src="https://images.pexels.com/photos/7535046/pexels-photo-7535046.jpeg" alt="Стулья" class="w-full h-40 object-cover rounded-md mb-4">
          <h4 class="font-semibold mb-2">Перетяжка стульев</h4>
          <p>Меняем обивку кухонных и мягких стульев.</p>
        </div>
        <!-- Card 4: Реставрация мягкой мебели -->
        <div class="bg-gray-50 p-4 rounded-lg text-center">
          <img src="https://images.pexels.com/photos/3913574/pexels-photo-3913574.jpeg" alt="Реставрация" class="w-full h-40 object-cover rounded-md mb-4">
          <h4 class="font-semibold mb-2">Реставрация мебели</h4>
          <p>Восстанавливаем каркас и наполнитель, делаем мебель прочнее.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Advantages -->
  <section class="py-12 bg-gray-100">
    <div class="container mx-auto px-4">
      <h3 class="text-2xl font-semibold mb-6 text-center">Почему выбирают нас</h3>
      <ul class="list-disc list-inside space-y-2 max-w-lg mx-auto">
        <li>Большой опыт работы (на рынке с [год]).</li>
        <li>Профессиональные мастера с высоким качеством работы.</li>
        <li>Бесплатный выезд по Новосибирску для замеров.</li>
        <li>Гарантия на выполненные работы и используемые материалы.</li>
        <li>Широкий выбор тканей разных расцветок и фактур.</li>
      </ul>
    </div>
  </section>

  <!-- Portfolio -->
  <section id="portfolio" class="py-12 bg-white">
    <div class="container mx-auto px-4">
      <h3 class="text-2xl font-semibold mb-6 text-center">Наше портфолио</h3>
      <div class="space-y-8">
        <!-- Пример 1 -->
        <div class="flex flex-col md:flex-row items-center">
          <img src="https://images.pexels.com/photos/19847683/pexels-photo-19847683.jpeg" alt="До" class="w-full md:w-1/2 h-48 object-cover rounded-md">
          <img src="https://images.pexels.com/photos/5942737/pexels-photo-5942737.jpeg" alt="После" class="w-full md:w-1/2 h-48 object-cover rounded-md md:ml-4 mt-4 md:mt-0">
        </div>
        <p class="text-center italic">Пример 1: диван до (слева) и после (справа) перетяжки.</p>

        <!-- Пример 2 -->
        <div class="flex flex-col md:flex-row items-center">
          <img src="https://images.pexels.com/photos/17915329/pexels-photo-17915329.jpeg" alt="До" class="w-full md:w-1/2 h-48 object-cover rounded-md">
          <img src="https://images.pexels.com/photos/5703542/pexels-photo-5703542.jpeg" alt="После" class="w-full md:w-1/2 h-48 object-cover rounded-md md:ml-4 mt-4 md:mt-0">
        </div>
        <p class="text-center italic">Пример 2: кресло до (слева) и после (справа) реставрации.</p>

        <!-- Пример 3 -->
        <div class="flex flex-col md:flex-row items-center">
          <img src="https://images.pexels.com/photos/11064887/pexels-photo-11064887.jpeg" alt="До" class="w-full md:w-1/2 h-48 object-cover rounded-md">
          <img src="https://images.pexels.com/photos/3258303/pexels-photo-3258303.jpeg" alt="После" class="w-full md:w-1/2 h-48 object-cover rounded-md md:ml-4 mt-4 md:mt-0">
        </div>
        <p class="text-center italic">Пример 3: стул до (слева) и после (справа) перетяжки.</p>
      </div>
    </div>
  </section>

  <!-- Contact Form -->
  <section id="contact" class="py-12 bg-gray-100">
    <div class="container mx-auto px-4 max-w-md">
      <h3 class="text-2xl font-semibold mb-6 text-center">Оставьте заявку</h3>
      <form class="space-y-4">
        <div>
          <label class="block mb-1">Имя</label>
          <input type="text" class="w-full px-3 py-2 border rounded" placeholder="Ваше имя">
        </div>
        <div>
          <label class="block mb-1">Телефон</label>
          <input type="tel" class="w-full px-3 py-2 border rounded" placeholder="+7 () ___-_">
        </div>
        <div>
          <label class="block mb-1">Комментарий</label>
          <textarea class="w-full px-3 py-2 border rounded" rows="3" placeholder="Ваш комментарий"></textarea>
        </div>
        <button type="submit" class="w-full py-3 bg-blue-600 hover:bg-blue-700 text-white font-semibold rounded">
          Отправить
        </button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-white py-6">
    <div class="container mx-auto px-4 text-center text-gray-600">
      <p>Новосибирск, ул. Примерная, д. 10. Тел: <a href="tel:+73831234567" class="text-blue-600">+7 383 123‑45‑67</a></p>
      <p class="mt-2">Мы в соцсетях: 
        <a href="#" class="mx-1 text-blue-600">Facebook</a> 
        <a href="#" class="mx-1 text-blue-600">Instagram</a> 
        <a href="#" class="mx-1 text-blue-600">VK</a>
      </p>
    </div>
  </footer>

</body>
</html>
