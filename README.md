Vim colors and vimrc/init.vim for vim/neovim

# How to use
## Windows
### Using colors
Paste colors folder to `C:\Program Files(x86)\Vim`  or inside `C:\tools\neovim\Neovim\share\nvim\runtime\` OR 
`C:\Program Files\Neovim\share\nvim\runtime` in case of neovim

If you can't find Vim in `Program Files(x86)`, check in `Program Files` it maybe that you have installed 64 bit vim.

### Using vimrc/init.vim
Paste `.vimrc` in `C:\Program Files(x86)\Vim` <br />
Rename .vimrc to _vimrc<br />
**Note: windows uses _vimrc and Linux/Mac uses .vimrc**

In case of neovim paste the init.vim file into `C:\Users\YOUR_USERNAME\AppData\Local\nvim\`

## Linux/Mac
### Using colors
Paste the colors folder into `/usr/share/vim/vim*/` <br />
vim* is your version of vim, in my case it's vim81 so my path looks like this: `/usr/share/vim/vim81/` <br />
You can cd into that path easily by using the command `cd /usr/share/vim/vim*/` on your terminal <br />

For neovim, paste the colors folder into `~/.config/nvim/`

### Using vimrc/init.vim
Paste the `.vimrc` file contents into `~/.vimrc` <br />
If you don't see any .vimrc, just create a new file in your home directory(~/) <br />

Paste the `init.vim` file inside `~/.config/nvim/` folder <br />
If there is no .config folder just create one, and inside it create nvim folder and inside that put your init.vim file.
