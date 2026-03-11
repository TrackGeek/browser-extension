<p align="center">
  <img src="https://github.com/TrackGeek.png" height="100px">
</p>

<h1 align="center">
  <samp>Browser extension</samp>
</h1>

<h4 align="center">
  <samp>Browser extension for unified media tracking across the web.</samp>
</h4>

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-99e3a0?style=for-the-badge&logo=typescript&logoColor=004b38">
  <img src="https://img.shields.io/badge/PReact-99e3a0?style=for-the-badge&logo=preact&logoColor=004b38">
  <img src="https://img.shields.io/badge/Chrome-99e3a0?style=for-the-badge&logo=googlechrome&logoColor=004b38">
  <img src="https://img.shields.io/badge/Firefox-99e3a0?style=for-the-badge&logo=firefox&logoColor=004b38">
  <a href="https://translate.trackgeek.net"><img src="https://img.shields.io/badge/Crowdin-99e3a0?style=for-the-badge&logo=crowdin&logoColor=004b38"></a>
</p>

## <samp>Features</samp>

<samp>

- Quick access to your TrackGeek account from the browser;
- View and manage your lists (games, anime, movies, TV shows, books, manga);
- Add or remove items from your lists;
- Update progress and status of your tracked media;
- Search and add new content directly from the extension;
- Lightweight popup interface;
- Sync with your TrackGeek account;
- Browser support for Chrome and Firefox.

</samp>

## <samp>Tech Stack</samp>

<samp>

- TypeScript
- Preact
- Vite
- WebExtensions API (Manifest V3)
- TailwindCSS
- shadcn/ui
- Axios
- Chrome Extension API
- Firefox WebExtension API

</samp>

## <samp>Run Locally</samp>

<samp>

### Prerequisites

- Node.js 18+ and npm
- Chrome or Firefox browser

### Steps

1. Clone the project

```bash
git clone https://github.com/TrackGeek/browser-extension.git
```

2. Go to the project directory

```bash
cd browser-extension
```

3. Install dependencies

```bash
npm install
```

4. Build the extension

For Chrome:

```bash
npm run build:chrome
```

For Firefox:

```bash
npm run build:firefox
```

For development with hot reload:

```bash
npm run dev:chrome
# or
npm run dev:firefox
```

### Load in Chrome

1. Open Chrome and navigate to `chrome://extensions/`
2. Enable "Developer mode" (toggle in the top right)
3. Click "Load unpacked"
4. Select the `dist/chrome` folder from the project
5. The extension will appear in your browser toolbar

### Load in Firefox

1. Open Firefox and navigate to `about:debugging#/runtime/this-firefox`
2. Click "Load Temporary Add-on"
3. Navigate to the `dist/firefox` folder
4. Select the `manifest.json` file
5. The extension will appear in your browser toolbar

</samp>

## <samp>Contributing</samp>

<samp>

Contributions are always welcome!

See `CONTRIBUTING.md` for ways to get started.

Please adhere to this project's `code of conduct`.

</samp>

