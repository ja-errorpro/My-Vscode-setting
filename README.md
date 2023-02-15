# VSCode Settings

## Installed Extensions

- [Android iOS Emulator](https://marketplace.visualstudio.com/items?itemName=DiemasMichiels.emulate)
Use Android and iOS emulators directly from VS Code.
- [background](https://marketplace.visualstudio.com/items?itemName=shalldie.background)
For setting the background image of VSCode.
- [Better C++ Syntax](https://marketplace.visualstudio.com/items?itemName=jeff-hykin.better-cpp-syntax)
A better C++ syntax for VS Code.
- [C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
C/C++ IntelliSense, debugging, and code browsing.
- [C/C++ Extension Pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools-extension-pack)
A collection of extensions that provide a rich C/C++ editing experience.
- [C/C++ Themes](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools-themes)
Themes for C/C++.
- [Chinese (Traditional) Language Pack for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-zh-hant)
繁體中文化
- [Clang-Format](https://marketplace.visualstudio.com/items?itemName=xaver.clang-format)
Format C/C++/ObjC code using clang-format.(Requires llvm/clang to be installed.)
- [CMake](https://marketplace.visualstudio.com/items?itemName=twxs.cmake)
- [CMake Tools](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cmake-tools)
- [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
code runner for multiple languages.
- [Competitive Programming Helper](https://marketplace.visualstudio.com/items?itemName=DivyanshuAgrawal.competitive-programming-helper)
test your code on various test cases.
- [Dart](https://marketplace.visualstudio.com/items?itemName=Dart-Code.dart-code)
Dart support and debugger for VSC.
- [Debugger for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-debug)
- [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
- [Extension Pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)
- [Flutter](https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter)
- [Github Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
AI-powered coding assistant.(Fee required)
- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Go](https://marketplace.visualstudio.com/items?itemName=golang.go)
- [Grandle for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-gradle)
- [IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
- [IntelliCode API Usage Examples](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.intellicode-api-usage-examples)
- [isort](https://marketplace.visualstudio.com/items?itemName=ms-python.isort)
- [JavaScript and TypeScript Nightly](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-next)
- [JavaScript Debugger (Nightly)](https://marketplace.visualstudio.com/items?itemName=ms-vscode.js-debug-nightly)
- [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
emulate a Jupyter notebook environment in VS Code.
- [Jupyter Cell Tags](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.vscode-jupyter-cell-tags)
- [Jupyter Keymap](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter-keymap)
- [Jupyter Notebook Renderers](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter-renderers)
- [Jupyter Slide Show](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.vscode-jupyter-slideshow)
- [Language Support for Java(TM) by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.java)
- [LaTeX language support](https://marketplace.visualstudio.com/items?itemName=torn4dom4n.latex-support)
- [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
Make documents or slides with LaTeX in VS Code.
- [Maven for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-maven)
- [Project Manager for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-dependency)
- [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)
- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- [Snippet Creator](https://marketplace.visualstudio.com/items?itemName=wware.snippet-creator)
- [solidity](https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity)
- [Test Runner for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-test)

## Description

### `settings_for_wins.json` 
* my frequently used settings for Windows.
* All of above extensions are required.

### `settings_for_wins_only_for_cpp.json` 
* for Windows, but only for C/C++.
* Required extensions: C/Cpp, Code Runner
* Required software: MinGW

### `settings_for_wins_only_for_cpp_with_clang.json`
* for Windows, but only for C/C++.
* Required extensions: C/Cpp, Code Runner, Clang-Format
* Required software: MinGW, LLVM/Clang
* Difference from `settings_for_wins_only_for_cpp.json`: Format codes using Google C++ Style while saving.

## Environment Variables(Windows)

需要設定環境變數以便讓 VS Code 可以找到編譯器。

You need to set environment variables so that VS Code can find the compiler.

如果是C/C++且環境為Windows，可參考我的[這篇文章](https://ja-errorpro.cf/posts/2022/vscode_cpp_setup/)

If it is C/C++ and the environment is Windows, you can refer to my [this article](https://ja-errorpro.cf/posts/2022/vscode_cpp_setup/)
