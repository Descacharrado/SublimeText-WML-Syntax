# SublimeText-WML-Syntax
Sublime text 3 package that is capable of basic highlighting in wesnoth markup language

## How to install on windows 10:
  - Go to windows and type "run"
  - type "%appdata%" and press enter
  - Go to "Sublime Text 3/Packages/user"
  - Clone the repo or copy the YAML files (WML.sublime-settings and WML.sublime-syntax) there
  
  You can also add my custom color scheme definitions (same folder, file Monokai.color-scheme) with the Monokai color scheme (Preferences > Select Color Scheme > Monokai)
  
## Basic implementation contains:
  - Coloring of WML Macros
  - Different colors for translatable and non-translatable strings
  - A special color for mainline unit types (if the unit type is not highlighted, you may have written it wrong)
  - A different color for tags (only admitted tags are colored)
  
## Wontfix:
  - Wrong attributes should not be highlighted (Reason: implementation would be too hard)
  - Numbers are highlighted where they should not (Reason: Can be avoided using quotation marks (""))

  ### Example:
  ![WMLSyntax](https://user-images.githubusercontent.com/30196839/197388755-c7b0ff45-442a-445c-92e1-f4c4b6dfb42b.png)
  An extract from wesnoth's HttT's first scenario's code

## To change the color scheme go to:
  https://www.sublimetext.com/docs/color_schemes.html
