# CLAUDE.md - Guidelines for Agentic Coding

## Commands
- Run Jupyter notebook: `jupyter notebook claude.ipynb`
- Python execution: `python -m script_name.py`
- Install packages: `pip install -r requirements.txt` (if requirements.txt exists)
- Run tests: `pytest` (when test files are added)
- Run single test: `pytest path/to/test_file.py::test_function_name -v`
- Lint code: `flake8` or `pylint *.py`
- Format code: `black .` or `black specific_file.py`

## Style Guidelines
- **Formatting**: Follow PEP 8 standards, use black for auto-formatting
- **Imports**: Group imports (stdlib, third-party, local) with one blank line between groups
- **Types**: Use type hints for function parameters and return values
- **Naming**: snake_case for variables/functions, PascalCase for classes
- **Docstrings**: Use Google style docstrings for functions and classes
- **Error handling**: Use try/except blocks appropriately, avoid bare except
- **Jupyter notebooks**: Keep cells focused on single tasks, include markdown documentation
- **Python version**: Code is using Python 3.10+ features