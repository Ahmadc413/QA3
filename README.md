# QA3
- Create welcome screen with category selection functionality
- Develop complete quiz interface with question display and multiple-choice options
- Implement answer submission with immediate feedback
- Add score tracking and display system
- Create Question class for display and validation operations
- Implement error handling for database operations
- Follow OOP principles with proper documentation and comments


# Quiz Application

A Python-based quiz application featuring a Tkinter GUI and SQLite database. The application provides a user-friendly interface for taking quizzes across multiple categories, and includes an admin panel for managing quiz content.

 Features

 User Features
- **Welcome Screen**: Select from 5 different quiz categories
- **Interactive Quiz Interface**:
  - Multiple-choice questions with easy selection
  - Immediate feedback on answers
  - Real-time score tracking
- **Results Screen**: 
  - Final score with percentage calculation
  - Performance-based motivational message
  - Options to retry or choose another category

 Admin Features
- **Secure Login System**:
  - Password protection with SHA-256 encryption
  - Default credentials provided
- **Comprehensive Question Management**:
  - Add new questions to any category
  - View and edit existing questions
  - Delete questions from the database
  - Navigation between different admin functions

 Database Structure
- SQLite3 database (`quiz_data.db`) created automatically
- Separate tables for each quiz category (Math, Science, History, Literature, General Knowledge)
- Each category includes 10+ sample questions
- Admin credentials table with secure password storage

 Installation & Usage

 Requirements
- Python 3.x
- Tkinter (included in standard Python installation)
- SQLite3 (included in Python standard library)

### Running the Application
1. Clone this repository or download the source code
2. Navigate to the project directory
3. Run the application:
   ```
   python quiz_app.py
   ```

### Admin Access
To access the admin panel:
1. Click "Admin Login" on the welcome screen
2. Use the following default credentials:
   - **Username**: admin
   - **Password**: admin123

## Project Structure
- `quiz_app.py`: Main application file containing all code
- `quiz_data.db`: SQLite database file (created on first run)

## Implementation Details
- **GUI**: Created using Tkinter with a clean, user-friendly interface
- **Database**: SQLite3 for lightweight, serverless data storage
- **Security**: Password hashing using SHA-256
- **Navigation**: Intuitive flow between different screens

## Future Enhancements
- Timer functionality for timed quizzes
- User accounts and score history
- Additional question types (true/false, fill-in-the-blank)
- Statistics and reporting features
- Theme customization options

## License
This project is available for personal and educational use.

## Author 
Ahmad Capehart
