# 👌 Handy helpers for new OSX machine

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
  brew tap wix/brew
  ```

  ### Formulae
  ```sh
  brew install tmux \
  iterm2 \
  exa \
  bat \
  glow \
  pgp \
  neovim \
  fonttools \
  font-roboto \
  font-roboto-mono \
  font-roboto-mono-nerd-font \
  font-roboto-for-powerline \
  android-studio \
  visual-studio-code \
  flipper \
  nvm \
  rectangle \
  applesimutils
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
  EMAIL=name@example.com
  git config --global user.name "Chuck Ng"
  git config --global user.email "$EMAIL"
  ssh-keygen -t ed25519 -C "$EMAIL"
  ```

  ### Aliases
  ```sh
  alias tw="tmux new -n workspaces -s"
  alias ls="exa --long --group --all --git"
  alias cat="bat"
  ```

  - [Create PGP Key](https://docs.github.com/en/authentication/managing-commit-signature-verification/generating-a-new-gpg-key)
  - [Configure Git to use PGP Key](https://docs.github.com/en/authentication/managing-commit-signature-verification/telling-git-about-your-signing-key)

</details>


<details>
   <summary>asdf</summary>
   
   - [Home Page](https://asdf-vm.com/)

   ### Installation scripts
   ```sh
   brew install coreutils curl git
   git clone https://github.com/asdf-vm/asdf.git ~/.asdf --branch v0.12.0
   ```
</details>
