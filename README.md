# File Fingerprint
![GitHub](https://img.shields.io/github/license/korayustundag/file-fingerprint)

File Fingerprint is an open-source console application developed in C# .NET 7. It allows you to calculate MD5, SHA-1, SHA256, SHA384, and SHA512 hashes for files. The program is currently available for Windows and Linux, with upcoming support for MacOS.
## Features
- Calculate MD5, SHA-1, SHA256, SHA384, and SHA512 hashes for files
- Option to save the hash values to a file
- Cross-platform support (Windows, Linux)
## Usage
### Windows
    ff.exe [-h | --help] <file path 1> <file path 2> ... <file path n>
### Linux
    ./ff [-h | --help] <file path 1> <file path 2> ... <file path n>
Use the above commands to run the File Fingerprint program on your respective operating systems.
## Build from Source
To build and run the File Fingerprint program from source, follow these steps:
1. Clone the repository: `git clone https://github.com/korayustundag/file-fingerprint.git`
2. Navigate to the project directory: `cd file-fingerprint`
3. Build the project: `dotnet build`
4. Publish for Windows: `dotnet publish -r win-x64 -c Release --self-contained false`
5. Publish for Linux: `dotnet publish -r linux-x64 -c Release --self-contained false`

Make sure you have .NET 7 SDK installed on your machine before building and running the project.
## License
File Fingerprint is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
