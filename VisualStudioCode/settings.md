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

# configuration json : mise a jour 17.10.2020

```json
{   
    // theme
    "workbench.colorTheme": "Tinacious Design",
    // font family
    "editor.fontFamily": "'Cascadia Code', Consolas, 'Courier New', monospace",
    "editor.fontLigatures": true, //default (null)
    // terminal bash git
    "terminal.integrated.shell.windows": "C:\\Program Files\\logiciels\\Git\\bin\\bash.exe"
    // minimap
    "editor.minimap.renderCharacters": false
}
```