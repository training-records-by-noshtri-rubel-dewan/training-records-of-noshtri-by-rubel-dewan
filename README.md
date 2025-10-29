# training-records-of-noshtri-by-rubel-dewan
Cantonment Road, Terokhadia, Rajpara, Raishahi-6202   www.noshtrri.gov.bd E-mail: jig.noshtri@dife.gov.bd
Training Records — Windows package
---------------------------------

Contents:
- training_records_excel_app.py   (the application source)
- Training records_Master Final 29102025.xlsx  (your Excel data file)
- build_exe.bat                  (one-click build script for Windows)
- README.txt                     (this file)

How to use (run without Python):
1. On a Windows machine with Python installed, open Command Prompt in this folder.
2. Install required packages (one-time):
   pip install pandas openpyxl pyinstaller
3. To build a single-file EXE (recommended):
   Double-click build_exe.bat OR run in CMD:
   build_exe.bat
   This will run PyInstaller and create 'dist\\training_records_excel_app.exe'.
4. After building, you'll find the executable in the 'dist' folder. Copy that .exe to any Windows PC and run it.
5. The app expects the Excel file to be in the same folder as the .exe. If you move the .exe, copy the Excel file alongside it or re-open your Excel file from the app.

Notes:
- Each save creates a backup of the Excel file in the same folder (filename with timestamp).
- If you want me to produce the .exe for you directly, I can attempt it, but building Windows executables from this environment may not be reliable. The provided build_exe.bat makes it one-click on your Windows machine.
- If you want different column mapping or UI changes, let me know before building the exe.

Generated on: 2025-10-29
