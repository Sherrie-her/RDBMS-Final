# RDBMS-Final
# Emo-Quiz

Emo-Quiz is an interactive application designed to help users learn and practice emoji meanings across multiple languages. Through various game modes and study tools, users can enhance their understanding of emoji usage in different cultural contexts.

## Features

### Study Mode
- **My Responses**: Track your learning progress
- **Story Mode**: Create stories using emoji combinations
- **Writing Mode**: Practice describing emojis in different languages
- **Flashcard Mode**: Study emoji meanings with interactive flashcards

### Practice Mode
- Multiple difficulty levels (Easy/Intermediate/Hard)
- Category-based learning
- Progress tracking
- Performance feedback

### Challenge Mode
- Time-based survival mode
- High score system
- Progressive difficulty
- Multi-language support

### Profile Features
- Performance tracking
- Wrong answer review
- Global rankings
- Learning history

## Requirements

### System Requirements
- Python 3.x
- MySQL Database
- tkinter
- PIL (Python Imaging Library)
- mysql-connector-python

### Database Setup
1. Install MySQL Server
2. Create a database named 'rdbmsfinal'
3. Configure database connection in the code:
```python
host="localhost"
user="root"
password="your_password"
database="rdbmsfinal"
```

### Required Python Packages
```bash
pip install mysql-connector-python
pip install pillow
pip install tkmacosx  # For MacOS users
```

## Installation

1. Clone the repository:
```bash
git clone [repository-url]
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Set up the database:
   - Run the provided SQL scripts to create necessary tables
   - Import initial emoji data

4. Update the image directory path in the code:
```python
self.image_dir = "path/to/your/emoji/images"
```

## Usage

1. Run the application:
```bash
python writingclass.team_gui_all-ver9.py
```

2. First-time users:
   - Enter a nickname
   - Select preferred language
   - Create new account

3. Returning users:
   - Enter existing nickname
   - System will load previous progress

## File Structure

```
project/
│
├── writingclass.team_gui_all-ver9.py    # Main application file
│
├── twemoji_final_png/                   # Emoji image directory
│   ├── twemoji_1.png
│   ├── twemoji_2.png
│   └── ...
│
└── database/                            # Database scripts and data
    ├── schema.sql
    └── initial_data.sql
```

## Database Schema

- user: User information and high scores
- emoji_basic: Basic emoji information
- emoji_description: Multi-language descriptions
- game_log: Game performance tracking
- practice_log: Practice session data
- my_responses: User response history

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## Known Issues

- Path settings may need adjustment based on operating system
- Some fonts might not be available on all systems
- Database connection requires local MySQL server

## Future Improvements

- Add more languages
- Implement additional game modes
- Enhance user interface
- Add multiplayer features
- Improve performance tracking

## Credits

- Emoji images: [Source]
- Font resources: [Source]
- Database design: [Team Members]

## License

[Your chosen license]

## Contact

For support or queries, please contact: [Your Contact Information]
