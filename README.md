# Todo Generator

A CLI tool to generate customizable, themed todo lists from Markdown files and integrate with popular task managers.

## Installation

```bash
pip install todo-generator
```

## Usage

```bash
todo-generator --file todo.md --theme default --task-manager-url http://localhost/api/tasks
```

## Configuration

Create a `config.toml` file with the following content:

```toml
[markdown_file]
file = 'todo.md'

[theme]
theme = 'default'

[task_manager]
url = 'http://localhost/api/tasks'
```
