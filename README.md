<!-- index.html -->
<!--
  Цей файл містить повний код простого адаптивного веб-сайту.
  Він розроблений з використанням Tailwind CSS для стилізації.
  Увесь контент, включаючи текст, зображення та посилання, можна легко змінити.
-->
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мій Перший Сайт</title>
    <!-- Підключення Tailwind CSS через CDN для швидкого старту -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Використання шрифту Inter для всього тексту */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6; /* Легкий сірий фон */
        }
    </style>
</head>
<body class="flex flex-col min-h-screen">

    <!-- Секція заголовка (Header) -->
    <header class="bg-indigo-600 text-white p-4 shadow-md">
        <div class="container mx-auto flex justify-between items-center">
            <!-- Назва сайту -->
            <h1 class="text-xl sm:text-2xl font-bold">Мій Сайт</h1>
            <!-- Навігаційне меню (приховано на мобільних, але можна розгорнути) -->
            <nav class="hidden md:block">
                <ul class="flex space-x-4">
                    <li><a href="#" class="hover:text-indigo-200 transition-colors duration-300">Головна</a></li>
                    <li><a href="#" class="hover:text-indigo-200 transition-colors duration-300">Про нас</a></li>
                    <li><a href="#" class="hover:text-indigo-200 transition-colors duration-300">Контакти</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Основний контент (Main Content) -->
    <main class="container mx-auto p-6 flex-grow">
        <section class="bg-white rounded-xl shadow-lg p-6 sm:p-8 mb-6">
            <!-- Заголовок розділу -->
            <h2 class="text-2xl sm:text-3xl font-bold text-gray-800 mb-4">Ласкаво просимо!</h2>
            <!-- Параграф тексту -->
            <p class="text-gray-600 mb-6 leading-relaxed">
                Цей сайт є чудовим початком для твого веб-проєкту. Ти можеш легко налаштувати його, змінивши текст, додавши нові розділи та вставивши власні зображення.
            </p>
            <!-- Блок з зображенням та додатковим текстом -->
            <div class="flex flex-col md:flex-row items-center space-y-4 md:space-y-0 md:space-x-8">
                <!-- Зображення-заглушка з плашкою та текстом -->
                <img src="https://placehold.co/600x400/2563eb/ffffff?text=Привіт!" alt="Зображення-заглушка" class="w-full md:w-1/2 rounded-xl shadow-md">
                <div class="text-gray-700 w-full md:w-1/2">
                    <h3 class="text-xl font-semibold mb-2">Наш Проєкт</h3>
                    <p>
                        Ми віримо, що створення сайтів має бути простим і доступним для кожного. Цей шаблон надає тобі надійну основу для твоїх ідей.
                    </p>
                </div>
            </div>
        </section>

        <section class="bg-white rounded-xl shadow-lg p-6 sm:p-8">
            <h2 class="text-2xl sm:text-3xl font-bold text-gray-800 mb-4">Наші послуги</h2>
            <!-- Список послуг у вигляді сітки -->
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Картка послуги 1 -->
                <div class="bg-gray-100 p-4 rounded-lg">
                    <h3 class="text-lg font-semibold mb-2 text-indigo-700">Веб-дизайн</h3>
                    <p class="text-sm text-gray-600">
                        Створення візуально привабливих та зручних для користувача інтерфейсів.
                    </p>
                </div>
                <!-- Картка послуги 2 -->
                <div class="bg-gray-100 p-4 rounded-lg">
                    <h3 class="text-lg font-semibold mb-2 text-indigo-700">Розробка</h3>
                    <p class="text-sm text-gray-600">
                        Написання якісного та чистого коду для твоїх проєктів.
                    </p>
                </div>
                <!-- Картка послуги 3 -->
                <div class="bg-gray-100 p-4 rounded-lg">
                    <h3 class="text-lg font-semibold mb-2 text-indigo-700">Підтримка</h3>
                    <p class="text-sm text-gray-600">
                        Постійна підтримка та оновлення твого сайту.
                    </p>
                </div>
            </div>
        </section>
    </main>

    <!-- Підвал (Footer) -->
    <footer class="bg-gray-800 text-gray-400 p-4 mt-6">
        <div class="container mx-auto text-center text-sm">
            <p>&copy; 2023 Мій Сайт. Усі права захищені.</p>
        </div>
    </footer>

</body>
</html>

