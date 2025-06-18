# Bcrypt Tool

A simple, modern web tool for generating and verifying bcrypt hashes directly in your browser. No backend or server required—everything runs locally using JavaScript and the [`bcrypt.js`](https://github.com/dcodeIO/bcrypt.js) library.

## Features

- **Generate bcrypt hashes:**  
  Enter any string (e.g., a password) and adjust the salt rounds (cost factor) to generate a secure bcrypt hash.
- **Verify hashes:**  
  Check if a plain text string matches a given bcrypt hash using instant client-side comparison.
- **Modern, responsive UI:**  
  Designed with a clean, user-friendly interface that works great on both desktop and mobile.
- **Clipboard support:**  
  Easily copy generated hashes to your clipboard with a single click.

## Demo

Open the `index.html` file in your browser—no installation or dependencies required.

![Screenshot of the bcrypt-tool UI](screenshot.png) <!-- Add a screenshot if available -->

## How to Use

1. **Clone or download this repository.**
2. **Open `index.html` in your web browser.**

### Generate Hash

- Go to the **Generate Hash** tab.
- Enter the text you want to hash.
- (Optional) Adjust the salt rounds (default is 10; higher is more secure but slower).
- Click **Generate Hash**.
- Copy the resulting hash with the copy button.

### Compare Hash

- Go to the **Compare Hash** tab.
- Enter the original plain text and the bcrypt hash to compare.
- Click **Compare** to see if they match.

## Technology

- **HTML, CSS, JavaScript (ES6)**
- [bcrypt.js](https://github.com/dcodeIO/bcrypt.js) (loaded via CDN)

## Security & Limitations

- **All operations happen locally** in your browser; no data is sent to any server.
- For real-world password management, always use secure practices and vetted libraries in your production backend.

## License

This project is open source. See [LICENSE](LICENSE) for details.

---

> Created by [@Mrutyunjay-Patil](https://github.com/Mrutyunjay-Patil)
