# tauri-yew

```bash
# general update for ubuntu
sudo apt-get update -y
# tauri stuff
sudo apt-get install -y libwebkit2gtk-4.0-dev build-essential curl wget file libssl-dev libgtk-3-dev libayatana-appindicator3-dev librsvg2-dev

# get rust
sudo curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

# get node js
  # get nvm (Node Version Manager)
  # install latest lts node
  nvm install lts/hydrogen
  nvm use lts/hydrogen
  node -v 

# get tauri cli tool
cargo install create-tauri-app

# tauri cli support
cargo install tauri-cli
# webserver that recreates on demand
cargo install trunk

# wasm as target for rustc
rustup target add wasm32-unknown-unknown

```
