<h1>MMCS Schedule App Landing Page</h1>
<p>
  Based on <a href="https://github.com/sandoche/Mobile-app-landingpage-template" target="_blank">template</a>
  <a href="/LICENSE"><img src="https://img.shields.io/github/license/mashape/apistatus.svg" alt="MIT"></a>
</p>

## 📖 How to use

1. Fork this project
2. Edit `_config.yml`, feel free to commut/uncomment what you need (google analtytics, or github for example)
3. Edit `_data/app.yml` with your app data
4. Update the text from `_data/strings.yml`, you can customize there the footer's links
5. Edit icons and screenshots inside the `_images` folder and `icon.png` in the root
6. Edit `_src/index.js` to update the product hunt modal (or to remove it) and to remove the darkmode plugin if you don't want it
7. Deploy (on netlify, gitpages or surge, they are all free)

## ⚙️ How to run

### Pre-requisites
- NodeJS
- Ruby, Bundler

### Install
```
npm install
bundler install
```

### Development
```
npm start
```

### Build
```
npm run build
```
