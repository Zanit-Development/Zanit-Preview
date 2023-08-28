# Project Zanit 미리보기 배포용

### package.json
```json
"homepage": "https://zanit-development.github.io/Zanit-Preview/",
```

### app.tsx
```tsx
const PUB_URL = process.env.PUBLIC_URL;
<BrowserRouter basename={PUB_URL}>
  ...
</BrowserRouter>
```
