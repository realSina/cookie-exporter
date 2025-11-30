# Cookie Exporter Chrome Extension

A Chrome Extension to export cookies from any website in multiple formats, including JSON, Netscape, and Cookie Header. This extension allows you to download cookies with a single click, making it useful for web developers, testers, and anyone working with browser cookies for automation or debugging.

## Features

- Export cookies in **JSON** format.
- Export cookies in **Netscape HTTP Cookie File** format.
- Export cookies as a **Cookie Header** for easy usage in curl or PHP.
- Simple and user-friendly interface.
- Supports any website you're currently visiting.

## Installation

1. Download or clone this repository to your local machine.
2. Open `Chrome` and go to `chrome://extensions/`.
3. Enable **Developer Mode** (top-right corner).
4. Click on **Load unpacked**.
5. Select the directory where you downloaded/cloned the repository.
6. The extension will be installed and visible in the Chrome toolbar.

## Usage

1. Click on the extension icon in your Chrome toolbar.
2. A popup window will appear with three options:
   - **Export as JSON**: Save the cookies in JSON format.
   - **Export as Netscape**: Save the cookies in Netscape HTTP Cookie File format.
   - **Export as Cookie Header**: Save the cookies as a Cookie Header string.
3. The cookies of the currently active website will be exported to a file of your choice.

## File Formats

### 1. **JSON Format**
The exported JSON file will contain all cookies for the domain, structured in a readable way. This format is useful for developers or tools that work with JSON.

### 2. **Netscape HTTP Cookie File**
This format is commonly used by tools like `curl`. The file will be formatted according to the Netscape cookie standard.

### 3. **Cookie Header**
The Cookie Header format can be used directly in curl requests or PHP scripts.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, feel free to fork the repository, create a branch, and submit a pull request.

### Steps to contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Create a new pull request.

## License

This project is open source and available under the [MIT License](LICENSE).
