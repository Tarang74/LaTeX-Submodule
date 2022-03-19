# LaTeX Submodule

Set up your LaTeX projects quickly using GitHub submodules!

----

## Importing the submodule

To add this submodule to your LaTeX project, use the following command:

```shell
# HTML
git submodule add https://github.com/Tarang74/LaTeX-Submodule
# SSH
git submodule add git@github.com:Tarang74/LaTeX-Submodule.git
```

## Initialising the submodule

If you are using a project that contains this submodule, initialise it with the following commands:

```shell
git submodule init
git submodule update --remote
```

## Copying the ignore file

Use the following commands if you want to use the provided `.ignore` file.

### Linux & macOS

```bash
cp LaTeX-Submodule/.gitignore .gitignore
```

### Windows

```batch
copy LaTeX-Submodule\.gitignore .gitignore
```

## Using the styles

To use the definitions in `template.sty`, place the following command in the preamble of your document.

```latex
\usepackage{LaTeX-Submodule/template}
```
