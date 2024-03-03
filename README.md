# Rust Notes

Notes on using the Rust Programming language

## Rust Playground

You can use the [Rust Playground](https://play.rust-lang.org/) to try Rust without installing it.

## Installing Rust

1. Website: https://www.rust-lang.org
2. Install Rust: https://www.rust-lang.org/tools/install
    1. macOS or Linux:
        1. curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
    2. Windows
       1. Download and run the appropriate rustup installer for Windows (32 bit or 64 bit)
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

## Basic CLI commands

|Command|Description|
|---|---|
| rustc file.rs | Compile the Rust code in the file 'file.rc' |
| rustc --explain E0308 | Explain a Rust error message, such as E0308 in this example |
| cargo run | Compile and run a debug version of the Rust project in the current folder |
| cargo build | Build a debug version of the Rust project in the current folder.  The executable will be in the file 'target/debug/PROJECT_NAME' |
| cargo build --release | Build a release version of the Rust project in the current folder.  The executable will be in the file 'target/release/PROJECT_NAME' |
| cargo check | Checks to see if your Rust program will compile without generating an executable |
| cargo new PROJECT_NAME | Create a new Rust project named PROJECT_NAME in a folder called PROJECT_NAME under the current folder |

## Common Files

|File|Description|
|---|---|
| Cargo.toml | Project file containing configuration settings |
| main.rs | Main file of the project.  Execution starts here in the main() function. |
| target/debug/PROJECT_NAME | Name of debug executable for the project named PROJECT_NAME (append .exe for Windows) |
| target/release/PROJECT_NAME | Name of release executable for the project named PROJECT_NAME (append .exe for Windows) |


## Links

### Rust Language

* [Rust Language Website](https://www.rust-lang.org)
* [The Rust Programming Language Book](https://doc.rust-lang.org/book/) - Online book documenting the Rust Language
* [The Cargo Book](https://doc.rust-lang.org/stable/cargo/) - Online book describing Cargo (the Rust build system)
* [Online Rust Langage Compiler](https://play.rust-lang.org) - Online Rust compiler for learning Rust without having to install it.
* [Rust Books](https://rust-lang.org/learn)
* [TOML - Tom's Obvious Minimal Language](https://toml.io/en/) - The Rust config file language (usually in the project root in a file called 'Cargo.toml')

### Training

* [Rustlings](https://github.com/rust-lang/rustlings) - A series of short Rust programs used to test your knowledge of various Rust concepts.
* [Cheat Sheet](https://cheats.rs/) - A cheat sheet documenting many Rust features and links to explanations of them in the documentation.
* [Rust by Example](https://doc.rust-lang.org/rust-by-example/) - A series of small Rust programs that explain different Rust features
* [Read Rust](https://readrust.net) A collection of links to various articles about Rust
* [No Boilerplate](https://www.youtube.com/@NoBoilerplate) - Youtube channel with various short videos on Rust
* [Faster Than Lime](https://fasterthanli.me) - Blog with many articles on learning Rust
* [No Boilerplate Discord](https://noboilerplate.org/discord)
* [The Little Book of Rust Macros](https://danielkeep.github.io/tlborm/book/index.html)
* [Advent of Code](https://adventofcode.com/) - A series of programming exercises.  It's not Rust specific but can be used for any language.

### Using

* [Instructions for setting up Rust in VS Code](https://code.visualstudio.com/docs/languages/rust)
* [Community Support](https://www.rust-;ang.org/community)

### Libraries

* [Rocket.RS](https://rocket.rs) - Rust-based web framework 
