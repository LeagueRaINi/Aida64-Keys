![Windows/Ubuntu/MacOS](https://github.com/LeagueRaINi/Aida64-Keygen/workflows/Windows/Ubuntu/MacOS/badge.svg)

# **This is for educational purposes only!**
- this project contains methods for generating and verifying aida64 keys

## Build

### Debian/Ubuntu

```sh
# Dependencies
apt update
apt install pkg-config cmake build-essential libxcb-composite0-dev libfontconfig1-dev
curl https://sh.rustup.rs -sSf | sh

# Repository
git clone https://github.com/LeagueRaINi/Aida64-Keys.git

# Build
cd ./Aida64-Keys
cargo build --verbose
```

If you want to build a Windows exec in Debian/Ubuntu, continue with these steps

```sh
# Dependencies
apt install mingw-w64

# Build
rustup target add x86_64-pc-windows-gnu
cargo build --target x86_64-pc-windows-gnu
```

**Thanks to:**
- approved for helping reverse some of this
- wildbook & veykril for helping me a lot converting this to rust
- moonshadow565 for explaining and simplifying some of the methods