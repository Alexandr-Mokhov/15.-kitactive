# ⚛️ Kit Storage - Личный кабинет файлового хранилища  

### Обзор  
🟣 Описание  
🟣 Инструкция  
🟣 Что было сделано  
🟣 План по доработке  
🟣 Стек и инструменты  
🟣 Ссылки  

### Описание  
Интерфейс для сервиса хранения файлов, с регистрацией и авторизацией.  
После регистрации и авторизации просиходит вход в личный кабинет.  
В личном кабинете можно загружать, просматривать, скачивать и удалять файлы.  
Если добавили картинку, то отображается привьюшка, если документ - то иконка документа.  

### Инструкция по запуску проекта  
- Установить Node.js если он еще не установлен, с официального сайта: https://nodejs.org/en/.  
- Установить NPM, если он еще не установлен. Для этого введите в командной строке: npm install -g npm.  
- Установить Git, если он еще не установлен, с официального сайта https://git-scm.com/.  
- Скачать репозиторий с этим проектом на свой компьютер, выполнив команду git clone https://github.com/Alexandr-Mokhov/test-kit.git.  
- Перейти в папку с проектом и открыть его в вашем любимом редакторе кода.  
- Установить зависимости проекта, выполнив команду npm install или npm ci.  
- Запустить проект, выполнив команду npm run start.  
- Проект должен запуститься и отобразиться в браузере, если этого не произошло - откройте браузер и введите в новой вкладке адрес http://localhost:3000/.  

### Что было сделано  
➤ приложение написано на React;  
➤ описана логика и вёрстка страниц регистрации, логина, личного кабинета;  
➤ авторизация, и манипуляции с файлами защищены токеном;  
➤ состояния хранятся в Redux;  
➤ реализованы асинхронные GET-, POST, DELETE-запросы к API;  
➤ изменяемое количество отображаемых файлов в зависимости от ширины экрана;  
➤ ограничение количества файлов которые пользователь может загрузить - 20 шт;  
➤ ограничение размера загружаемых данных за 1 запрос - 1 Mб;  
➤ в личном кабинете счетчик загруженных файлов;  
➤ выход из личного кабинета;  
➤ описана инструкция по использованию;  
➤ результат выложен на github и github-pages;  

### План по доработке  
➤ добавить роут 404 - Not Found;  
➤ проверка соответствия email и token на сервере;  
➤ сделать всплывающие кастомные модалки вместо алертов;  

### Стек и инструменты  

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original.svg" title="react" alt="react" width="40" height="40"/> 
  <img src="https://github.com/devicons/devicon/blob/master/icons/redux/redux-original.svg" title="redux" alt="redux" width="40" height="40"/> 
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="javascript" alt="javascript" width="40" height="40"/> 
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="html5" alt="html5" width="40" height="40"/> 
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-original.svg" title="css3" alt="css" width="40" height="40"/> 
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original.svg" title="git" alt="git" width="40" height="40"/> 
  <img src="https://github.com/devicons/devicon/blob/master/icons/github/github-original.svg" title="github" alt="github" width="40" height="40"/> 
  <img src="https://cdn.icon-icons.com/icons2/3053/PNG/512/postman_macos_bigsur_icon_189815.png" title="postman" alt="postman" width="40" height="40"/> 
</div>

### Ссылки  
🌎 [Ссылка на сайт](https://alexandr-mokhov.github.io/test-kit/)  

🌎 [Ссылка на задание](https://github.com/Ahitkin-kitactive/test-js)  

## Приятного просмотра!  

