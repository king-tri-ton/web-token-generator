# Web Token Generator

## Description

This is a simple application for generating web tokens, providing convenient access through the system tray. The application is written in Python and uses the pystray, pyperclip, and Pillow libraries.

## Installation

1. Clone the repository:

   ```bash
   https://github.com/king-tri-ton/web-token-generator.git
   ```

2. Navigate to the project directory:

   ```bash
   cd web-token-generator
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the script:

   ```bash
   python token_generator.py
   ```

2. An icon will appear in the system tray.

3. Right-click on the icon to display the context menu.

4. Select "Copy" to copy the new web token to the clipboard.

5. Select "Exit" to close the application.

## Usage Examples

- **Development and Testing:**
  Use it for quick generation of test web tokens during the development and debugging of web applications.

- **Integration with Web Services and APIs:**
  A convenient way to create temporary tokens for authentication when working with web services and APIs.

- **Security Testing:**
  A helper in security testing for generating various tokens.

- **Education and Training:**
  Useful for education and practical exercises where the use of web tokens is required.

## Dependencies

- Python 3.x
- pystray
- pyperclip
- Pillow

## License

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License.
