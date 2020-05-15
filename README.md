# BashProfile
Bash Profile for my Mac.

# Install Oh My SH

- Ensure zsh is installed on your terminal.
`which zsh`

- Install oh my ZSH
Run `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

# Install iterm2
brew cask install iterm2

# Download the edited* common ZSH theme
- Download file to `/.oh-my-zsh/custom/themes`
- `curl -O https://raw.githubusercontent.com/zipzapzup/BashProfile/master/common_profile_edited.zsh_theme`
- `vi ~/.zshrc`
- Change `ZSH_THEME="common_profile_edited"`
