## 의존성 설치

```bash
npm install -D @styled/typescript-styled-plugin
```

## tsconfig.json

```json

{
  "compilerOptions": {
    "plugins": [
      {
        "name": "@styled/typescript-styled-plugin",
        "lint": {
          "validProperties": [
            "label"
          ]
        }
      }
    ],
    ..

  }
}
```

## TS서버 재시작

```
F1 > Typescript: Restart TS Server
```
