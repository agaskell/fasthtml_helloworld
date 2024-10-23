Running

- Get [uv](https://github.com/astral-sh/uv?tab=readme-ov-file#installation) installed.
- In this directory, run `uv run python src/hello-fasthtml.py`. This will:
    - Install the required version of Python.
    - Install all dependencies. See [pyproject.toml](./pyproject.toml) and [uv.lock](./uv.lock).
    - Run the Python program.


VS Code

- Be sure to have Python and Pylance extensions installed.
- Not sure if [.vscode/settings.json](.vscode/settings.json) is needed but I've had to add lines like this to my Python projects.
- See [.gitignore](.gitignore) for disclaimer on including [.vscode](.vscode) :)