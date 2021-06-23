# WebsiteToDesktopApp
WebsiteToDesktopApp - Use to Electron :)


I made a javascript based sample application using Electron to make the website a desktop application in an easy way.



## Usage

 
```
PM> Main.js
```

```javascript
  const siteurl = 'https://localhost/'; 
```

```
PM> CreateApp.bat
```

{APPNAME} = This is Application Name

```csharp
  electron-packager . --platform=win32 --arch=x32 --ico=launcher.png {APPNAME} 
```

```
PM> package.json
```

You can edit the application information here according to your own

```json
  {
  "name": "WebToDesktop",
  "version": "1.0.0",
  "description": "Web Site To Desktop App",
  "main": "main.js",
  "scripts": {
    "start": "electron ."
  },
  "repository": "https://github.net",
  "keywords": [
    "enis",
    "website to desktop application"
  ],
  "author": "enisgurkan",
  "license": "CC0-1.0",
  "devDependencies": {
    "electron": "^10.1.3"
  },
  "dependencies": {
    "@exponent/electron-cookies": "^2.0.0",
    "electron-packager": "^15.2.0",
    "getmac": "^5.16.0"
  }
}

```


After editing, just run the "CreateApp.bat" file.
