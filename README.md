# GIF Comments — GitHub Pages

Готовый статический сайт расширения: главная страница, политика конфиденциальности и контакт поддержки **melroncode@bk.ru**. Без сборки, npm, JavaScript, внешних шрифтов и аналитики.

## Размещение в IT-Shelter-Labs

1. Войдите в GitHub под аккаунтом, которому доступно создание репозиториев в организации IT-Shelter-Labs. Откройте https://github.com/new.
2. В поле **Owner** выберите **IT-Shelter-Labs**.
3. Название репозитория: **gif-comments-site**. Выберите **Public**. Если репозиторий с таким именем уже есть, откройте его; не перезаписывайте существующие файлы без проверки. Если используете другое имя, изменится адрес сайта.
4. Нажмите **Create repository**.
5. В пустом репозитории нажмите **uploading an existing file**. Если файлы уже есть: **Add file → Upload files**.
6. Распакуйте полученный ZIP на компьютере и загрузите в **корень репозитория** файлы index.html, privacy.html, style.css, icon.svg, PRIVACY.md и README.md. Добавьте также .nojekyll. Сам ZIP и папку-обёртку загружать не нужно.
7. Введите сообщение **Add GIF Comments website** и нажмите **Commit changes**. Для нового репозитория используйте ветку **main**.
8. Откройте **Settings → Pages**. В **Build and deployment → Source** выберите **Deploy from a branch**. В **Branch** выберите **main**, папку **/(root)**, нажмите **Save**.
9. Дождитесь успешного выполнения **pages build and deployment** во вкладке **Actions**. В **Settings → Pages** откройте **Visit site**. Появление сайта может занять несколько минут.

Если .nojekyll не виден в распакованной папке, создайте его через **Add file → Create new file**. Имя файла — `.nojekyll`, содержимое — `Static site: no Jekyll build required`. Сохраните в main. Для обычных HTML-файлов он не обязателен, но явно отключает обработку Jekyll.

Для бесплатного GitHub Pages на GitHub Free репозиторий должен быть публичным. Права admin или maintainer позволяют настроить источник Pages. Если Owner или Settings недоступны, потребуется доступ от владельца организации.

## Адреса для каталогов

При размещении в **IT-Shelter-Labs/gif-comments-site** без отдельного домена ожидаются:

- Главная / Website / Support URL: **https://it-shelter-labs.github.io/gif-comments-site/**
- Privacy Policy URL: **https://it-shelter-labs.github.io/gif-comments-site/privacy.html**
- Support email: **melroncode@bk.ru**

Эти адреса — ожидаемые после публикации, а не подтверждение уже работающего сайта. Используйте адрес, который фактически покажет Settings → Pages; настройки домена организации могут его изменить. Перед вставкой в Firefox/Edge откройте обе страницы в приватном окне без входа в GitHub.

## Проверка после публикации

- Главная открывается, иконка и оформление видны.
- Ссылка **Privacy / Конфиденциальность** ведёт на страницу политики.
- На странице политики есть русский и английский текст и правильная почта поддержки.
- Сайт доступен без входа в аккаунт; политика открывается по HTTPS.

Если появилась 404: проверьте успешный запуск Actions, имя репозитория, ветку main и положение index.html в корне. Если нет оформления: style.css и icon.svg должны лежать рядом с index.html. Обновите страницу после завершения публикации.

## Обновления

Заменяйте нужные файлы через Add file → Upload files и сохраняйте изменения в main. GitHub Pages обновит сайт автоматически. Когда появятся действующие страницы расширения в каталогах, можно добавить их ссылки в index.html. Пока ссылки на каталоги не придуманы.

На странице нет личной подписи; репозиторий и адрес сайта будут публично связаны с организацией IT-Shelter-Labs. Контакт поддержки опубликован по указанию владельца проекта.

## Состав

- index.html — главная страница.
- privacy.html — политика конфиденциальности.
- style.css — общие стили.
- icon.svg — нейтральная иконка.
- PRIVACY.md — та же политика в текстовом формате.
- .nojekyll — отключение Jekyll.
- README.md — этот гайд.

Репозиторий и публикация не создавались этой подготовкой.

Основа инструкции: [настройка источника GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site), [создание сайта](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site). Проверено 14 октября 2026.
