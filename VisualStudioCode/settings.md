# Configuration Vscode mode Developpeur 

- extraire puis taper sur la font cascadia code
    - aller dans le fichier ttf
    - installez-les font, sur Windows

- [Installation fira font ](https://github.com/tonsky/FiraCode/wiki/VS-Code-Instructions)
- [Installation cascadia](https://github.com/microsoft/cascadia-code/wiki/Installing-Cascadia-Code)
- [Repository cascadia code](https://github.com/microsoft/cascadia-code)

Dans les paramètres de vs code : 
- mettre dans font family ```'Cascadia Code', Consolas, 'Courier New', monospace```
- mettre les ligatures : ```"editor.fontLigatures": true,```
    - par defaut : null

- taper dans la recherche minimap > decocher : render caracters
- pour afficher la ligne 120 mots, il faut ajouter :
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

## Autre infos :
- Font size: 16
- Line height: 24 ou 26