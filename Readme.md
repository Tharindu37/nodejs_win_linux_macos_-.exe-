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
```