# LaTeX Submodule
Set up your LaTeX projects quickly using GitHub submodules! 

----

## Importing the submodule
To add this submodule to your LaTeX project, use the following command:
```shell
git submodule add https://github.com/Tarang74/LaTeX-Submodule
```
## Linking the ignore file
The provided `.gitignore` file can be accessed using a symbolic link.
### Linux & macOS:
```bash
ln -s submodule\.gitignore submodule.gitignore
```
### Windows (requires Admin):
```batch
mklink submodule.gitignore submodule\.gitignore
```
**Note:** *to allow you to add your own ignore patterns, the ignore file is named `submodule.gitignore`.*
## Using the styles
To utilise the styles in `template.sty`, place the following command in the preamble of your document.
```latex
\usepackage{template}
```
As TeX searches for files within subdirectories, we do not need to specify the subfolder.
