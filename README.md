```console
$ uv --version
uv 0.7.7 (Homebrew 2025-05-22)

$ # Create a packaged application project
$ uv init --package my-uv-tool

$ # Run the default command
$ cd my-uv-tool
$ uv run my-uv-tool

$ # ... Write your code (or outsource it to AI) ...
$ # ... Define the entry points in pyproject.toml ...

$ # Install the tool
$ uv tool install -e .

$ # Set up PATH if needed (restart your shell afterward)
$ uv tool update-shell

$ # Run the command from anywhere
$ my-uv-tool
```

- Details:
  - Japanese: [https://note.nkmk.me/python-uv-cli-tool/](https://note.nkmk.me/python-uv-cli-tool/)
  - English: [https://note.nkmk.me/en/python-uv-cli-tool/](https://note.nkmk.me/en/python-uv-cli-tool/)
