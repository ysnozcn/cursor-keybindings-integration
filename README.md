
# Cursor Keybindings Integration

## Repository Purpose
This repository is designed to provide a seamless integration of Visual Studio Code’s default keybindings into Cursor, while allowing for custom shortcuts specific to Cursor. The goal is to make Cursor more usable for those accustomed to VS Code’s shortcuts, especially since some of Cursor’s default keybindings differ, which can create challenges for users.

## Why This is Needed
If you're a developer who enjoys using Cursor but finds it difficult to adapt due to changes in keybindings, this repository aims to solve that problem. By incorporating VS Code’s shortcuts into Cursor, you can maintain your familiar workflow while still benefiting from the unique features of Cursor. This will help in reducing the learning curve and make the transition smoother for VS Code users.

## How it Works
1. **Backup First**: Before starting, make sure to backup your existing Cursor `keybindings.json` file.
2. **Find/Create VS Code Keybindings**: Obtain or create a JSON file containing the default keybindings from VS Code.
3. **Copy Keybindings**: Copy the VS Code keybindings into Cursor’s `keybindings.json` file.
4. **Add Cursor-specific Commands**: If you want to keep or add Cursor-specific commands, manually edit the JSON file to include those custom bindings.
5. **Save & Restart**: Save the changes and restart Cursor to apply the new keybindings.

## Potential Risks
- Certain Cursor-specific commands or features might stop working as expected.
- There may be differences between VS Code and Cursor that prevent some shortcuts from working properly.
- Future updates to Cursor might affect your customized keybindings.

## Recommended Alternative Approach
To mitigate these risks:
1. Keep your existing Cursor keybindings intact.
2. Identify the specific shortcuts from VS Code you want to use.
3. Manually add or modify only those specific shortcuts in Cursor’s `keybindings.json` file. This ensures you maintain the integrity of both environments without breaking any essential Cursor functionality.



## New Shortcuts

### 1. `shift+cmd+space` -  Opens a New AI Chat Screen
This shortcut opens a new chat screen in Cursor, enabling you to interact with the AI chat functionality without navigating through menus.

### 2. `shift+cmd+a` -  Opens a New AI Chat Screen
This shortcut opens a new AI modal in Cursor, offering different behavior based on whether you’ve selected code or not.

### 3. `cmd+e` -  Generate in Terminal
This shortcut allows generating AI-suggested commands in the terminal. It can be triggered when the terminal is in focus and supports terminal processes, making it easier to run AI-generated code directly in the terminal environment.