# Configuration Vscode mode Developpeur 

- extract then type on the font cascadia code
    - go to ttf file
    - install them do, on Windows

- [Installation fira font ](https://github.com/tonsky/FiraCode/wiki/VS-Code-Instructions)
- [Installation cascadia](https://github.com/microsoft/cascadia-code/wiki/Installing-Cascadia-Code)
- [Repository cascadia code](https://github.com/microsoft/cascadia-code)

In the vscode settings: 
- put in font family ```'Cascadia Code', Consolas, 'Courier New', monospace```
- put on the ligatures : ```"editor.fontLigatures": true,```
    - by default : null

- type in the minimap search > uncheck: render caracters
- to display the 120-word line, add :

```json
"editor.rulers": [
    120
],
```
# configuration json : mise a jour 17.10.2020

```json
{   
    // theme
    "workbench.colorTheme": "Tinacious Design",
    // font family Cascadia Code
    "editor.fontFamily": "'Cascadia Code', Consolas, 'Courier New', monospace",
    "editor.lineHeight": 26,
    "editor.fontSize": 15,
    "editor.fontLigatures": true,

    // terminal bash git
    "terminal.integrated.shell.windows": "C:\\Program Files\\logiciels\\Git\\bin\\bash.exe",
    "terminal.integrated.fontFamily": "Meslo LG M DZ for Powerline",

    // minimap
    "editor.minimap.renderCharacters": false,
    "editor.minimap.maxColumn": 200,
    "editor.minimap.showSlider": "always",
    
    // cursor
    // "editor.cursorBlinking": "Phase",
    // "editor.cursorSmoothCaretAnimation": true,
    // "editor.cursorStyle": "block"
}
```

## Other information :
- Font size: 16
- Line height: 24 ou 26