# Project Zanit 미리보기 배포용

### modules
```
npm install gh-pages --save-dev
```

### package.json
```json
"script": {
  ...
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}

"homepage": "https://zanit-development.github.io/Zanit-Preview/",
```

### app.tsx
```tsx
const PUB_URL = process.env.PUBLIC_URL;

...

<BrowserRouter basename={PUB_URL}>
  ...
</BrowserRouter>
```
