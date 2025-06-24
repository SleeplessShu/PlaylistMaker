# 🎵 PlaylistMaker

**PlaylistMaker** - Android-приложение для создания и прослушивания музыкальных плейлистов. Пользователи могут искать треки, добавлять их в плейлисты, слушать музыку и настраивать внешний вид приложения.

---

## 📱 Скриншоты
<table>
  <tr>
    <td align="center" valign="top">
      <img src="https://github.com/user-attachments/assets/5e03d1a0-cc1c-48c7-b295-caa5f18a6dbf" style="max-height:300px; height:auto; width:auto;"/><br/>
      <sub>Главный экран / Избранные треки</sub>
    </td>
    <td align="center" valign="top">
      <img src="https://github.com/user-attachments/assets/0712599d-cc05-45be-9774-f2c9013de6a1" style="max-height:300px; height:auto; width:auto;"/><br/>
      <sub>Поиск</sub>
    </td>
    <td align="center" valign="top">
      <img src="https://github.com/user-attachments/assets/4fd8fb86-1f16-4a16-be55-27f335a32b7f" style="max-height:300px; height:auto; width:auto;"/><br/>
      <sub>Плеер</sub>
    </td>
    <td align="center" valign="top">
      <img src="https://github.com/user-attachments/assets/9da95d1b-af36-4e5d-8646-60118adc9de2" style="max-height:300px; height:auto; width:auto;"/><br/>
      <sub>Плейлисты</sub>
    </td>
    <td align="center" valign="top">
      <img src="https://github.com/user-attachments/assets/8844bcae-887f-4fb1-abd5-eeb08f73c67e" style="max-height:300px; height:auto; width:auto;"/><br/>
      <sub>Редактор плейлиста</sub>
    </td>
  </tr>
</table>

---

## 🔧 Функции

- 🔍 Поиск треков (через iTunes API)
- 🎧 Воспроизведение музыки
- 📝 Создание и редактирование плейлистов
- 🌙 Поддержка тёмной темы
- ⚙️ Настройки и очистка истории поиска

---

### 🛠️ Стек технологий

- **Язык программирования:** Kotlin
- **Архитектура:** MVVM + Clean Architecture
- **DI (внедрение зависимостей):** Koin
- **Асинхронность:** Kotlin Coroutines, Flow
- **Хранение данных:**
  - Room (для плейлистов и треков)
  - SharedPreferences (для настроек и истории поиска)
- **Сетевое взаимодействие:** Retrofit (подключение к iTunes API)
- **UI-компоненты:** RecyclerView, Fragment, BottomSheetDialog, Material Components
- **Мультимедиа:** MediaPlayer API (воспроизведение аудио)
- **Темы:** Поддержка светлой и тёмной темы
- **Тестирование:** JUnit (юнит-тесты бизнес-логики)
- **Слои:** Data / Domain / UI (по Clean Architecture)

---

## 🗂️ Структура модулей

- `search` - поиск треков
- `player` - экран плеера
- `mediateka` - избранное и сохранённые плейлисты
- `playlist` - экран плейлиста
- `playlist_editor` - создание и редактирование плейлистов
- `settings` - настройки, переключение темы

---

## 🚀 Запуск проекта

1. Склонируй репозиторий:
   ```bash
   git clone https://github.com/SleeplessShu/PlaylistMaker.git

2. Открой проект в Android Studio

3. Запусти на эмуляторе или устройстве (minSdk = 21)


