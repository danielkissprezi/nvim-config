# Frenetiq NeoVim settings

## Install (Windows)

- Install neovim
- clone into your nvim directory (AppData/Local/nvim on Windows) `git clone https://github.com/snorrwe/nvim-config.git` 
- Init venv `virtualenv python3`
- Install the `neovim` package
    ```
    python3/Scripts/activate
    pip install neovim
    ```
- Install plugins in vim `:PlugInstall`
- Install [libclang](https://github.com/djp952/external-libclang)
- Install [YouCompleteMe](https://github.com/Valloric/YouCompleteMe)
- Install RustFMT `rustup component add rustfmt-preview`
- Edit `init.vim` to your liking. Be sure to edit __HOME__ and __LLVM__
- Profit

