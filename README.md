**🔐 Secure File Encryption Web App | AES-256-GCM Implementation**

------------

**🌟 Overview**
A lightweight, browser-based file encryption tool using AES-256-GCM for secure file protection. Works completely offline - no server communication required! Perfect for keeping your sensitive files safe with military-grade encryption.

**✨ Key Features**
- 🔒 AES-256-GCM encryption (industry standard)
- 💻 100% client-side processing
- 🌐 Offline compatible - works without internet
- 🎯 Zero server dependencies
- 📦 Handles files of any type
- 🔑 Password-based key derivation (PBKDF2)
- 📊 Real-time progress tracking
- ⚡ Fast processing with optimized code
- 🛡️ Secure salt and IV handling



###  **🚀 How It Works**

------------


1. **Encryption Process:**

- Generates cryptographically secure random salt and IV
- Derives encryption key using PBKDF2
- Encrypts file data using AES-256-GCM
- Packages salt, IV, and encrypted data
- Auto-downloads the encrypted file


2. **Decryption Process:**

- Extracts salt and IV from encrypted file
- Reconstructs encryption key using provided password
- Decrypts data using AES-256-GCM
- Auto-downloads the original file

------------



**💻 Usage**

- Simply open index.html in any modern browser
- Select file & enter password for encryption
- Use same password to decrypt the file later

**🔧 Technical Details**

- **Implementation:** Pure JavaScript
- **Encryption:** AES-256-GCM
- **Key Derivation: **PBKDF2
- **File Processing:** Single-block handling
- **Browser Support: **All modern browsers

**🛡️ Security Features**

- **No data transmission **- everything stays on your device
- Secure random number generation
- Strong key derivation function
- Authenticated encryption mode (GCM)
- Zero data persistence

**⚠️ Important Notes**


- **Keep your password safe** - no recovery possible
- **Works offline **- save the HTML file for portable use
- Recommended for modern browsers only
- Large files may take longer to process

**📝 License**

------------


MIT License - Feel free to use, modify, and distribute!



***Note: This is a client-side tool. Your files never leave your browser. Always keep backups of important files and passwords.***
