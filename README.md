# 📁 Express File Upload API with Multer

A simple file upload API built using Express.js and Multer. It allows users to upload files to a specified directory on the server. The file is stored with a unique name using a timestamp and the original extension.

---

## 🚀 Features

- 🗂 Upload any type of file (images, PDFs, etc.)
- 📂 Save files in a custom directory (from `.env`)
- 📄 Returns file metadata: name, type, and size
- 🔐 Environment-based config using `dotenv`

---

## 📦 Requirements

- Node.js
- Express
- Multer
- dotenv

Install dependencies:

```bash
npm install express multer dotenv
