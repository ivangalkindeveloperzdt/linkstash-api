# linkstash-api

Learning project: clean Express API structure

## What it does

- REST endpoints: list / create / delete / search
- Morgan logging and centralized error handler
- env-driven port, runs anywhere Node does
- Request validation helpers, no framework magic
- In-memory store with optional JSON persistence

## Install

```bash
npm install
npm run dev
```

## Usage

```bash
curl -X POST localhost:3000/api/bookmarks \
  -H 'content-type: application/json' \
  -d '{"url": "https://example.com", "tags": ["reading"]}'
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── usage.md
├── src/
│   ├── config.js
│   ├── index.js
│   └── store.js
├── .editorconfig
├── .gitignore
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

## 说明

个人练习项目, 谨慎用于生产环境。

## License

MIT licensed, see LICENSE.
