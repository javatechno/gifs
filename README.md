# Данные пользователя в каждом коммите

Мы реализовали сквозную передачу логина пользователя из Keycloak в Git. Теперь у каждого коммита в репозитории есть автор из Keycloak.

<img src="https://github.com/javatechno/gifs/blob/main/Keycloak%20%D0%B8%20Git%201.jpg"  width="800" height="400">

# Объединение разделов Сервисы и Контейнеры

Мы упростили просмотр информации по контейнерам и сервисам, запущенным в Roc Integration Toolkit. Теперь всё можно посмотреть в одном месте, всего лишь развернув блок информации по контейнеру.

<img src="https://github.com/javatechno/gifs/blob/main/%D0%98%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%80%D0%B0%D0%B7%D0%B4%D0%B5%D0%BB%D0%BE%D0%B2.gif"  width="800" height="400">
<img src="https://github.com/javatechno/gifs/blob/main/%D0%A2%D0%B8%D0%BF%20%D0%BA%D0%BE%D0%BD%D1%82%D0%B5%D0%B9%D0%BD%D0%B5%D1%80%D0%B0.gif"  width="800" height="400">
<img src="https://github.com/javatechno/gifs/blob/main/%D0%98%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D1%8F%20%D0%BE%20%D0%BA%D0%BE%D0%BD%D1%82%D0%B5%D0%B9%D0%BD%D0%B5%D1%80%D0%B5.gif" width="800" height="400">

# Визуализация описания ошибок при запуске контейнеров

Теперь вы сразу увидите причину, по которой не запускается контейнер, описанный в файле devservices — ошибка появится рядом с вашим контейнером в разделе "Контейнеры".
<img src="https://github.com/javatechno/gifs/blob/main/%D0%BE%D1%88%D0%B8%D0%B1%D0%BA%D0%B0%20%D0%BF%D1%80%D0%B8%20%D0%B7%D0%B0%D0%BF%D1%83%D1%81%D0%BA%D0%B5%20resized.gif"  width="800" height="400">

# Поиск по тексту в Базе знаний

Мы добавили возможность поиска элементов Базы знаний по тексту из описания. Теперь не обязательно знать название шаблона или камлета, вы можете искать шаблоны, камленты и компоненты по их текстовому описанию. Для этого просто введите нужный текст в строке поиска, и система отфильтрует подходящие элементы в режиме реального времени.
<img src="https://github.com/javatechno/gifs/blob/main/%D0%BF%D0%BE%D0%B8%D1%81%D0%BA%20%D0%B2%20%D0%B1%D0%B0%D0%B7%D0%B5%20%D0%B7%D0%BD%D0%B0%D0%BD%D0%B8%D0%B9%20resized.gif"  width="800" height="400">

# Сравнение и откат изменений файлов проекта

Иногда очень важно посмотреть, какие изменения внесены в файлы проекта перед коммитом в Git. Теперь это можно сделать в один клик — просто нажав на кнопку "ИЗМЕНЕН". А с помощью кнопки "Отмена изменений" можно вернуться до версии файла, которая последней была закоммичена в Git.
<img src="https://github.com/javatechno/gifs/blob/main/%D0%A1%D1%80%D0%B0%D0%B2%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B8%20%D0%BE%D1%82%D0%BC%D0%B5%D0%BD%D0%B0%20%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D0%B9.gif"  width="800" height="400">

# Выбор файлов для коммита в репозиторий

Часто при работе с проектом мы меняем не все его файлы. И для того, чтобы загрузка в репозиторий проходила быстрее, мы добавили чекбокс с выбором файлов для загрузки. Теперь вы можете загружать в репозиторий только измененные файлы.
<img src="https://github.com/javatechno/gifs/blob/main/%D0%B2%D1%8B%D0%B1%D0%BE%D1%80%20%D1%84%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2%20%D0%B4%D0%BB%D1%8F%20%D0%BA%D0%BE%D0%BC%D0%BC%D0%B8%D1%82%D0%B0%20resized.gif"  width="800" height="400">

# Генерация манифестов Kubernetes

