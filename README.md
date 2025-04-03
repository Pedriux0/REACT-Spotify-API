# 🎵 Spotify Music Search App

A React Native app built with **Expo** that allows users to search for songs using the **Spotify API** and listen to track previews.

## 🚀 Features
- 🔍 Search for songs by title, artist, or keyword
- 🎧 Play **30-second** previews of songs (if available)
- 🎨 **Modern & stylish UI** with dark mode theme
- 🔄 Smooth **fade-in animation** for search results
- ✅ Uses **Spotify's client credentials** for authentication
- 📱 Built with **React Native & Expo Snack**

## 📦 Installation
### Prerequisites
Make sure you have the following installed:
- **Node.js** (Latest LTS recommended)
- **Expo CLI** (Install using `npm install -g expo-cli`)

### Clone the Repository
```sh
git clone https://github.com/your-username/spotify-music-search.git
cd spotify-music-search
```

### Install Dependencies
```sh
npm install
```

### Run the App
```sh
npx expo start
```
This will open Expo Developer Tools in your browser. You can run the app on an emulator or a physical device using the Expo Go app.

## 🔑 Spotify API Authentication
This app uses Spotify's **Client Credentials Flow**. To get your **Client ID** and **Client Secret**:
1. Go to the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/applications)
2. Create a new app
3. Copy your `CLIENT_ID` and `CLIENT_SECRET`
4. Replace the placeholder values in `App.js`:
   ```js
   const SPOTIFY_CLIENT_ID = 'your-client-id';
   const SPOTIFY_CLIENT_SECRET = 'your-client-secret';
   ```

## 🛠️ How It Works
1. Enter a song title or artist in the search bar
2. Tap **Search** to fetch results from Spotify
3. Browse through the list of tracks with album art
4. Tap **Play** to listen to a 30-second preview (if available)

## 🖌️ Screenshots
(Include images of the app here)

## 🤝 Contributing
Pull requests are welcome! If you’d like to contribute:
1. Fork the repo
2. Create a new branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Added new feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request

## 📜 License
This project is licensed under the **MIT License**.

## 🙌 Acknowledgments
- [Spotify API](https://developer.spotify.com/documentation/web-api/)
- [Expo](https://expo.dev/)
- [React Native](https://reactnative.dev/)

---
Made with ❤️ by Juan 

