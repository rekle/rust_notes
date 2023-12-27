# Rust Notes

Notes on using the Rust Programming language

## Installing Rust

1. Website: https://www.rust-lang.org
2. Install Rust: https://www.rust-lang.org/tools/install
    1. macOS or Linux:
        1. curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
    2. Windows
       1. Download the appropriate installer for Windows
3. Restart terminal window

## Checking Rust Version
1. rustc --version
2. cargo --version

## Updating existing Rust
1. rustup update

## Setting up Rust in Visual Studio Code

### Initial Setup for Rust Debugging in VS Code (macOS and Windows)

1. Install 'rust-analyzer' VS Code Extension
2. Install 'CodeLLDB' VS Code Extension.

### Creating a new Rust Project
1. Run 'cargo new <project_name>' from Terminal to create new Rust Project

### Enabling Debug in a Rust Project 

1. Run 'code <project_name>' from Terminal to open that project in VS Code
2. Click on Run & Debug tab in VS Code
3. Click on "Show all automatic debug configurations"
4. Click on "Add configuration" in dropdown.
5. Choose 'LLDB'
6. Click 'Yes' on the dialog box that pops up.
7. This will generate a new '.vscode/launch.json' file which will allow debugging.
8. Set any breakpoints you need in the source.
9. Go to the Run & Debug tab on VS Code.
10. Click the Green arrow on the top to start running.

## Links

### Rust Language

* [Rust Language Website](https://www.rust-lang.org)
* [The Rust Programming Language Book](https://doc.rust-lang.org/book/) - Online book documenting the Rust Language
* [The Cargo Book](https://doc.rust-lang.org/stable/cargo/) - Online book describing Cargo (the Rust build system)
* [Online Rust Langage Compiler](https://play.rust-lang.org) - Online Rust compiler for learning Rust without having to install it.
* [Rust Books](https://rust-lang.org/learn)

### Training

* [Rustlings](https://github.com/rust-lang/rustlings) - A series of short Rust programs used to test your knowledge of various Rust concepts.
* [Cheat Sheet](https://cheats.rs/) - A cheat sheet documenting many Rust features and links to explanations of them in the documentation.
* [Rust by Example](https://doc.rust-lang.org/rust-by-example/) - A series of small Rust programs that explain different Rust features
* [Read Rust](https://readrust.net) A collection of links to various articles about Rust
* [No Boilerplate](https://www.youtube.com/@NoBoilerplate) - Youtube channel with various short videos on Rust
* [Faster Than Lime]https://fasterthanli.me_ - Blog with many articles on learning Rust
* [No Boilerplate Discord](https://noboilerplate.org/discord)
* [The Little Book of Rust Macros](https://danielkeep.github.io/tlborm/book/index.html)

### Using

* [Instructions for setting up Rust in VS Code](https://code.visualstudio.com/docs/languages/rust)
* [Community Support](https://www.rust-;ang.org/community)

### Libraries

* [Rocket.RS](https://rocket.rs) - Rust-based web framework 
