# gptsh

Tiny streaming CLI for OpenAI-compatible chat APIs

## Install

```bash
pip install -r requirements.txt
export OPENAI_API_KEY=sk-...
```

## Features

- Streams tokens as they arrive
- Model and system prompt via flags or env
- Works with any OpenAI-compatible endpoint
- Reads the prompt from args or stdin

## Usage

```bash
chatsh explain this error < error.log
cat diff.patch | chatsh review this diff
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── configuration.md
│   ├── roadmap.md
│   └── usage.md
├── tests/
│   └── test_smoke.py
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── chatsh.py
└── requirements.txt
```

## License

MIT licensed, see LICENSE.
