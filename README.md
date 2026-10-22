# Ai Agent 

This is a simple ai agent made using Python.

## About

This project is a part of a backend course on [boot.dev](https://www.boot.dev/). 

> [!Warning]
> This tool is not designed to run in a production environment. It's a proof-of-concept and watered down version of what a real coding agent does. Run at your own risk.

## Requirements

- uv
- Python 3.14+
- dotenv

## Installation
1. Clone the repository.

   ```bash
   git clone https://github.com/faisalalhatimi/ai-agent.git
   cd ai-agent
   ```

2. Create a `.env` file in the project root and configure the following environment variable.

   ```env
   OPENROUTER_API_KEY=your_api_key
   ```



3. Install the dependencies.

   ```bash
   uv sync
   ```

## Usage

- `uv run main.py <prompt>`
- `--verbose` displays prompt metadata (e.g. prompt tokens)
