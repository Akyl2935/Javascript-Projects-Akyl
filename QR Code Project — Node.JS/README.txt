# QR Code Generator

## Project Overview

This project allows you to generate a QR code for a given URL using Node.js. The generated QR code is saved as a PNG image, and the input URL is stored in a text file.

## Author

- **Akyl Abdrakhmanov**

## Getting Started

1. **Clone the Repository:**

    ```bash
    git clone <repository_url>
    ```

2. **Navigate to the Project Folder:**

    ```bash
    cd <project_folder>
    ```

3. **Open Terminal:**

    Open your preferred terminal, for example, the Git terminal.

4. **Run the Application:**

    ```bash
    node index.js
    ```

5. **Enter URL:**

    Follow the prompt and enter the URL when prompted.

6. **Generated Files:**

    - The QR code image will be saved as `qr_image.png` in the project folder.
    - The entered URL will be saved in `URL.txt`.

## Dependencies

- [inquirer](https://www.npmjs.com/package/inquirer): For interactive command-line prompts.
- [qr-image](https://www.npmjs.com/package/qr-image): For generating QR codes.
- [fs](https://nodejs.org/api/fs.html): Node.js file system module.

## Usage Example

```bash
node index.js
# Enter the URL when prompted
