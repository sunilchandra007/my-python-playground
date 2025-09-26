### 🌟 UV: A Modern Python Package Manager

- ⚡ **Blazing Fast**: Written in Rust for high performance.
- 🧰 **Unified Tooling**: Designed to replace tools like `pip`, `virtualenv`, and `poetry` with a single, streamlined solution.
- 🚀 **Superior Speed**: Faster than `pip` for dependency resolution and installation.

```bash
#create a new uv project
uv init

#create a virtual environment
uv venu

#start a virtual environment
source .venv/bin/activate

#install packages
pip install -r requirements.txt

#install the dependency in virtual env
uv add "mcp[cli]" httpx

#stop the virtual environment
deactivate
```
