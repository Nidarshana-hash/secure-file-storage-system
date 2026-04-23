# Secure-File-Storage-and-Sharing

A secure web application built using Flask and MongoDB that enables users to upload, store, and share files with strong encryption and strict access control. The system ensures data confidentiality by allowing only authorized users to access and decrypt files.

# Technologies Used:
Backend: Flask (Python)
Database: MongoDB
Encryption: AES (CBC mode), PBKDF2 key derivation
Frontend: HTML, CSS, JavaScript
Utilities: Flask Sessions, werkzeug.security
Deployment: Flask Development Server

# Key Features:
User Authentication: Secure login and registration with hashed passwords
File Upload & Encryption: Files encrypted using AES before storage
File Decryption & Download: Access files with correct password
Secure Sharing: Controlled file sharing between users
Access Control & Notifications: Approval-based access with notifications
File Re-encryption: Files re-encrypted for the recipient
Security: Strong encryption with AES and PBKDF2

# Challenges Addressed:
Secure File Handling: Protected storage using encryption
User Access Control: Restricted access to authorized users only
Notification Management: Efficient handling of access requests

# Project Outcomes:
Built a secure platform for file upload and sharing
Ensured confidentiality with encryption and password protection
Improved user control with an access request system

# Database:
used mongoDB database to store:
    1.user credentials
    2.uploaded files
    3.encrypted file passwords and credetials