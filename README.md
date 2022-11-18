# Rust Notes

Notes on using the Rust Programming language

## Installing Rust

1. Website: https://www.rust-lang.org
2. Install Rust: https://www.rust-lang.org/tools/install
    1. macOS or Linux:
        1. curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
3. Restart terminal window

## Checking Rust Version
1. rustc --version
2. cargo --version

## Updating existing Rust
1. rustup update

## Setting up Rust in Visual Studio Code

### Initial Setup for Rust Debugging in VS Code

1. Install 'rust-analyzer' VS Code Extension
2. Install 'CodeLLDB' VS Code Extension (for MacOS) or 'Microsoft C++' VS Code Extension for Windows

### Enabling Debug in a Rust Project 

1. Run 'cargo new <project_name>' from Terminal to create new Rust Project
2. Run 'code <project_name>' from Terminal to open that project in VS Code
3. Click on Run & Debug tab in VS Code
4. Click on "Show all automatic debug configurations"
5. Click on "Add configuration" in dropdown.
6. Choose 'LLDB'
7. Click 'Yes' on the dialog box that pops up.
8. This will generate a new '.vscode/launch.json' file which will allow debugging.
9. Set any breakpoints you need in the source.
10. Go to the Run & Debug tab on VS Code.
11. Click the Green arrow on the top to start running.

# Links

* [Rust Language Website](https://www.rust-lang.org)
* [The Rust Programming Language Book](https://doc.rust-lang.org/book/)
* [The Cargo Book](https://doc.rust-lang.org/stable/cargo/)
* [Instructions for setting up in VS Code](https://code.visualstudio.com/docs/languages/rust)
* [Online Rust Langage Compiler](https://play.rust-lang.org)
