[![MyPy Check](https://github.com/Process-Mining-Group-9/backend/actions/workflows/mypy.yml/badge.svg)](https://github.com/Process-Mining-Group-9/backend/actions/workflows/mypy.yml)

# Installation and Running

1. Check that your Python version is relatively new (```python --version```). Version 3.8 is used in production.
2. Create a virtual environment using ```python -m venv venv``` and activate it:
   1. On Linux: ```source venv\bin\activate```
   2. On Windows: ```\venv\Scripts\activate```
3. Install the required packages using ```pip install -r requirements.txt```.
4. Navigate to the ```src``` directory and run the application with ```python main.py```

## Type Checking

Use ```mypy src``` to type-check the code for type violations.
