# Python GUI Excel Unprotect
# Preface: 
Tried of your co-workers protecting the sheet and using that as a concrete-evidence that their work is tamper-proofed? Use this project to prove them wrong. (LOL JK) but this project provides a quick way for not-so-technical users to unprotect their excel.

### One-liner:
```shell
git clone https://github.com/manitouphon/gui-python-excel-unprotector
cd gui-python-excel-unprotector
python3 -m pip install -r requirements.txt
python3 ./gui.py
```
<img src="https://github.com/manitouphon/gui-python-excel-unprotector/blob/28edf802b1c52842f71860b11582c46ece093244/excel-unprotect-gui-screenshot.png" alt="Brida Logo"/>

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

(Beware that the output executable might get flagged by AV as it will extracts python env to Temp folder which is how most malware loads their things).
