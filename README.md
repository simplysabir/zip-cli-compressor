
# ZIP CLI Compressor

## Introduction
ZIP CLI Compressor is a command-line interface tool built using Rust for efficiently compressing files into ZIP format. This tool simplifies the process of zipping files, offering a straightforward and fast solution for file compression needs.

## Features
- **CLI-Based:** Easy-to-use command-line interface for quick compression tasks.
- **File Compression:** Converts any file into a compressed ZIP format.
- **Rust-Powered:** Developed using Rust, ensuring fast and reliable performance.

## Installation and Setup

### Prerequisites
- Rust Programming Environment
- Basic knowledge of command-line operations and Rust

### Setting Up the Project
1. **Clone the Repository:**
   ```
   git clone https://github.com/simplysabir/zip-cli-compressor
   cd zip-cli-compressor
   ```

2. **Build the Project:**
   Use Rust's cargo build system to compile the project:
   ```
   cargo build --release
   ```
   This will create an executable in the `./target/release` directory.

## Usage
After building the project, use the following command format to compress files into ZIP format:

```
cargo run -- file_name.extension compressed_filename.zip
```

- `file_name.extension`: Replace this with the name and extension of the file you want to compress.
- `compressed_filename.zip`: Specify the desired name for the compressed output file.

## Contributions
Contributions to enhance or expand the ZIP CLI Compressor are welcome. If you have suggestions or improvements, feel free to fork the repository and submit a pull request. For significant changes, please open an issue first to discuss what you would like to change.

To explore more about my projects and contributions, visit [GitHub](https://github.com/simplysabir) or [Portfolio](https://simplysabir.live/).
