# Visual Studio Code - reactjs

```
"features": {
  "python": "latest"
}
```

// Use 'postCreateCommand' to run commands after the container is created.
```
"postCreateCommand": "pip install pre-commit && pre-commit --version && pre-commit install",
```

```
// Set *default* container specific settings.json values on container create.
"settings": {
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.inlineSuggest.enabled": true,
  "github.copilot.enable": {
    "*": true,
    "yaml": false,
    "plaintext": false,
    "markdown": true
  }
},
```

```
// Add the IDs of extensions you want installed when the container is created.
"extensions": [
  "dbaeumer.vscode-eslint",
  "GitHub.copilotvs",
  "WakaTime.WakaTime",
  "esbenp.prettier-vscode",
  "bradlc.vscode-tailwindcss"
],
```
