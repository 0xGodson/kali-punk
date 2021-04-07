![main-logo](https://github.com/jopraveen/kali-punk/blob/main/assets/main-logo.png) <br><br>

<p align="center">
  <img src="https://img.shields.io/badge/Maintained%3F-Yes-green?style=for-the-badge">
  <img src="https://img.shields.io/github/license/jopraveen/kali-punk?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/jopraveen/kali-punk?style=for-the-badge">
  <img src="https://img.shields.io/github/issues/jopraveen/kali-punk?color=violet&style=for-the-badge">
  <img src="https://img.shields.io/github/forks/jopraveen/kali-punk?color=teal&style=for-the-badge">
</p>

<h2 align="center">i3 rice Inspired by Cyberpunk 2077 (still under construction)</h2> <br>


<details>
<summary>👈 Dependencies</summary> <br>

<!--Ok The headache starts here-->

  <details>
  <summary>i3</summary> <br>

  ```bash
  sudo apt install i3
  ```
  </details>

  <details>
  <summary>polybar</summary> <br>

  ```bash
  sudo apt install polybar
  ```
  </details>

  <details>
  <summary>zsh</summary> <br>

  ```bash
  sudo apt install zsh
  chsh -s $(which zsh)
  ```
  </details>

  <details>
  <summary>oh-my-zsh</summary> <br>

  ```bash
  sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

  git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

  git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

  chsh -s $(which zsh)
  ```

  ## Any errors?
  ### Read this: https://techdhee.in/how-to-install-zsh-in-kali-linux/#How_To_Install_ZSH_in_Kali_Linux
  </details>

  <details>
  <summary>mate-terminal</summary> <br>

  ```bash
  sudo apt install mate-terminal
  ```

  #### ok now go to profile preferences and change these things (in mate-terminal) 🙂
  + General    
      + Font: Monospace Regular 
      + Font Size: 9
      + Uncheck [Show menubar by default in new terminals]

  + Colors
      + Foreground, Background, Bold and Underline
          + Build-in schemes: Custom
          + Text color: #E30A7D
          + Bold color: #F809B7
          + Background color: #020429
      + Palette
          + Build-in schemes: Solarized

  + Background

      + Tansparent Background : set 68% transparency

  </details>

  <details>
  <summary>compton</summary> <br>

  ```bash
  sudo apt install compton
  ```
  </details>

  <details>
  <summary>feh</summary> <br>

  ```bash
  sudo apt install feh
  ```
  </details>

  <details>
  <summary>neofetch</summary> <br>

  ```bash
  sudo apt install neofetch
  ```
  </details>

  <details>
  <summary>brave-browser</summary> <br>

  ```bash
  sudo apt install brave-browser
  ```
  </details>

  <details>
  <summary>w3m</summary> <br>

  ```bash
  sudo apt install w3m
  ```
  </details>

  <details>
  <summary>i3-gaps</summary> <br>

  ```bash
  sudo apt  install i3-gaps 
  ```
  </details>

  <details>
  <summary>ranger</summary> <br>

  ```bash
  sudo apt install ranger 
  ```
  </details>

  <details>
  <summary>rofi</summary> <br>

  ```bash
  sudo apt install rofi 
  ```
  </details>
  
  <details>
  <summary>wallset</summary> <br>

  ```bash
  git clone https://github.com/terroo/wallset
  cd wallset
  sudo bash install.sh
  ```
  ### The installer says that a package is not installed, but are you sure it is?
  ```bash
  sudo ./install.sh --force
  ```
  </details>
  
  <details>
  <summary>term-clock</summary> <br>

  ```bash
  git clone https://github.com/Souravgoswami/term-clock
  cd term-clock
  ```
  #### You can run this clock by `ruby term-clock.rb`
  </details>  
  
  <details>
  <summary>polybar-themes</summary> <br>

  ```bash
  git clone --depth=1 https://github.com/adi1090x/polybar-themes.git
  cd polybar-themes
  chmod +x setup.sh
  ./setup.sh
  ```
  
  ##### Ok now choose option 1 that's all
  
  </details>  
  
</details>



<!--Soon I'll upload i3wm kali linux files with cyberpunk rice
I'll upload a video in few days in my youtube channel (How to make tutorial video)
 subscribe to get instant notification: https://bit.ly/3rLKyZi -->
