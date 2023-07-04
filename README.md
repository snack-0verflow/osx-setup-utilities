# Setting up new OSX machine

## 👌 Handy helpers

<details>
  <summary>Brew</summary>
  
  ### Installation
  ```sh
  # https://brew.sh/
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  ```

  ### Cask taps
  ```sh
  # You only need to do this once!
  brew tap homebrew/cask
  brew tap homebrew/cask-fonts
  ```

  ### Formulae
  ```sh
  tmux
  iterm2
  exa
  fonttools
  font-roboto
  font-roboto-mono
  font-roboto-mono-nerd-font
  font-roboto-for-powerline
  visual-studio-code
  android-studio
  ```
</details>


<details>
  <summary>Terminal</summary>
  
  ### Tmux setup (Oh my tmux)
  - [Oh my tmux](https://github.com/gpakosz/.tmux)
  - [Ayu iTerm2 theme](https://github.com/hwyncho/ayu-iTerm)

</details>

<details>
  <summary>Git & SSH</summary>
  
  ### Helper
  ```sh
  EMAIL=cheuk-man.ng@ledger.fr
  git config --global user.name "Chuck Ng"
  git config --global user.email "$EMAIL"
  ssh-keygen -t ed25519 -C "$EMAIL"
  ```

  ### Aliases
  ```sh
  alias tw="tmux new -n workspaces -s"
  ```

</details>