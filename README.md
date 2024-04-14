# getfile
Description getfile is a simple command-line tool that downloads files from a given URL to your current working directory. It uses libcurl for efficient downloading and is easy to use: simply provide the URL as an argument.


# getfile Tool

`getfile` is a command-line tool that allows you to download a file from a specified URL to your current working directory.

## Installation

To install the `getfile` tool, follow these steps:

1. Download or clone the `getfile` source code (`getfile.c`) and the installation script (`install.sh`) to your system.

2. Give execute permissions to the installation script:

    ```bash
    chmod +x install.sh
    ```

3. Run the installation script as root (or with `sudo`) to compile and install the `getfile` program to `/usr/local/bin`:

    ```bash
    sudo ./install.sh
    ```

The script will compile the `getfile` program and install it to `/usr/local/bin`, allowing you to use the program from any directory on your system.

## Usage

To use the `getfile` tool, open a terminal and run the following command:

```bash
getfile <URL>
```

Replace `<URL>` with the URL of the file you want to download.

For example, to download a file from `https://example.com/file.txt`, you would run:

```bash
getfile https://example.com/file.txt
```

The file will be downloaded to your current working directory.

## Troubleshooting

- **Permission Denied**: Ensure you are running the installation script as root (or with `sudo`) to install the program.

- **Compilation Failed**: Check the source code (`getfile.c`) for any errors or missing dependencies.

## Contact

For any issues or suggestions, please open an issue on the [GitHub repository](https://github.com/parodiq/getfile).

--- 
