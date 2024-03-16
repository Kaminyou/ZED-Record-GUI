# ZED-Record-GUI
A GUI implemented by Python for ZED video recording

## Dependency
### `tkinter`
```
$ sudo apt-get install python3-tk
```

### `pyinstaller`
```
$ pip install pyinstaller
```

## Build
```
$ pyinstaller --hidden-import=tkinter --hidden-import=tkinter.filedialog main.py --onefile -w
```
Then the executable file will be `dist/main`

