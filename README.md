# vscode-setup-guide

My personal setup guide to use VSCode 🤫

## Topics

- [vscode-setup-guide](#vscode-setup-guide)
  - [Topics](#topics)
  - [Appearance 🎨](#appearance-)
  - [Extensions 🎲](#extensions-)
  - [Personal Tips/Tricks 📙](#personal-tipstricks-)

## Appearance 🎨

Themes

- [Aura](https://marketplace.visualstudio.com/items?itemName=DaltonMenezes.aura-theme)
- [Night Owl](https://marketplace.visualstudio.com/items?itemName=sdras.night-owl)
- [Atom One Dark](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-theme-onedark)

Icon Themes

- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

Fonts

- [Fira Code](https://github.com/tonsky/FiraCode/wiki/VS-Code-Instructions)

## Extensions 🎲

- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Turbo Consol Log](https://marketplace.visualstudio.com/items?itemName=ChakrounAnas.turbo-console-log)
- [Tab Out](https://marketplace.visualstudio.com/items?itemName=albert.TabOut)
- [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
- [Remote Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- [Remote SSH](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)
- [SSH: Editing Configuration Files](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh-edit)
- [GistPad](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.gistfs)
- [BlockMan](https://marketplace.visualstudio.com/items?itemName=leodevbro.blockman)
  ```
  // add these in setting.json
  "blockman.n33A01B1FromDepth0ToInwardForAllBorders": "200,0,0,1; none",
  "blockman.n33A01B2FromDepth0ToInwardForAllBackgrounds": "200,0,0,1; none",
  "blockman.n33A05B2FromFocusToInwardForAllBackgrounds": "250,0,0,1; rgb(5, 5, 23)"
  ```

### Personal Tips/Tricks 📙

- Use `code -r .` to open the folder in current window.
  _When you `cd` into any directory and do `code .` VSCode opens the folder in separate window_
- If you have bigger display, you can use,
  ```
    "workbench.editor.wrapTabs": true
  ```
  to have windows stacked up rather than be hidden
