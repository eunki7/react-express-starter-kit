# react-express-starter-kit
### (Node.js, Express, React.js, Babel, Webpack)

### Usage
**Clone this repository**
```
git clone https://github.com/eunki7/react-express-starter-kit.git
```

**When you use Windows**
```
Use package_windows.json Rename to package.json
```

**When you use osx(default)**
```
Use package_mac.json Rename to package.json
```

**Install**
```
npm install
```

**When ready, build for production**
```
npm run build
```

**Start the application**
```
npm run start
```

Open http://localhost:3000 in your browser.

**Start the application in development mode**
```
npm run development
```

Open http://localhost:3001 in your browser.(Debug Mode)

Static files are served from the `public` folder, project JavaScript files are bundled from the `app` folder.

**When ready, clean for production**
```
npm run clean
```

This will generate a minimized bundle.js file on the `public` folder.

### Dependencies

* React & React-DOM
* Express
* Webpack & webpack-dev-server
* Babel Core
* Babel Loader (With "es2015" and "react" presets)
* React-hot-loader
