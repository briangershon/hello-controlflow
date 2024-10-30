# hello-controlflow

Play with [ControlFlow](https://controlflow.ai/) Python framework for building agentic AI workflows, using `uv` Python package and project manager.

## Run

For installing dependencies

- ensure rust and cargo are installed. You can use `brew install rust` on MacOS.
- Intentionally using 3.12 in `.python-version` which is max version currently supported by `pyo3` package.

Run

```bash
export OPENAI_API_KEY="your-api-key"
uv run hello.py
```
