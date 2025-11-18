<h1>
  <img src="https://github.com/user-attachments/assets/9c3a5059-988d-41aa-b9f2-ba2f34ec7f75" height="28"/>
  PlaylistMaker
</h1>

**PlaylistMaker** - An Android application for creating and listening to music playlists. Users can search for tracks, add them to playlists, listen to music, and customize the appearance of the app.

---

## 📱 Screenshots
<table>
  <tr>
    <td align="center" valign="top">
      <img src="https://github.com/user-attachments/assets/5e03d1a0-cc1c-48c7-b295-caa5f18a6dbf" style="height:300px; object-fit:contain;"/><br/>
      <sub>Главный экран / Избранные треки</sub>
    </td>
    <td align="center" valign="top">
      <img src="https://github.com/user-attachments/assets/0712599d-cc05-45be-9774-f2c9013de6a1" style="height:300px; object-fit:contain;"/><br/>
      <sub>Поиск</sub>
    </td>
    <td align="center" valign="top">
      <img src="https://github.com/user-attachments/assets/4fd8fb86-1f16-4a16-be55-27f335a32b7f" style="height:300px; object-fit:contain;"/><br/>
      <sub>Плеер</sub>
    </td>
    <td align="center" valign="top">
      <img src="https://github.com/user-attachments/assets/9da95d1b-af36-4e5d-8646-60118adc9de2" style="height:300px; object-fit:contain;"/><br/>
      <sub>Плейлисты</sub>
    </td>
    <td align="center" valign="top">
      <img src="https://github.com/user-attachments/assets/8844bcae-887f-4fb1-abd5-eeb08f73c67e" style="height:300px; object-fit:contain;"/><br/>
      <sub>Редактор плейлиста</sub>
    </td>
  </tr>
</table>

---

## 🔧 Functions

- 🔍 Track search (via the iTunes API)
- 🎧 Music playback
- 📝 Playlist creation and editing
- 🌙 Dark theme support
- ⚙️ Settings and search history management

---

### 🛠️ Tech Stack

Programming language: Kotlin
Architecture: MVVM + Clean Architecture
Dependency Injection: Koin
Asynchronous tools: Kotlin Coroutines, Flow
Data storage:
Room (for playlists and tracks)
SharedPreferences (for settings and search history)
Networking: Retrofit (iTunes API integration)
UI components: RecyclerView, Fragment, BottomSheetDialog, Material Components
Multimedia: MediaPlayer API (audio playback)
Themes: Light & Dark theme support
Testing: JUnit (unit tests for business logic)
Project structure: Data / Domain / UI (Clean Architecture layered approach)

---

## 🗂️ Module structure

- `search` - track search
- `player` - music player screen
- `mediateka` - favorites and saved playlists
- `playlist` - playlist screen
- `playlist_editor` - creating and editing playlists
- `settings` - app settings and theme switching

---

## 🚀 Running the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/SleeplessShu/PlaylistMaker.git

2. Open the project in Android Studio.

3. Run the app on an emulator or a physical device (minSdk = 21).


