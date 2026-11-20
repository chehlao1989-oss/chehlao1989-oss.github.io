# Корневой адрес сайта русской PoB 2

Корневой GitHub Pages для `chehlao1989-oss.github.io`. Перенаправляет посетителя на существующий сайт проекта: https://chehlao1989-oss.github.io/PathOfBuilding-PoE2-RU/ .

Google Search выбирает один favicon для хоста и читает сведения о нём на домашней странице хоста. Этот репозиторий делает корень доступным и публикует тот же значок RU в PNG/ICO. Основные тексты, скриншоты, аналитика, исходники программы и выпуски находятся в https://github.com/chehlao1989-oss/PathOfBuilding-PoE2-RU .

Публикация: GitHub Pages, корень ветки `main`, `.nojekyll`. Страница входа не загружает Google Analytics. Переход JavaScript сохраняет параметры и якорь, включая `?analytics=off`; HTML-переход и обычная ссылка работают без JavaScript. Для проверки никогда не скачивать ZIP и не создавать тестовую статистику.

Иконка: исходный золотой знак RU сайта. `favicon-96.png`, `favicon-192.png`, многоразмерный `favicon.ico`. При обновлении знака синхронизировать файлы с `docs/site-assets/` основного репозитория. URL значков сохранять стабильными.

Документация Google: https://developers.google.com/search/docs/appearance/favicon-in-search . Появление favicon в выдаче не гарантируется и проверяется отдельно после повторного обхода Google.
