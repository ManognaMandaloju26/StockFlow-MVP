# StockFlow MVP — Inventory Management System

StockFlow MVP is a web-based inventory management application built using Python and Flask. It provides a simple interface for managing product information and organizing inventory records.

## 🚀 Features

- **User Authentication:** Register and log in to access the application.
- **Product Management:** Add and manage product details.
- **SKU Identification:** Assign unique Stock Keeping Units (SKUs) to products.
- **Product Descriptions:** Store descriptions for inventory items.
- **Dashboard:** Access inventory information through a web interface.
- **Web-Based Application:** Run locally in a web browser.

## 🛠️ Technologies Used

- Python
- Flask
- HTML
- CSS
- JavaScript
- SQLite (if configured in the application)

## 📂 Project Structure

```text
StockFlow-MVP/
├── app.py
├── requirements.txt
├── Procfile
├── README.md
├── .gitignore
├── static/
└── templates/
```

## ⚙️ Installation and Setup

### Prerequisites

- Python 3.10 or a compatible Python version
- pip
- Git (optional, for cloning the repository)

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/StockFlow-MVP.git
cd StockFlow-MVP
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Create a virtual environment

**Windows PowerShell:**

```powershell
py -m venv .venv
```

### 3. Activate the environment

```powershell
.\.venv\Scripts\Activate.ps1
```

### 4. Install dependencies

```powershell
python -m pip install -r requirements.txt
```

### 5. Run the application

```powershell
python app.py
```

### 6. Open in your browser

Open the local URL displayed in the terminal. For example:

```text
http://127.0.0.1:5000
```

The exact address and port depend on the application's configuration.

## 📋 How to Use

1. Start the application.
2. Register a user account if registration is available.
3. Log in to the application.
4. Open the product or inventory section.
5. Enter a product name, unique SKU, and description.
6. Save the product and review the inventory information.

## 🔧 Troubleshooting

**Missing dependencies**

```powershell
python -m pip install -r requirements.txt
```

**Port already in use**

Stop the other application using the same port, or configure StockFlow to use a different available port.

**Application does not start**

Check the terminal output for errors and confirm that you are running the command from the folder containing `app.py`.

## 🔐 Security Notes

- Do not upload passwords, API keys, or other secrets to GitHub.
- Keep your virtual environment out of version control.
- Use secure password handling and a strong secret key before deploying the application publicly.
- Do not store sensitive inventory or customer information in a publicly accessible database.

## 🌐 Deployment

The application can be deployed to a compatible Python hosting platform, such as Render, after configuring the required dependencies, start command, environment variables, and database storage.

A public GitHub repository does not automatically create a live application URL. The deployed URL should be added here after deployment.

**Live URL:** To be added after successful deployment.

## 👩‍💻 Author

**Manogna Mandaloju**

B.Tech — Information Technology

## ⚠️ Project Status

Minimum Viable Product (MVP) — features and deployment should be tested before production use.

## 📄 License

No license has been specified. Add a license if you intend to permit others to use, modify, or distribute this project.
