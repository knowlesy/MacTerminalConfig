# MacTerminalConfig
Configuring your Mac Terminal to look a smidge better  

[Video Guide (Not my own)](https://youtu.be/wNQpDWLs4To?si=Cw3WTgKQzMZfuRxj)

## What You will need to install 
[iterm2 Console](https://iterm2.com/)

[iterm2 ColourScheme](https://iterm2colorschemes.com/)

[ohMyZsh](https://ohmyz.sh/)

[Additional Fonts](https://www.nerdfonts.com/)

[powerlevel10k](https://github.com/romkatv/powerlevel10k)

[zsh Syntax Highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)

[zsh Auto Suggestions](https://github.com/zsh-users/zsh-autosuggestions)

[colorls](https://github.com/athityakumar/colorls#installation)

passing in kubctl commands to zsh 

```
source <(kubectl completion zsh)  # set up autocomplete in zsh into the current shell
echo '[[ $commands[kubectl] ]] && source <(kubectl completion zsh)' >> ~/.zshrc # add autocomplete permanently to your zsh shell
```
