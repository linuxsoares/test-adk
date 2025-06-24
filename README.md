# Test ADK (Agent Development Kit)

A test project for exploring Google's Agent Development Kit (ADK) library for building AI agents.

## About

This project serves as a testing ground and experimental environment for the Google ADK library, which is designed for developing intelligent agents. The repository contains a multi-tool agent implementation that demonstrates various capabilities and features of the ADK framework.

## Project Structure

```
test-adk/
├── main.py                 # Main entry point
├── multi_tool_agent/       # Multi-tool agent implementation
│   ├── __init__.py
│   └── agent.py           # Core agent logic
├── Makefile               # Build and run commands
├── pyproject.toml         # Python project configuration
├── uv.lock               # Dependency lock file
└── README.md             # This file
```

## Getting Started

### Prerequisites

- Python 3.x
- [uv](https://github.com/astral-sh/uv) package manager

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/linuxsoares/test-adk.git
   cd test-adk
   ```

2. Install dependencies:
   ```bash
   uv sync
   ```

### Usage

#### Run the main application:
```bash
make run
# or
uv run python main.py
```

#### Run the web interface:
```bash
make web
# or
uv run adk web
```

## Purpose

This project is designed to:
- Test and explore the capabilities of Google's ADK library
- Experiment with multi-tool agent implementations
- Provide a foundation for agent development and testing
- Demonstrate best practices for ADK-based projects

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to submit issues, fork the repository, and create pull requests for any improvements.
