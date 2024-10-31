# hello-controlflow

Start a project based on [ControlFlow](https://controlflow.ai/), a Python framework for building agentic AI workflows.

Find example ControlFlow code to play with at <https://controlflow.ai/examples>.

Features:

- a template repo for starting a ControlFlow app
- uses `uv` Python package and project manager that handles both virtual environment management and dependencies setup.

## Run it

prerequisites for installing dependencies:

- ensure rust and cargo are installed. You can use `brew install rust` on MacOS.
- intentionally uses Python 3.12 in `.python-version` which is max version currently supported by `pyo3` package.

```bash
export OPENAI_API_KEY="your-api-key"
uv run hello.py
```
