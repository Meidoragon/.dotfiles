[PACKAGE LIST]
# list of commands to get up and running to a similar level to what I want
$PACKAGE_MANAGER install rustup { pkgconf | pkg-config }
rustup default {stable | nightly}
cargo install sccache
$PACKAGE_MANAGER install alacritty cargo github-cli neovim nushell rustup starship stow ttf-mononoki-nerd vim zellij 
