# Laba5 Хранение данных. Настройки и внешние файлы.

Это приложение для Android, которое позволяет загружать файлы в формате PDF, просматривать их и удалять. Оно использует всплывающее окно для приветственного сообщения и поддерживает асинхронную загрузку файлов с сервера.

## Функции приложения

- **Загрузка файла:** Приложение позволяет пользователю ввести ID журнала и загрузить соответствующий PDF-файл с указанного URL.
- **Просмотр файла:** После успешной загрузки файла появляется кнопка для его просмотра в PDF-формате.
- **Удаление файла:** Пользователь может удалить загруженный файл.
- **Настройки:** В приложении есть настройка, которая позволяет пользователю отключить всплывающее окно с инструкцией на первый запуск.

## Основной функционал

1. **Всплывающее окно с инструкцией:** При первом запуске приложения отображается всплывающее окно с инструкцией, в котором есть возможность выбрать опцию "Больше не показывать".
2. **Загрузка файлов:** Приложение поддерживает асинхронную загрузку PDF-файлов по URL, полученному из ввода пользователя.
3. **Работа с файлами:** После загрузки файла появляется возможность его открытия и удаления.

## Структура проекта

- **MainActivity.java:** Основная активность приложения, которая управляет загрузкой, просмотром и удалением файлов.
- **popup_window.xml:** Макет для всплывающего окна с инструкцией.
- **activity_main.xml:** Главный макет приложения с кнопками и полями для ввода.

## Используемые технологии

- **Java:** Основной язык для разработки Android-приложений.
- **AsyncTask:** Используется для асинхронной загрузки файлов.
- **SharedPreferences:** Для сохранения настроек, таких как "показать всплывающее окно".
- **FileProvider:** Для безопасного доступа к файлам в Android.


