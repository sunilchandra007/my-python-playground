### 🌟 UV: A Modern Python Package Manager

- ⚡ **Blazing Fast**: Written in Rust for high performance.
- 🧰 **Unified Tooling**: Designed to replace tools like `pip`, `virtualenv`, and `poetry` with a single, streamlined solution.
- 🚀 **Superior Speed**: Faster than `pip` for dependency resolution and installation.

```bash
# 1. Create a new uv project
uv init

# 2. Create a virtual environment
uv venv

# install dependency from project toml file
uv sync

# show depenndency tree
uv tree

# 3. Start the virtual environment
source .venv/bin/activate

# 4. Install packages from requirements.txt
uv pip install -r requirements.txt

# 5. Install additional dependencies in the virtual environment
uv add "mcp[cli]" httpx

# 6. Install Jupyter and register the environment as a kernel
uv pip install notebook ipykernel
python -m ipykernel install --user --name=uv-env --display-name "Python (uv-env)"

# 7. Run Jupyter Notebook
jupyter notebook

# 7a. troubleshooting - check kernal in use
import sys
print("Python executable:", sys.executable)

# 8. Stop the virtual environment when done
deactivate

```
