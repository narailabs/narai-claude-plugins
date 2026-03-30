# Narai Plugins

Claude Code plugin marketplace by [NarAI Labs](https://github.com/narailabs).

## Setup

Add this marketplace to Claude Code:

```bash
claude plugin:marketplace add narailabs/narai-claude-plugins
```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [browser-qa](https://github.com/narailabs/claude-browser-qa) | AI-powered QA agent |
| [agentic-tdd](https://github.com/narailabs/claude-agentic-tdd) | Enforced TDD with agent teams, structural enforcement gates, three-stage review |
| [feedback-loop-builder](https://github.com/narailabs/claude-feedback-loop-builder) | Retrofit self-improving feedback loops into skills/agents |

## Usage

Install a plugin from this marketplace:

```bash
claude plugin install narailabs/claude-browser-qa
```

## Contributing

1. Fork this repository
2. Add your plugin entry to `.claude-plugin/marketplace.json`
3. Submit a pull request

## License

[MIT](LICENSE)
