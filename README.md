# Articles App

A simple Python application to manage articles, authors, and magazines using SQLite.

## Features

- Create, update, and query articles, authors, and magazines.
- Enforces relationships between articles, authors, and magazines.
- Uses SQLite for data storage.
- Includes tests for core functionality.

## Project Structure

```
lib/
  db/
    connection.py
    schema.sql
  models/
    article.py
    author.py
    magazine.py
scripts/
  setup_db.py
tests/
  test_article.py
  test_author.py
  test_magazine.py
README.md
```

## Setup

1. **Clone the repository**  
   ```
   git clone <repo-url>
   cd Articles-App
   ```

2. **Set up the database**  
   ```
   python3 scripts/setup_db.py
   ```

3. **Install dependencies**  
   This project uses only the Python standard library. For testing, install `pytest`:
   ```
   pip install pytest
   ```

## Usage

- Models for `Author`, `Magazine`, and `Article` are in `lib/models/`.
- Run tests with:
  ```
  pytest
  ```

## Database Schema

- See `lib/db/schema.sql` for table definitions.

## License

MIT License

