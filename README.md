# Stardew Valley Icon Theme

A Stardew Valley themed file icon pack for VS Code!
Currently for common front-end web development file types.

![Bar](/resources/Bar.png)
![Overview](/resources/Overview.png)

## Installation

### From a VSIX file
1. Generate a VSIX file:
   ```
   vsce package
   ```
2. Install the generated file (use the filename `vsce` produced):
   ```
   code --install-extension <generated-file>.vsix
   ```

### From source (local folder)
1. Symlink this folder into your VS Code extensions directory:
   ```
   ln -s /path/to/this-repo ~/.vscode/extensions/stardew-valley-icon-theme
   ```
2. Reload VS Code (`Cmd+Shift+P` / `Ctrl+Shift+P` → `Developer: Reload Window`)

## Enabling the theme
After installing:
1. Open the Command Palette (`Cmd+Shift+P` / `Ctrl+Shift+P`)
2. Run `Preferences: File Icon Theme`
3. Select **Stardew Valley**
4. If the icons don't update right away, run `Developer: Reload Window`

## Resources
Forked from https://github.com/klyap/vscode-stardew-icon-theme

Icons from https://stardewvalleywiki.com/Stardew_Valley_Wiki
