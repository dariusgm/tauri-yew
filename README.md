# Tauri + Yew

This template should help get you started developing with Tauri and Yew.

Install "create-tauri-app" for generating a different template.
```bash
# general update for ubuntu
sudo apt-get update -y
# tauri stuff
sudo apt-get install -y libwebkit2gtk-4.0-dev build-essential curl wget file libssl-dev libgtk-3-dev libayatana-appindicator3-dev librsvg2-dev

# get rust
sudo curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

# get node, in case you want to use the node ecosystem
  # get nvm (Node Version Manager)
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
  # install latest lts node
  nvm install lts/hydrogen
  nvm use lts/hydrogen
  node -v 

# get template generator app. When using this template, its not needed.
cargo install create-tauri-app

# tauri cli support
cargo install tauri-cli
# webserver that recreates on demand
cargo install trunk

# wasm as target for rustc
rustup target add wasm32-unknown-unknown
```

# development
Run the following commands in the root of the project to start the development server.
```bash
cargo tauri dev
```
