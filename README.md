# Title
Angular primeNG with Electron integrated

## Steps to start

### download dependencies
```javascript
npm install
```

### compile angular project
```javascript
ng build --prod
```

### start electron app
```javascript
npm run electron:start
```

### compile electron app for linux (Ubuntu)
```javascript
npm run electron:linux
```

[You must install some dependencies](https://www.electronjs.org/docs/development/build-instructions-linux)

The project is prepared for compile on Windows, Mac or Linux. Check dependencies for each case
```javascript
npm run electron:mac
npm run electron:windows
```

### PoC Web from browser
![from_Brower](https://user-images.githubusercontent.com/1216181/99386156-4b823600-28d2-11eb-88bf-c3facb34296c.png)

### PoC Web from electron
![from_electron](https://user-images.githubusercontent.com/1216181/99386214-6785d780-28d2-11eb-9e57-2c7343e626f8.png)
