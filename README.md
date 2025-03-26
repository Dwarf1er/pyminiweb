# pyminiweb

`pyminiweb` is a mini web framework built to experiment with making my a web framework more-or-less from scratch.

- [pyminiweb](#pyminiweb)
  - [Installation](#installation)
  - [License](#license)

## Installation

To set up the development environment for `pyminiweb`, follow these steps:

1. Clone the repository
   ```bash
   git clone https://github.com/Dwarf1er/pyminiweb
   ```
2. Navigate to the project directory
   ```bash
   cd path/to/pyminiweb
   ```
3. Install `virtualenv` if you haven't already installed it, you can do so using `pip`
   ```bash
   pip install virtualenv 
   ```
4. Create a virtual environment
   ```bash
   python -m venv .venv
   ```
5. Activate the virtual environment
   ```bash
   # On Linux/MacOS
   source .venv/bin/activate

   # On Windows
   .\.venv\Scripts\Activate.ps1
   ```
6. Install the required dependencies
   ```bash
   pip install -r requirements.txt
   ```
7. Add new dependencies to requirements.txt
   ```
   pip freeze > requirements.txt
   ```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.