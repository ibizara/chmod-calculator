# Chmod Calculator

A feature-rich chmod calculator that allows you to explore and configure Unix file permissions. This tool supports:
- Standard permissions (Read, Write, Execute)
- Special permissions: SUID, SGID, and Sticky Bit
- Various file types: Regular file, Directory, Symbolic Link, Named Pipe, Socket, Block Device, Character Device, and External Link
- Dynamic updates between text representation, numeric values, and checkboxes

## Live Preview
Check out the live preview of the chmod calculator here:
[Live Demo](https://ibizara.github.io/chmod-calculator/chmod-calculator.html)

## Features
- **Real-time Sync**: Updates between numeric values, text-based permissions, and checkboxes in real-time.
- **Error Handling**: Provides detailed error messages for invalid inputs.
- **Example Command Generator**: Automatically generates an example `chmod` command based on your selections.
- **User-Friendly Interface**: Intuitive layout for easy use.

## How to Use
1. Select a **File Type** (e.g., Regular File, Directory).
2. Set permissions using:
   - **Checkboxes** for Read, Write, Execute, and Special permissions.
   - **Numeric values** for `Owner`, `Group`, `Other`, and `Special`.
   - **Text-based permission string** (e.g., `-rwxr-xrwx`).
3. The tool will:
   - Dynamically update all fields.
   - Generate an example `chmod` command below.

## Development
To run this project locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/ibizara/chmod-calculator.git
   ```
2. Open `chmod-calculator.html` in your browser:
   ```bash
   open chmod-calculator.html
   # Or on Windows:
   start chmod-calculator.html
   ```

## Contributing
Contributions are welcome! If you encounter any issues or have suggestions, please open an [issue](https://github.com/ibizara/chmod-calculator/issues) or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
