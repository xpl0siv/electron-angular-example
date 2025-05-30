# for use in npm scripts
npm install electron-packager --save-dev

# for use from cli
npm install electron-packager -g

### must be a string matching: ia32, x64, armv7l, arm64, mips64el, universal
npx electron-packager . example --platform=win32 --arch=x64
npx electron-packager . example --platform=win32 --arch=x86_64

# En el index.html del /dist del angular super importante:

```
  <base href="./">
```