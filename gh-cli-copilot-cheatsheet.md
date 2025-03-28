# cheat sheet

## slash commands

| command | description |
| -------- | ------- |
| /clear | Start a new chat session. |
| /explain| Explain how the code in your active editor works. |
| /fix| Propose a fix for problems in the selected code. |
| /fixTestFailure| Find and fix a failing test. |
| /help| Quick reference and basics of using GitHub Copilot. |
| /new| Create a new project. |
| /tests| Generate unit tests for the selected code. |

## chat variables

| variables | description |
| -------- | ------- |
| #block | Includes the current block of code in the prompt. |
| #class | Includes the current class in the prompt. |
| #comment | Includes the current comment in the prompt. |
| #file | Includes the current file's content in the prompt. |
| #function | Includes the current function or method in the prompt. |
| #line | Includes the current line of code in the prompt. |
| #path | Includes the file path in the prompt. |
| #project | Includes the project context in the prompt. |
| #selection | Includes the currently selected text in the prompt. |
| #sym | Includes the current symbol in the prompt. |

## chat participants

| variables | description |
| -------- | ------- |
| @azure | Has context about Azure services and how to use, deploy and manage them. Use @azure when you want help with Azure. The @azure chat participant is currently in public preview and is subject to change. |
| @github | Allows you to use GitHub-specific Copilot skills. See Asking GitHub Copilot questions in your IDE. |
| @terminal | Has context about the Visual Studio Code terminal shell and its contents. Use @terminal when you want help creating or debugging terminal commands. |
| @vscode | Has context about Visual Studio Code commands and features. Use @vscode when you want help with Visual Studio Code. |
| @workspace | Has context about the code in your workspace. Use @workspace when you want Copilot to consider the structure of your project, how different parts of your code interact, or design patterns in your project. |
