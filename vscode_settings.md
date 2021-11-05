# VS-Code settings

## Extensions

- Python
- Python Extension Pack
- Python Docstring Generator
- GitHub Pull Requests and Issues
- Jupyter
- Jupyter Keymap
- Jupyter Notebook Renderers
- Markdown Preview Enhanced
- markdownlint
- Pylance
- reStructuredText
- Visual Studio IntelliCode
- Code Runner
- LaTex Workshop
- Live Share (for collaborating with your team on vs code!)

*and GitHub Copilot - sign up to be on the waitlist [here](https://github.com/features/copilot/signup)!*

## Settings

```json
{
    "markdown-preview-enhanced.automaticallyShowPreviewOfMarkdownBeingEdited": true,
    "security.workspace.trust.untrustedFiles": "open",
    "github.copilot.enable": {
        "*": true,
        "yaml": false,
        "plaintext": true,
        "markdown": true
    },
    "editor.inlineSuggest.enabled": true,
    "editor.renderControlCharacters": true,
    "editor.renderWhitespace": "all",
    "editor.wordWrap": "wordWrapColumn",
    "editor.wordWrapColumn": 100,
    "editor.formatOnSave": true,
    "editor.codeActionsOnSave": {
        "source.organizeImports": true
    },
    "files.trimTrailingWhitespace": true,
    // "python.pythonPath": "E:\\Program Files\\WPy64-3880\\python-3.8.8.amd64\\python.exe",
    "python.pythonPath": "C:\\Program Files\\Python39\\python.exe",
    "python.defaultInterpreterPath": "C:\\Program Files\\Python39\\python.exe",
    "python.formatting.provider": "black",
    "python.formatting.blackArgs": [
        "-l 100"
    ],
    "autoDocstring.docstringFormat": "numpy",
    "cSpell.userWords": [
        "neuropsychologist",
        "neuropsychologists"
    ],
    "cSpell.language": "en,fr",
    "workbench.editorAssociations": {
        "*.ipynb": "jupyter-notebook"
    },
    "autoDocstring.includeName": true,
    "autoDocstring.startOnNewLine": true,
    "files.autoSave": "afterDelay",
    "security.workspace.trust.enabled": false,
    "jupyter.enableNativeInteractiveWindow": true,
    "jupyter.sendSelectionToInteractiveWindow": true,
    "editor.formatOnType": true,
    "jupyter.runStartupCommands": [
        // Always import these packages
        "import numpy as np",
        "import pandas as pd",
        "import matplotlib.pyplot as plt",
        "import matplotlib",
        "import sys",
        // Matplotlib settings
        "plt.rcParams['figure.figsize'] = [19.2, 10.8]",
        "matplotlib.use('TkAgg')", // wxAgg, Qt5Agg
        "%matplotlib auto", // widget
        // The following must be adapted based on your environment
        "sys.path.append('C:/Dropbox/RealityBendingLab/Pyllusion/')",
        "sys.path.append('C:/Dropbox/RECHERCHE/N/NeuroKit/')",
        "sys.path.append('C:/Dropbox/RECHERCHE/N/TruScanEEGpy/')",
        "sys.path.append('C:/Dropbox/RECHERCHE/N/mne-python/')",
        "import neurokit2 as nk"
    ],
    "jupyter.askForKernelRestart": false,
    "notebook.cellToolbarLocation": {
        "default": "right",
        "jupyter-notebook": "left"
    },
    "spellright.language": [
        "en",
        "fr"
    ],
    "settingsSync.ignoredSettings": [
        // These are machine-dependent must be setup manually
        // e.g., "python.pythonPath": "C:\\Program Files\\Python39\\python.exe",
        "python.pythonPath",
        "python.defaultInterpreterPath"
    ],
    "jupyter.interactiveWindowMode": "single",
    "jupyter.widgetScriptSources": [
        "jsdelivr.com",
        "unpkg.com"
    ]
}
```
