# BetPro

Sports bet tracking application

## Installation

## Usage

## Building from source

### Prerequisites

#### Windows

- [Tauri Dependencies](https://tauri.app/v1/guides/getting-started/prerequisites#setting-up-windows)
- [Rust >= 1.56.0](https://rustup.rs/)
- [Node.js v18.x.x](https://nodejs.org/)

#### Linux

- [Tauri Dependencies](https://tauri.app/v1/guides/getting-started/prerequisites#setting-up-linux)
- rust
- nodejs
- libsqlite3-dev (Debian/Ubuntu) or sqlite-devel (Fedora) or sqlite (Arch)

#### macOS

WARNING: I don't have a Mac so this is completely untested

- [Tauri Dependencies](https://tauri.app/v1/guides/getting-started/prerequisites#setting-up-macos)
- [Rust >= 1.56.0](https://rustup.rs/)
- [Node.js v18.x.x](https://nodejs.org/)

#### Diesel

```shell
cargo install --no-default-features --features "sqlite"
```

Using bundled sqlite. On windows installing shared libraries can be a pain so you can use the bundled libraries instead.

```shell
cargo install --no-default-features --features "sqlite-bundled"
```

#### Building

```shell
yarn install
yarn tauri build
```
