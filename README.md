# SecureCodeBox Unix CLI

This Unix CLI script facilitates the creation of scans for SecureCodeBox, focusing on nmap scanning. SecureCodeBox is an open-source tool suite for continuous automated security testing.

## Prerequisites

Ensure you have the following prerequisites installed on your system:

- Bash
- SecureCodeBox

## Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/your_username/securecodebox-cli.git
    ```

2. Navigate to the directory:

    ```bash
    cd securecodebox-cli
    ```

3. Make the script executable:

    ```bash
    chmod +x scbctl.sh
    ```

## Usage

To use the CLI, follow these steps:

1. Run the script:

    ```bash
    ./scbctl.sh
    ```

2. You will be prompted with `secureCodeBox\CLI:`. Enter the following command to create a new scan:

    ```bash
    scbctl create scan nmap <URL>
    ```

    Replace `<URL>` with the target URL you want to scan.

3. Wait for the scan to be created. You'll receive a confirmation message once the scan is created in the `scans` folder.

4. To exit the CLI, type:

    ```bash
    exit
    ```

## Example

```bash
./scbctl.sh
secureCodeBox\CLI: scbctl create scan nmap example.com
```

## Contributing

Contributions are welcome! Feel free to open issues or pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- This CLI script is a part of the GSOC 24 OWASP SecureCodeBox project.
- Special thanks to the contributors and maintainers of SecureCodeBox.
