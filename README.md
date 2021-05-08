# Cansat-2021
Software for CanSat Team 3226 P.O.P.T.A.R.T.S.

## Ground Control Software Build Instructions

### Windows
```bat
:: Create virtual environment
$ python -m venv venv

:: Start virtual environment
$ call venv/scripts/activate.bat

:: Install required packages
$ pip install -r requirements.txt

:: Run the GCS
$ python main.py

:: Leave the virtual environment
$ deactivate
```

### Linux
```bash
# Create virtual environment
$ python3 -m venv venv

# Start virtual environment
$ source /venv/bin/activate

# Install requried packages
$ pip install -r requirements.txt

# Run the GCS
$ python3 main.py

# Leave the virtual environment
$ deactivate
```
