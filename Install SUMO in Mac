# Install SUMO in Mac
---
Course AH2174/FAH3002 - Traffic Simulation Modeling and 
Applications   
Project I Assignment
Author: ZHIGUO ZHANG
Date: 11.05.2022

---
- Tutorial Reference links
  
  [Link1](https://sumo.dlr.de/docs/Installing/MacOS_Build.html)


  [Link2](https://sumo.dlr.de/docs/Installing/index.html#macos)


- Open terminal.app
- Install home brew
  ```
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
  ```
  ```
  brew update
  ```

- Install xcode
  ```
  xcode-select --install
  ```
  ```
  clang --version
  ```
- install dependencies
  ```
  brew install --cask xquartz
  brew install xerces-c fox proj gdal gl2ps
  ```
  ```
  brew install python swig eigen pygobject3 gtk+3 adwaita-icon-theme
  ```

- install SUMO
  ```
  brew tap dlr-ts/sumo
  brew install sumo
  ```

- Path 

  ```
  echo $SHELL 
  ```
  If the return is "/bin/zsh", then 
  ```
  open ~/.zshrc
  ```
  otherwise,the return is "/bin/bash",then
  ```
  open ~/.bashrc
  ```
  Just insert the following new line at the end of the file:
  ```
  export SUMO_HOME=/your path to/sumo
  ```
  you can get "your path to" in terminal after you have done the command "brew install sumo". For example,
  ```
  export SUMO_HOME=/opt/homebrew/opt/sumo/share/sumo
  ```

- install SUMO launchers
  
  download from [link](https://sumo.dlr.de/daily/SUMO_launchers.dmg)

  Then you got
  ![alt text](result.jpg "Title")


**P.S.** before open sumo-gui.app, make sure that the XQuartz is open or running in the background.
