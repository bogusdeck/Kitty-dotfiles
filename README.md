# Kitty Terminal Configuration

![screenshot (1)](https://github.com/Prome-theus/Kitty-dotfiles/assets/80052733/a6abe5ad-6903-4e60-808d-64272d321fb2)


This repository contains my personal configuration for the Kitty terminal emulator, tailored to enhance my development workflow and make the terminal experience more enjoyable. Kitty is a fast, feature-rich, GPU-accelerated terminal emulator.

## Installation

1. **Install Kitty Terminal:**

   If you haven't installed Kitty yet, follow the [official installation instructions](https://sw.kovidgoyal.net/kitty/#id4).

2. **Clone this Repository:**

   ```bash
   git clone https://github.com/Prome-theus/Kitty-dotfiles
   ```

3. **Copy Configuration Files:**

   Navigate to the cloned directory and copy the configuration files to the appropriate locations:

   ```bash
   cp kitty.conf ~/.config/kitty/
   cp tanish.omp.json ~/.config/kitty
   ```

4. **Restart Kitty Terminal:**

   Restart the Kitty terminal for the changes to take effect.

5. **Install OMP(OH_MY_POSH):**
   
   [installation guide OMP](https://ohmyposh.dev/docs/installation/linux)

   for arch linux :
   ```bash
   yay -S oh-my-posh
   ```
   for windows
   ```powershell
   winget install JanDeDobbeleer.OhMyPosh -s winget
   ```
   
6. **Install fonts:(optional)**

   [VictorMono Nerd Font.](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.1.1/VictorMono.zip)

7. **Activate Oh-my-posh :**

   ```bash
   oh-my-posh init
   ```
   than install font
   ```bash
   oh-my-posh font install
   ```
   select VictorMono nerd font

8. **Copy the config files:**

   ```bash
   cp -f config.fish ~/.config/fish/
   ```

---

Enjoy using the Kitty terminal with this configuration! If you find it helpful, don't forget to give it a star. Happy coding! 🚀
