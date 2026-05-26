# Portfolio

## Running

Create the SQLite database from the schema and seed data:

    sqlite3 database/database.db < database/database.sql

To view the current project locally, run:

    php -S localhost:9000

Then open this link in the browser:

    http://localhost:9000

## Project Structure

```text
Portfolio/
├── actions/                  # Form handlers and session actions
├── css/                      # Stylesheets for the website
├── database/                 # SQLite schema, data and PHP DB helpers
├── images/                   # Images used in the pages
├── pages/                    # Public PHP pages
├── templates/                # Reusable PHP templates
├── README.md                 # Project overview and running instructions
└── .gitignore                # Git ignore rules
```
