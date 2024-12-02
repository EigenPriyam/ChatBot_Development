# Chatbot Development Project

This project is a chatbot application with a backend built using Python FastAPI, a MySQL database, a Dialogflow integration for training phrases and intents, and a frontend website.

---

## Directory Structure
- **`backend/`**: Contains Python FastAPI backend code.
- **`db/`**: Contains the MySQL database dump. Import this into your database using MySQL Workbench.
- **`dialogflow_assets/`**: Includes Dialogflow training phrases, intents, and configurations.
- **`frontend/`**: Contains the website code for the chatbot.

---

## Prerequisites
Before starting, ensure you have the following installed:
- Python 3.8 or above
- MySQL database
- MySQL Workbench
- Ngrok (for HTTPS tunneling)

---

## Installation

### Install Required Python Modules
You can install the required Python dependencies using pip:

```bash
pip install mysql-connector
pip install "fastapi[all]"
