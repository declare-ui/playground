<p align="left">
    <img width="1280" height="192" alt="DeclareUI" src="https://github.com/user-attachments/assets/d51c038f-7822-4ee4-beb8-f438894f7736#gh-light-mode-only" />
    <img width="1280" height="192" alt="DeclareUI" src="https://github.com/user-attachments/assets/44918531-3b1b-4ace-bca0-db0ea99f8bc8#gh-dark-mode-only" />
</p>

# DeclareUI Playground

Interactive web playground — edit YAML components and preview the generated output in all target frameworks, live in the browser.

---

## Features

- **Live editor** — write `.ui.yaml` with syntax highlighting and autocomplete
- **Multi-framework preview** — see the generated React, Vue, Svelte, Angular, and Web Components code side by side
- **Rendered preview** — view the actual rendered component
- **Shareable links** — share your component declarations via URL
- **Template gallery** — start from pre-built component templates
- **Zero setup** — runs entirely in the browser, no install needed

## Development

```bash
pnpm install
pnpm dev
```

## Tech stack

- Vite + React
- Monaco Editor (YAML editing)
- `@declareui/core` (compiled to WASM for browser use)
- Tailwind CSS

## Related packages

| Package | Description |
|:--------|:------------|
| [`@declareui/core`](https://github.com/declare-ui/core) | Parser, AST, and code generators |
| [`@declareui/components`](https://github.com/declare-ui/components) | Pre-built component library |
| [`@declareui/docs`](https://github.com/declare-ui/docs) | Documentation site |

## Contributing

See [CONTRIBUTING.md](https://github.com/declare-ui/.github/blob/main/CONTRIBUTING.md) for guidelines.

## License

MIT
