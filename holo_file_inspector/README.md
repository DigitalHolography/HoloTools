A simple python script to manipulate the header and footer of an .holo file.

# Build

In order to build the script into a single executable run:

```bash
pyinstaller.exe --onefile --name "Holo file inspector" main.py
```

The executable will be located at `./dist/Holo file inspector.exe`.
You can better customize the build by changing parameter in the `./Holo file inspector.spec` file.

# Development

If you want to contribute to the script install the required package with:

```bash
pip install -r requirements.txt
```