В новой версии Roc Integration Toolkits мы добавили ещё один полезный инструмент — генерацию манифестов Kubernetes на основе docker-compose.yaml. Для этого всего лишь нужно нажать на кнопку "Создать манифест".
<img src="https://github.com/javatechno/gifs/blob/main/%D0%B3%D0%B5%D0%BD%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D1%8F%20%D0%BC%D0%B0%D0%BD%D0%B8%D1%84%D0%B5%D1%81%D1%82%D0%BE%D0%B2%20kubernetes%20resized.gif"  width="800" height="400">

# Осторожно, персональные данные!

Если ваша интеграция содержит информацию, которая потенциально должна быть закодирована, то Roc Integration Toolkit добавит значок и предупреждающее сообщение рядом с соответствующим файлом проекта.
<img src="https://github.com/javatechno/gifs/blob/main/%D0%A3%D0%B2%D0%B5%D0%B4%D0%BE%D0%BC%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BE%20%D1%81%D0%B5%D0%BA%D1%80%D0%B5%D1%82%D0%B0%D1%85.gif"  width="800" height="400">

# Теперь у нас есть env

В версии 1.0.1 появилась возможность создавать свои env переменные в файлах проекта и использовать их в product-ready образах.
<img src="https://github.com/javatechno/gifs/blob/main/env%20%D0%BF%D0%B5%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%BD%D1%8B%D0%B5%20resized.gif"  width="800" height="400">

# Новый поиск элементов маршрута

Мы придумали более удобную форму для поиска элементов маршрута и хотим поделиться этим с вами. Открывается форма всё так же — при нажатии на "+" в маршруте.
<img src="https://github.com/javatechno/gifs/blob/main/%D0%BF%D0%BE%D0%B8%D1%81%D0%BA%20%D1%8D%D0%BB%D0%B5%D0%BC%D0%B5%D0%BD%D1%82%D0%BE%D0%B2%20resized.gif"  width="800" height="400">

# Изменение начального элемента интеграции

Теперь можно поменять начальный элемент интеграции и при этом не выстраивать маршрут с нуля.
<img src="https://github.com/javatechno/gifs/blob/main/%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BD%D0%B0%D1%87%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D0%B3%D0%BE%20%D1%8D%D0%BB%D0%B5%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%20%D0%B8%D0%BD%D1%82%D0%B5%D0%B3%D1%80%D0%B0%D1%86%D0%B8%D0%B8%20resized.gif"  width="800" height="400">

# OpenAPI 3.0 / Swagger 2

Мы добавили возможность генерации Rest эндпоинтов по OpenAPI 3.0 / Swagger 2 спецификации. Импортируйте подготовленные файлы в свой интеграционный проект в один клик.
<img src="https://github.com/javatechno/gifs/blob/main/API%203.0%20resized.gif"  width="800" height="400">

# Конвертация между элементами

В новой версии Roc Integration Toolkit можно конвертировать элемент SetHeader в SetHeaders и наоборот, а также конвертировать друг в друга SetVariable и SetVariables. Самое важное, что менять маршрут интеграции при этом не придется.

<img src="https://github.com/javatechno/gifs/blob/main/SetVariable%20%D0%B8%20SetVariables.gif"  width="800" height="400">
<img src="https://github.com/javatechno/gifs/blob/main/setheaders%20resized.gif.jpg"  width="800" height="400">

# Готовые бины для EIP Aggregator и Idempotent Consumer

Добавлена возможность выбирать бины из пакета Camel SPI для элементов маршрута EIP Aggregator и Idempotent Consumer.

<img src="https://github.com/javatechno/gifs/blob/main/%D0%B2%D1%8B%D0%B1%D0%BE%D1%80%20%D0%B1%D0%B8%D0%BD%D0%BE%D0%B2%20%D0%B4%D0%BB%D1%8F%20Aggregate%20resized.gif"  width="800" height="400">
<img src="https://github.com/javatechno/gifs/blob/main/%D0%B2%D1%8B%D0%B1%D0%BE%D1%80%20%D0%B1%D0%B8%D0%BD%D0%BE%D0%B2%20idempotent%20consumer%20resized.gif"  width="800" height="400">
