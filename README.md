### Installation and Configuration

1. Clone the repository:
```bash
git https://github.com/phillipefs/how-to-validate-the-excel-schema.git
cd how-to-validate-the-excel-schema
```

2. Set up the correct Python version with `pyenv`:
```bash
pyenv install 3.11.5
pyenv local 3.11.5
```

3. Install project dependencies:
```bash
python -m venv .venv
# The default is to use .venv
source .venv/bin/activate
# For Linux and Mac users
.venv\Scripts\Activate
# For Windows users
pip install -r requirements.txt  
```