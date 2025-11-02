# JavaDecompiler 🛠️

![JavaDecompiler](https://img.shields.io/badge/JavaDecompiler-v1.0.0-blue.svg)  
[Download Latest Release](https://github.com/dzanaimamovic/JavaDecompiler/releases)  

## Overview

JavaDecompiler is a multi-threaded Java batch decompiler tool based on the Vineflower engine. It allows you to quickly process large numbers of `.class` files and `.jar` files. This tool is designed for developers who need to analyze Java bytecode efficiently and effectively.

## Features

- **Multi-threading**: Process multiple files simultaneously to save time.
- **Batch Processing**: Decompile many files at once, ideal for large projects.
- **User-friendly Interface**: Simple commands and options for ease of use.
- **Supports Various Formats**: Handle both `.class` and `.jar` files seamlessly.

## Getting Started

To get started with JavaDecompiler, you need to download the latest release. You can find it [here](https://github.com/dzanaimamovic/JavaDecompiler/releases). Download the file and execute it to start using the tool.

### Prerequisites

- **Java JDK**: Ensure you have Java JDK installed on your machine. You can download it from the [official site](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).
- **Operating System**: This tool works on Windows, macOS, and Linux.

### Installation

1. Download the latest release from the [Releases page](https://github.com/dzanaimamovic/JavaDecompiler/releases).
2. Extract the downloaded file to your desired location.
3. Open your terminal or command prompt.
4. Navigate to the extracted folder.
5. Run the following command to start the decompiler:

   ```bash
   java -jar JavaDecompiler.jar
   ```

## Usage

### Basic Commands

After launching the application, you can use the following commands to decompile your files:

- **Decompile a Single File**:

  ```bash
  java -jar JavaDecompiler.jar decompile path/to/yourfile.class
  ```

- **Decompile a JAR File**:

  ```bash
  java -jar JavaDecompiler.jar decompile path/to/yourfile.jar
  ```

- **Batch Decompile**:

  To decompile multiple files, use:

  ```bash
  java -jar JavaDecompiler.jar batch path/to/directory
  ```

### Options

You can customize your decompilation process with various options:

- `--output`: Specify the output directory for the decompiled files.
- `--verbose`: Enable detailed logging of the decompilation process.
- `--help`: Display the help message with all available commands.

## Example

Here’s an example of how to decompile a JAR file:

1. Download the JAR file you want to decompile.
2. Use the following command:

   ```bash
   java -jar JavaDecompiler.jar decompile myproject.jar --output ./decompiled
   ```

This command will decompile `myproject.jar` and save the output in the `./decompiled` directory.

## Troubleshooting

If you encounter issues while using JavaDecompiler, consider the following steps:

- **Check Java Version**: Ensure you are using a compatible version of Java JDK.
- **File Paths**: Verify that the file paths you provide are correct.
- **Permissions**: Make sure you have the necessary permissions to read the files.

For further assistance, please check the [Issues section](https://github.com/dzanaimamovic/JavaDecompiler/issues) on GitHub.

## Contributing

We welcome contributions to JavaDecompiler! If you have suggestions or improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your fork.
5. Create a pull request.

## License

JavaDecompiler is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Community

Join our community to discuss features, share tips, and get help:

- **GitHub Discussions**: Engage with other users and contributors.
- **Social Media**: Follow us on Twitter and LinkedIn for updates.

## Acknowledgments

JavaDecompiler is built on the Vineflower engine, which provides the core decompilation functionality. We appreciate the hard work of the Vineflower team and the open-source community.

## Conclusion

JavaDecompiler is a powerful tool for anyone working with Java bytecode. Its multi-threaded capabilities and batch processing make it an efficient choice for developers. Don’t forget to download the latest release from the [Releases page](https://github.com/dzanaimamovic/JavaDecompiler/releases) and start decompiling your Java files today!

![JavaDecompiler](https://img.shields.io/badge/JavaDecompiler-v1.0.0-blue.svg)  
[Download Latest Release](https://github.com/dzanaimamovic/JavaDecompiler/releases)