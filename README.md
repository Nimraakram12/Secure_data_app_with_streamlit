## SecureData 🔒

A secure data storage application built with Streamlit and PostgreSQL, designed to encrypt and store sensitive information using AES-256 encryption. 

---

## Features ✨
- **🔐 Encryption**: Data is encrypted with a user-provided passkey before storage.
- **🗄️ Secure Storage**: Encrypted data stored in a PostgreSQL database (hosted on Neon.tech).
- **🔍 Data Retrieval**: Decrypt stored data using the correct passkey.
- **👤 User Authentication**: Login/logout functionality via Streamlit session state.
- **🧂 Salt Generation**: Unique salt per encryption for enhanced security.

## Usage 🖥️
# Store Data:

Enter your sensitive data (text).

Provide a strong passkey.

Click "Encrypt and Save" (data encrypted and stored in DB).

Retrieve Data:

Navigate to the retrieval page.

Enter the correct passkey to decrypt data.

Logout:

Session-based authentication ensures data access only for logged-in users.
