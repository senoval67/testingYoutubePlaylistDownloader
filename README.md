<h1 align="center">Тестирование</h1>

<p align="center">
  <b>Проект:</b> <a href="https://github.com/shaked6540/YoutubePlaylistDownloader">YoutubePlaylistDownloader</a><br>
  <b>Версия:</b> <code>1.9.34</code><br>
  <b>Дата тестирования:</b> <i>20.09.2026</i>
</p>

---

##  О тестировании

> Проведено **ручное тестирование** ключевых функций приложения.
> Основная цель — убедиться, что **меню**, **настройки**, **скачивание видео и музыки**и **фильтры** работают так, как ожидается.

<details>
<summary><b>полный список проверенных областей</b></summary>

<br>

|  Область | Что проверялось |
|:--|:--|
| **Меню** | «О программе», «Помощь», «Настройки», способы загрузки, подтверждение выхода |
| **Настройки** | Тёмная тема, автообновление, сохранение предпочтений, подтверждение выхода, смена цвета, смена языка |
| **Скачивание видео** | Выбор папки, открытие папки после загрузки, пропуск существующих файлов, формат имени, расширение, разрешение, субтитры |
| **Скачивание музыки** | Конвертация в `mp3`, загрузка без тегов, загрузка только аудио |
| **Плейлисты** | Загрузка плейлиста с настройкой «Загрузить с видео номер» |
| **Фильтры** | Фильтр по длительности видео |
| **Виды скачивания** | Поиск, Очередь, Массовая загрузка |

</details>

---

##  Скриншоты

### Главное окно и меню

<p align="center">
  <img src="https://raw.githubusercontent.com/senoval67/myimages/main/images/YouTubeSETMenu.jpg" width="700" alt="Главное окно"><br>
  <i>Главное окно приложения</i>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/senoval67/myimages/main/images/YouTubeSETOPR.jpg" width="700" alt="О программе">
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

###  Скачивание музыки

<p align="center">
  <img src="https://raw.githubusercontent.com/senoval67/myimages/main/images/YouTubeSETMUSIC.jpg" width="700" alt="Предпросмотр видео"><br>
  <i>Предпросмотр видео перед скачиванием</i>
</p>

---

##  Найденные баги

> [!WARNING]
> **BUG-MF-01** — Краш приложения при **быстром многократном** нажатии на кнопку *«Проверить наличие обновлений»*.
>
> - **Тип:** плавающий (*~1 из 50 попыток*)
> - **Серьёзность:** низкая
> - **Связанный тест-кейс:** `MF-01`
> - **Рекомендация:** добавить задержку (~1 сек) на кнопку, чтобы успевало появиться всплывающее окно.

---

## 📌 Итог

<p align="center">
  <b>✅ Большинство сценариев — <u>пройдено успешно</u>.</b><br>
  ⚠️ Найден <b>один плавающий баг</b> низкой серьёзности.<br>
  🚫 Часть тестов <i>заблокирована</i> из-за отсутствия новых версий на момент проверки.
</p>

---

<p align="center">
  <i>Тестирование выполнено вручную. Скриншоты добавлены как визуальные доказательства работы приложения.</i>
</p>
