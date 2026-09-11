# hooksmith

A handful of React hooks I keep copy-pasting between projects

Built for my own use; public in case it helps someone.

## Installation

```bash
npm install
npm test
```

## How to use

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## What it does

- Tiny: no dependencies besides React
- useLocalStorage with JSON serialization
- useDebounce with leading/trailing options
- useMediaQuery SSR-safe

## Project structure

```text
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── bug_report.md
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
└── package.json
```

## Development

```bash
npm install
```

## License

MIT. Do whatever you want.
