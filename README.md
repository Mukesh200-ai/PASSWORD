# PASSWORD
IT IS A SMALL PROJECT THAT STORES PASSWORD IN YOUR LOCAL STORAGE
# Password Manager

A simple and secure desktop-based Password Manager built using Python's Tkinter library. It allows users to generate strong passwords, store them locally in a JSON file, and retrieve them when needed. This tool is ideal for personal use.

## Features

- 🔐 **Generate Strong Passwords**
- 💾 **Save website/email/password securely in a local JSON file**
- 🔍 **Search functionality to retrieve stored credentials**
- 📋 **Clipboard copy for generated passwords**
- 🖥️ **User-friendly GUI built with Tkinter**

## Getting Started

### Prerequisites

- Python 3.x
- `pyperclip` module

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/password-manager.git
cd password-manager
```

2. Install dependencies:

```bash
pip install pyperclip
```

3. Run the application:

```bash
python main.py
```

Make sure `logo.png` is in the directory for the GUI. You can replace or remove that part from the code if needed.

## File Structure

```
password-manager/
├── main.py          # Main application file
├── data.json        # Password storage (auto-created)
├── logo.png         # Logo image for GUI
└── README.md        # Project documentation
```

## Security Notes

- This project stores passwords in plain text. Do **not** use it for sensitive or production-level data.
- You can enhance the security by encrypting the JSON file with libraries like `cryptography`.

## Possible Improvements

- [ ] Add encryption
- [ ] Add password visibility toggle
- [ ] Export feature (CSV or encrypted backup)

## License

This project is licensed under the [MIT License](LICENSE).

---

> Contributions and suggestions are welcome!
