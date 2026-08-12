# Note Sharing Django Project

## Project Overview
This is a collaborative Django-based web application designed to facilitate the sharing and management of notes. The platform allows users to upload, share, and manage notes while interacting through features like comments and tags.

## Features
- **User Authentication**: Register, login, and manage user accounts.
- **Note Management**: Upload, edit, and delete notes with file support.
- **Search Functionality**: Search notes by title or tags.
- **Media Handling**: Manage user-uploaded files in the `media` directory.
- **Database**: Preconfigured with SQLite for quick setup.

## Project Structure
```
project/
├── .idea/                  # IDE configuration files
├── db.sqlite3              # SQLite database file
├── manage.py               # Django management script
├── media/                  # Directory for uploaded files
├── notes/                  # Notes app containing views, models, and templates
├── NotesSharingProject/    # Main project folder with settings and URLs
```

## Installation and Setup

### Prerequisites
- Python 3.8+
- Django 4.0+

### Steps
1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd project
   ```
3. **Create a Virtual Environment**:
   ```bash
   python -m venv env
   source env/bin/activate   # On Windows: env\Scripts\activate
   ```
4. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
5. **Apply Migrations**:
   ```bash
   python manage.py migrate
   ```
6. **Run the Development Server**:
   ```bash
   python manage.py runserver
   ```
   Access the application at `http://127.0.0.1:8000/`.

## Usage
1. Register a new account or log in using an existing account.
2. Upload notes and manage them via the user dashboard.
3. Use the search feature to find relevant notes.
4. Download or interact with shared notes.

## Contribution Guidelines
We welcome contributions to improve this project! To contribute:
1. Fork this repository.
2. Create a new branch for your changes:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request on GitHub.



## Team Members
- **[Member 1]**: Abdul Aziz
- **[Member 2]**: Md.Tanvir Hasan Rafi
- **[Member 3]**: Maruf Khan
- **[Member 4]**: Md.Sariful Islam




