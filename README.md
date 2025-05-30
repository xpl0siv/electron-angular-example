### En el index.html del /dist del angular super importante:

```
  <base href="./">
```

### must be a string matching: ia32, x64, armv7l, arm64, mips64el, universal
```
npx electron-packager . example --platform=win32 --arch=x64
npx electron-packager . example --platform=win32 --arch=x86_64
```
- Genera el .exe