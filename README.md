# HideIt: Sci-Fi Encrypt / Decrypt 💾🔒
hideIt is a next-generation, browser-based data encryption platform designed to secure your files using cutting-edge client-side cryptography. Upload any file—image, video, document, or archive—and transform it into a stream of mysterious, shareable symbols, secured by a unique, local key.

Absolute privacy is the core protocol. All encryption and decryption processes occur directly in your browser, ensuring zero server-side processing and zero data leakage.

Features
Client-Side Cryptography: Leverages the Web Crypto API for powerful, local encryption using AES-GCM-256. Your files never leave your device.

Unique Output Format: Encrypted data is converted into a stream of Sci-Fi Symbols (!@#$%^&*(), etc.) for easy copying and sharing.

Multi-File Support: Encrypt and decrypt multiple files simultaneously.

Key Management: Generates a secure .p8 key file for every encrypted data stream. This key is the only way to recover your original file.

Futuristic UI: A dynamic, neon-themed interface built with a subtle particle field and glass morphism for a cutting-edge user experience.

How It Works
Encrypt 🔐
Select one or more files (any format) to upload.

Click "Encrypt selected files."

The browser generates a unique AES-GCM-256 key and IV locally.

Your file data is encrypted and converted into the symbol text.

You receive two essential downloads:

The Symbol File (.txt): Contains the encrypted symbol stream. This can be safely shared or stored.

The Key File (.p8): Contains the necessary cryptographic key and IV. Keep this secret and safe.

Decrypt 🔓
Navigate to the Decrypt tab.

Upload the corresponding .p8 key file(s).

Upload the Symbol File(s) (.txt) or paste the symbol text directly into the input area.

Click "Decrypt uploaded files."

The browser uses the key to reverse the process, and your original file will be instantly available for download.

Technology Stack
HTML5

CSS3 (Custom Sci-Fi theme styling)

JavaScript (The core logic)

Web Crypto API: For all cryptographic operations (AES-GCM-256).

Canvas API: Used for the subtle, animated background particle field.

Setup and Development
Since this is a client-side application, you don't need a complex backend setup—just a local web server to run the files.

Prerequisites
You need a modern web browser that supports the Web Crypto API (Chrome, Firefox, Edge, Safari, etc.).

Local Installation
Clone the repository:

Bash

git clone https://github.com/Games-of-Ayaan/Hide-It.git
cd Hide-It
Run a local web server (using Python is the simplest):

Bash

python3 -m http.server 8000
Open your browser and navigate to http://localhost:8000 (or the port your server is running on).

Contributing
We welcome contributions! Whether you want to fix a bug, enhance the UI, or propose a new cryptographic feature, please feel free to fork the repository and submit a Pull Request.

Fork the Project.

Create your Feature Branch (git checkout -b feature/AmazingFeature).

Commit your Changes (git commit -m 'Add AmazingFeature' or a similar message).

Push to the Branch (git push origin feature/AmazingFeature).

Open a Pull Request.

Contact
Ayaan GameDev – gamedevayaan@gmail.com

Project Link: https://github.com/Games-of-Ayaan/Hide-It
