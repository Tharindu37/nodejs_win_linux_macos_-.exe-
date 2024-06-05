```
npm i -g pkg
```
```
"pkg": {
    "scripts": "build/**/*.js",
    "assets": "views/**/*",
    "targets": [
      "node14-linux-arm64"
    ],
    "outputPath": "dist"
  }
```
```
pkg index.js --targets node18-win-x64
pkg index.js --targets node16-win-x64 --output express-app.exe
pkg server.js --targets node16-win-x64 --output dist\nodejs_exe.exe
```
