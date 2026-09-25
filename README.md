<h1 align="center">Тестирование</h1>

<p align="center">
  <b>Проект:</b> <a href="https://github.com/shaked6540/YoutubePlaylistDownloader">YoutubePlaylistDownloader</a><br>
  <b>Версия:</b> <code>1.9.34</code><br>
  <b>Дата тестирования:</b> <i>20.09.2026</i>
</p>

## О тестировании

> Проведено **ручное тестирование** ключевых функций приложения.
> Основная цель — убедиться, что **меню**, **настройки**, **скачивание видео и музыки** и **фильтры** работают так, как ожидается.

<details>
<summary><b>Полный список проверенных областей</b></summary>

<br>

<table>
  <thead>
    <tr>
      <th align="left">Область</th>
      <th align="left">Что проверялось</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Меню</b></td>
      <td>«О программе», «Помощь», «Настройки», способы загрузки, подтверждение выхода</td>
    </tr>
    <tr>
      <td><b>Настройки</b></td>
      <td>Тёмная тема, автообновление, сохранение предпочтений, подтверждение выхода, смена цвета, смена языка</td>
    </tr>
    <tr>
      <td><b>Скачивание видео</b></td>
      <td>Выбор папки, открытие папки после загрузки, пропуск существующих файлов, формат имени, расширение, разрешение, субтитры</td>
    </tr>
    <tr>
      <td><b>Скачивание музыки</b></td>
      <td>Конвертация в <code>mp3</code>, загрузка без тегов, загрузка только аудио</td>
    </tr>
    <tr>
      <td><b>Плейлисты</b></td>
      <td>Загрузка плейлиста с настройкой «Загрузить с видео номер»</td>
    </tr>
    <tr>
      <td><b>Фильтры</b></td>
      <td>Фильтр по длительности видео</td>
    </tr>
    <tr>
      <td><b>Виды скачивания</b></td>
      <td>Поиск, Очередь, Массовая загрузка</td>
    </tr>
  </tbody>
</table>

</details>

## Скриншоты

### Главное окно и меню

<p align="center">
  <img src="https://raw.githubusercontent.com/senoval67/myimages/main/images/YouTubeSETMenu.jpg" width="700" alt="Главное окно"><br>
  <i>Главное окно приложения</i>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/senoval67/myimages/main/images/YouTubeSETOPR.jpg" width="700" alt="О программе"><br>
  <img src="https://raw.githubusercontent.com/senoval67/myimages/main/images/YouTubeSETSV.jpg" width="700" alt="Помощь"><br>
  <i>Сверху — «О программе», Снизу — «Помощь»</i>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/senoval67/myimages/main/images/YouTubeSETSETI.jpg" width="700" alt="Настройки"><br>
  <i>Раздел «Настройки»</i>
</p>

### Скачивание видео

<p align="center">
  <img src="https://raw.githubusercontent.com/senoval67/myimages/main/images/YouTubeSETVOLDER.jpg" width="700" alt="Опции"><br>
  <i>Раздел «Опции» — выбор папки и параметров</i>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/senoval67/myimages/main/images/YouTubeSETZAGRYSKA.jpg" width="700" alt="Процесс скачивания"><br>
  <i>Процесс скачивания видео</i>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/senoval67/myimages/main/images/YouTubeSETGOTOVO.jpg" width="700" alt="Готово"><br>
  <i>Загрузка завершена — «Готово»</i>
</p>

### Скачивание музыки

<p align="center">
  <img src="https://raw.githubusercontent.com/senoval67/myimages/main/images/YouTubeSETMUSIC.jpg" width="700" alt="Предпросмотр видео"><br>
  <i>Предпросмотр видео перед скачиванием</i>
</p>

<h2>Пример тест-кейса</h2>

<p>Ниже приведён один из тест-кейсов для демонстрации формата. Полный набор тест-кейсов и баг-репортов доступен в Word-документе <code>testingYoutubePlaylistDownloader.docx</code>.</p>

<table>
  <thead>
    <tr>
      <th align="left" width="180">Поле</th>
      <th align="left">Значения</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>ID</b></td>
      <td><code>MF-01</code></td>
    </tr>
    <tr>
      <td><b>Название</b></td>
      <td>Кнопка «О программе» и проверка обновлений</td>
    </tr>
    <tr>
      <td><b>Предусловия</b></td>
      <td>Приложение установлено. Приложение запущено.</td>
    </tr>
    <tr>
      <td><b>Шаги</b></td>
      <td>
        1. Нажать на кнопку «О программе».<br>
        2. В открывшемся описании «О программе» нажать на кнопку «Проверить наличие обновлений».<br>
        3. Во всплывающем сообщении нажать кнопку «Ок».<br>
        4. В открывшемся описании «О программе» нажать кнопку «Домой».
      </td>
    </tr>
    <tr>
      <td><b>Ожидаемый результат</b></td>
      <td>
        При нажатии кнопки «О программе» открывается окно с описанием программы.<br>
        При нажатии на кнопку «Проверить наличие обновлений» всплывает сообщение о том, что обновлений не найдено.<br>
        При нажатии кнопки «Домой» открывается главное меню.
      </td>
    </tr>
    <tr>
      <td><b>Фактический результат</b></td>
      <td>
        При нажатии кнопки «О программе» открывается окно с описанием программы.<br>
        При нажатии на кнопку «Проверить наличие обновлений» всплывает сообщение о том, что обновлений не найдено.<br>
        При нажатии кнопки «Домой» открывается главное меню.
      </td>
    </tr>
    <tr>
      <td><b>Статус</b></td>
      <td><b>Пройден</b></td>
    </tr>
  </tbody>
</table>

## Найденные баги

> [!WARNING]
> **BUG-MF-01** — Краш приложения при **быстром многократном** нажатии на кнопку *«Проверить наличие обновлений»*.
>
> - **Тип:** плавающий (*~1 из 50 попыток*)
> - **Серьёзность:** низкая
> - **Связанный тест-кейс:** `MF-01`
> - **Рекомендация:** добавить задержку (~1 сек) на кнопку, чтобы успевало появиться всплывающее окно.

