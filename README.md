# Toshiba AC control
This software allows to control Toshiba AC

## Instalation
1. Download or clone this repository to desired directory:

    `git clone https://github.com/KaSroka/Toshiba-AC-control.git`
2. Install toshiba-ac package:

    `pip3 install .`

    If you want to edit the code you can install package as editable:

    `pip3 install -e .`

## Sample script
Sample GUI application `toshiba_ac_gui.py` was created to demonstrate usage of this package. It allows to switch basic functionalities of the AC and shows current status.

It requires to provide env variables with login information:
```
TOSHIBA_USER=<USER_NAME> TOSHIBA_PASS=<PASSWORD> python3 toshiba_ac_gui.py
```
or
```
export TOSHIBA_USER=<USER_NAME>
export TOSHIBA_PASS=<PASSWORD>
python3 toshiba_ac_gui.py
```
