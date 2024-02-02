## My Setup ArchLinux 


# configs and install 

$ sudo pacman -S zsh python git clang gcc gcc-libs meson 

# configs prompts 

# install 

# omz --> git : https://github.com/ohmyzsh/ohmyzsh.git

# website -> https://ohmyz.sh


# installer 

$ sh -c "$(wget https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"

# installing highlightings

$ git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

# activate 

# .zshrc edit file  add file element 

# $ plugins=(
#	 zsh-highlighting	
#)

# installing suggestions 
$  git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions


# edit .zshrc 

# $plugins=(
#	zsh-autosuggestions	
#)

# install spacevim 

$ https://spacevim.org

