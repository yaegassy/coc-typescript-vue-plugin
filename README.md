# coc-typescript-vue-plugin

TypeScript Vue Plugin (Volar) for [coc.nvim](https://github.com/neoclide/coc.nvim)

> A [TS server plugin](https://github.com/microsoft/TypeScript/wiki/Writing-a-Language-Service-Plugin) to make TS server know `*.vue` files

## Note

This extension enable the [typescript-vue-plugin](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) on the `tsserver` launched by [coc-tsserver](https://github.com/neoclide/coc-tsserver). coc-tsserver respects the `contributes.typescriptServerPlugins` setting in `package.json`.

## Install

**CocInstall**:

> ...TODO

**e.g. vim-plug**:

```vim
Plug 'yaegassy/coc-typescript-vue-plugin', {'do': 'yarn install --frozen-lockfile'}
```

## Thanks

- [vuejs/language-tools](https://github.com/vuejs/language-tools)

## License

MIT

---

> This extension is built with [create-coc-extension](https://github.com/fannheyward/create-coc-extension)
