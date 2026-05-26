# DaviGa Theme

Tema escuro para VS Code baseado em tons de dourado, âmbar e cinza.

## Instalação

```bash
npx vsce package --allow-missing-repository
code --install-extension daviga-theme-0.0.1.vsix
```

Depois: **Ctrl+Shift+P** → `Preferences: Color Theme` → **Gold Standard Dark**

## Atualizar após editar o tema

Sempre que editar `themes/daviga-theme.json`, rode os dois comandos acima novamente para reinstalar com as mudanças.

## Paleta de cores

| Cor        | Hex       | Uso                              |
|------------|-----------|----------------------------------|
| Dourado    | `#d1ad54` | Funções, classes, operadores     |
| Âmbar      | `#ebcb8b` | Strings, escapes, avisos         |
| Roxo       | `#b48ead` | Constantes em maiúsculo          |
| Cinza      | `#989898` | Keywords, comentários, pontuação |
| Vermelho   | `#bf616a` | Erros                            |
| Azul       | `#5e81ac` | Preprocessor, meta               |
| Branco     | `#f8f8f8` | Texto padrão, variáveis          |
| Fundo      | `#222222` | Background do editor             |
