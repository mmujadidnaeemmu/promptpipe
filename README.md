# promptpipe

Tiny streaming CLI for OpenAI-compatible chat APIs

Small but I use it weekly.

## How to use

```bash
chatsh explain this error < error.log
cat diff.patch | chatsh review this diff
```

## Installation

```bash
pip install -r requirements.txt
export OPENAI_API_KEY=sk-...
```

## Features

- Streams tokens as they arrive
- Model and system prompt via flags or env
- Works with any OpenAI-compatible endpoint
- Reads the prompt from args or stdin

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── faq.md
├── tests/
│   └── test_smoke.py
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── chatsh.py
└── requirements.txt
```

## License

MIT licensed, see LICENSE.
