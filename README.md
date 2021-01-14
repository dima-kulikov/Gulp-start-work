<h1 class="text-center">Gulp </h1>
<h2 class="text-center">Стартовая сборка для верстки</h2>

<p>1.Для работы открываем консоль и даем команду:</p>
<p> <strong>"npm i"</strong> (установка всех пакето в впроэкт)</p>
<p>2.запуск галпа командой:</p>
<p><strong>"gulp"</strong></p>

<p>Под капотом Gulp имеет:</p>
<ul>
  <li>открытие страницы в браузере с html</li>
  <li>групировка html в один файл, через @@include путь к html, который
    нужно вставить</li>
  <li>при ctrl+s сохранение данных и автоперезагрузка страницы</li>
  <li>scss</li>
  <li>обработка и перевод scss в стандартный css</li>
  <li>автопрефиксер</li>
  <li>групировка медиазапросов(находит все медиазапросы и групирует внизу
    css)</li>
  <li>"cleancss" сжимает css и создает файл min.css(в конечно йпапке css
    файл и min.css)</li>
  <li>сборка js файлов в один</li>
  <li>создание обычного js файла и min.js</li>
  <li>оптимизация изображений (уменьшает размер изображения на 40-50%)</li>
  <li>создания (конвертирование) формата изображения WEBp</li>
  <li>webp html сразу в html подключает данный формат изображений</li>
  <li>webp в css, все изображения которые в css, ставит формат webp
    (неработает, нужнапроверка!)</li>
  <li>есть файл normalize, (подводит под один стандарт css настройки разных браузеров.) </li>
</ul>