# Setup

**Note** Inspired by https://github.com/dreamsofcode-io/tmux

```shell
# Install tmux
sudo apt install tmux
# Install tpm - tmux package manager
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
# copy the config file
cp tmux.conf ~/.config/tmux/
# Reload new config
tmux source ~/.config/tmux/tmux.conf
