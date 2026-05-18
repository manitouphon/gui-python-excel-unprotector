# Python GUI Excel Unprotect
# Preface: 
Tried of your co-workers protecting the sheet and using that as a concrete-evidence that their work is tamper-proofed? Use this project to prove them wrong. (LOL JK) but this project provides a quick way for not-so-technical users to unprotect their excel.

### Requirements:
Install Required Libraries 
```shell
python3 -m pip install -r requirements.txt
```

### How to use:
```shell
git clone https://github.com/manitouphon/gui-python-excel-unprotector
cd gui-python-excel-unprotector
python3 /.gui.py
```

## Compiling as an executable: 
Install PyInstaller
```shell
python3 -m pip install pyinstaller
```
Compile:
```shell
python3 -m PyInstaller --onefile --noconsole ./gui.py
```
You will find the executable file in ```/dist```
