# Hello World CLI in Rust
## Description
This is a simple CLI that prints "Hello, World!", written in Rust. While this is basic, it serves as a way for me to create a README and learn the basics of building a Rust project, while also playing around with basic Git commands.

## Explanation
- `src` is the directory for the source code.
- `.gitignore` is a list of every directory/files that won't be pushed to GitHub.
- `Cargo.toml` contains basic information about the project.
- `Cargo.lock` is maintained by Cargo and pins down dependencies exact version. Should not be edited.

## Installation
a. You can get this by simply running `cargo new hello-world`. This will create a directory with the name `hello-world`, which has the same file content. Move to the directory with `cd hello-world`, run `cargo build`, and lastly `cargo run` to run the main file.

b. Or, the GitHub way:
1. Clone this repo
```
git clone https://github.com/irevle/hello-world-rust
```
2. Move to the directory
```
cd hello-world-rust
```
3. Compile/build the project. This should create `target` folder.
```
cargo build
```
4. Run the compiled project.
```
cargo run
```
