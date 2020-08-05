# Mesa-LLVM
Script for installing Mesa-git and LLVM-git on Ubuntu and Debian based distros.

# Running the script

# Speed up compilation
You can use ccache for compiling much faster than if you were using gcc or g++. In order to setup ccache you can run ccache.sh or type the following commands on terminal:
```
sudo apt install -y ccache
echo 'export PATH="/usr/lib/ccache:$PATH"' | sudo tee -a ~/.bashrc
sudo /usr/sbin/update-ccache-symlinks
```
