## <img align="left" width="100px" src="https://user-images.githubusercontent.com/19890545/179967638-6b0e4e7d-7f8c-412a-b87d-47ba8e694477.png" alt="ebitengine-kage-support" /> Ebitengine Kage support for Sublime Text

Basic syntax and snippet support for the Ebitengine Kage shading language. 

<br>

Ebitengine adopts an original shading language 'Kage'. This has a compatible syntax with Go, but the details are different. Kage has high portability. Ebitengine uses graphics libraries like OpenGL or Metal and this depends on environments, but Kage is compiled on the fly so that this works equally everywhere.

### Installation

[![](https://img.shields.io/badge/get%20it%20from-555555?style=for-the-badge&logo=sublimetext&logoColor=ba9759)![](https://img.shields.io/badge/package%20control-ba9759?style=for-the-badge)](https://packagecontrol.io/packages/Ebitengine%20Kage)

<details><summary>Manual installation</summary><br>
  
  To add a package manually, open command palette and type `Package Control: Add Repository`.

  ![image](https://user-images.githubusercontent.com/19890545/179971478-0cd10e28-ac31-46c4-8c2d-e40152c45025.png)

  In the dialog that opens below, enter the url of the repository `https://github.com/sedyh/ebitengine-kage-sublime`.

  ![image](https://user-images.githubusercontent.com/19890545/179971756-9a4e9909-56ae-4903-9640-e8319a62bf91.png)

  Then open the package installation via `Package Control: Install Package` dialog and find `ebitengine-kage-sublime` package there.

  ![image](https://user-images.githubusercontent.com/19890545/179972515-1e443959-7833-4c14-beaf-fd92fd930e86.png)

  ![image](https://user-images.githubusercontent.com/19890545/179972097-273131df-0e98-4ce4-b8db-6096cbb82df8.png)
  
</details>

### Other editors

[![](https://img.shields.io/badge/source-555555?style=for-the-badge&logo=vim&logoColor=60b371)](https://github.com/sedyh/ebitengine-kage-vim)[![](https://img.shields.io/badge/download-60b371?style=for-the-badge)](https://www.vim.org/scripts/script.php?script_id=6021)<br>
[![](https://img.shields.io/badge/source-555555?style=for-the-badge&logo=visualstudiocode&logoColor=72a9d4)](https://github.com/sedyh/ebitengine-kage-vscode)[![](https://img.shields.io/badge/download-72a9d4?style=for-the-badge)](https://marketplace.visualstudio.com/items?itemName=sedyh.ebitengine-kage)

### Features

- [Basic syntax highlighting](#basic-syntax-highlighting)
- [Quick start](#quick-start)
- [Short documentation](#short-documentation)
- [List of all built-in functions](#list-of-all-built-in-functions)

### Basic syntax highlighting

<a href="#features"><img src="https://user-images.githubusercontent.com/19890545/150034365-6561ab71-5cb4-466f-996c-ae4204ef7c12.png" alt="back" title="back" width="16px"/></a> This plugin provides basic Kage language support for Ebitengine. It includes keywords, types, literals and snippets.

![feature-syntax](https://user-images.githubusercontent.com/19890545/178739793-e745e6bf-dea6-4454-8d85-9c72ed970967.png)

### Quick start

<a href="#features"><img src="https://user-images.githubusercontent.com/19890545/150034365-6561ab71-5cb4-466f-996c-ae4204ef7c12.png" alt="back" title="back" width="16px"/></a> To quickly start writing a shader, you can type "fragment" or "package".

![feature-quickstart](https://user-images.githubusercontent.com/19890545/178740612-bfdb4bae-1d6e-47bc-9c0b-3dc122fcfdd7.png)

### Short documentation

<a href="#features"><img src="https://user-images.githubusercontent.com/19890545/150034365-6561ab71-5cb4-466f-996c-ae4204ef7c12.png" alt="back" title="back" width="16px"/></a> The plugin provides a short help for each feature in Kage.

![feature-description](https://user-images.githubusercontent.com/19890545/178740945-85d75d86-0af7-4224-8c3a-c684af59500a.png)

### List of all built-in functions

<a href="#features"><img src="https://user-images.githubusercontent.com/19890545/150034365-6561ab71-5cb4-466f-996c-ae4204ef7c12.png" alt="back" title="back" width="16px"/></a> You can see a list of all built-in functions by typing "kage".

![feature-help](https://user-images.githubusercontent.com/19890545/178741240-4df370c2-7b20-409f-9437-a213aa198a2f.png)

## Known Issues

The plugin will highlight complex numbers despite the fact that, at the moment, Kage does not support them.
