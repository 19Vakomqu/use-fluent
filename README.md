# use-fluent

Small typed hooks: debounce, localStorage, media query, toggle

## Usage

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Installation

```bash
npm install
npm test
```

## Features

- Tiny: no dependencies besides React
- useLocalStorage with JSON serialization
- useDebounce with leading/trailing options
- useMediaQuery SSR-safe

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   └── development.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
└── package.json
```

## Development

```bash
npm install
```

## License

MIT licensed, see LICENSE.
