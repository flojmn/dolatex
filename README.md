# dolatex
dolatex is a tool that combines the convenience of Docker & LaTeX with Visual Studio Code. It enables integration between LaTeX and VS Code, providing a smooth workflow for writing, editing, and compiling LaTeX documents.

## Features
+ **Dockerized LaTeX:** dolatex utilizes Docker to provide a consistent and isolated LaTeX environment. You no longer need to worry about installing LaTeX distributions on your local machine or dealing with compatibility issues.
+ **Visual Studio Code Integration:** dolatex integrates seamlessly with Visual Studio Code, allowing you to write, edit, and compile LaTeX documents using the familiar and feature-rich editor. Enjoy enhanced productivity and a comfortable development experience.
+ **Syntax Highlighting and Autocompletion:** Take advantage of Visual Studio Code's powerful syntax highlighting and autocompletion capabilities. dolatex enhances your LaTeX editing experience by providing context-aware suggestions and highlighting syntax errors as you type.

## Getting Started
### Windows
+ Install [Docker Desktop]([https://pages.github.com/](https://www.docker.com/products/docker-desktop/)https://www.docker.com/products/docker-desktop/) on your system.

## Installation
Clone the dolatex repository to your local machine: 
```shell
git clone git@github.com:flojmn/dolatex.git
```
## Usage
1. Open Visual Studio Code and navigate to the "dolatex" folder. 
5. Press Ctrl + Shift + P to open the command palette, and select "dolatex: Rebuild and Reopen in Container".
6. Begin writing your LaTeX document in Visual Studio Code. Save the file to trigger the automatic compilation and view the live preview of your document.
7. To stop the dolatex container, use the command "dolatex: Stop Container" in the command palette.
