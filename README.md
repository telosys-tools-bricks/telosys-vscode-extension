# Telosys plugin for VSCode editor

Telosys templates, DSL models and configuration files support for VSCode.  

## Features

This package provides syntax coloration and auto-completion for :  
- Telosys DSL model ".entity" & ".model" files.  
- Telosys configuration files ".cfg".  
- Telosys template files ".cfg".  

## Installation

1. In Visual Studio Code, click on the "Extensions" icon (or CTRL+Maj+X).  
2. In the search box, write "telosys".  
3. The Telosys plugin should appear, just click on "Install", wait for installation completion then hit "Reload" and you're done !  

**ADDITIONAL** : If you want to use Telosys-CLI from VSCode :  
1 - Install Telosys-CLI by following the instructions at [the Telosys-CLI repo](https://github.com/telosys-tools-bricks/telosys-cli)  
2 - In Visual Studio Code, use the Ctrl+Maj+C keybinding to start a new console, then type "tt". Telosys-CLI will start at your project's folder.  
  
-- OR --  
For an advanced integration of Telosys-CLI :  
1 - Install Telosys-CLI by following the instructions at [the Telosys-CLI repo](https://github.com/telosys-tools-bricks/telosys-cli)  
2 - Install the VSCode Extension [Open in User Defined Console](https://marketplace.visualstudio.com/items?itemName=vilicvane.console) and set the following configuration :  
```  
Example for windows :
{
    "console.executable": "cmd.exe",
    "console.args": ""/C start tt -h {dirname}""
}
```  
4 - Use the keybinding of the extension (Ctrl/Cmd+Shift+C) to open Telosys-CLI in your working directory with the path automatically set.

## License

This package uses the [LGPL v3 License](https://www.gnu.org/licenses/lgpl-3.0.en.html) (See the LICENSE file in this repository).  

## Credits

- Made by [Romuald Tuffreau](https://github.com/romwaldtff).  
- [Laurent Guerin](https://github.com/l-gu) for [Telosys](http://telosys.org/) and [Telosys-CLI](https://github.com/telosys-tools-bricks/telosys-cli).