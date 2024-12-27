- pnpm i
- pnpm add -D @tauri-apps/cli@latest -w
- pnpm tauri init

```
  "build": {
    "frontendDist": "../dist/editor",
    "devUrl": "http://localhost:8080",
    "beforeDevCommand": "pnpm run start:editor",
    "beforeBuildCommand": "pnpm run build:editor"
  },
```

- pnpm tauri dev
