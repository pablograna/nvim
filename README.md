# Personal nvim configuration

Installed nvim from downloaded tgz.
Built nvim-qt from sources -> Stopped using, high CPU.

Instead, I created ~/bin/v with the folling content:

gnome-terminal -- nvim "$@"

Cloned ~/.config/nvim from git@github.com:LazyVim/starter.git to ~/.config/nvim.

To clean up everything (almost):
rm -rf /home/pablo/.local/share/nvim /home/pablo/.local/state/nvim ~/.cache/nvim/

Using DejaVuSansMono from https://www.nerdfonts.com/font-downloads. You must
restart the gnome terminal by killing gnome-terminal-server after installing.

To install the font:

cd ~/fonts/
unzip ~/.config/nvim/DejaVuSansMono.zip


