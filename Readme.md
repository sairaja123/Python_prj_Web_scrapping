Project_Name : 2019_forbes_list_of_canada

1. Folder Structure

1.1 Overview
This project structure is designed for clarity and organization:

instance: Configuration file (if applicable).For storing sensitive information we used directory like API keys or database connection details.
templates: Contains HTML templates used by the Flask application (index.html and about.html).

forbes_database: Stores the database files related to companies.
python scrap: File responsible for web scraping to update the forbes_database.

run_app.py: The main backend file that initializes and runs the Flask application.

1.2 Example

plaintext
Copy code
/project_name
|-- instance
|   |-- config.py
|-- templates
|   |-- index.html
|   |-- about.html
|-- forbes_database
|   |-- forbes_database.db
|-- python scrap
|   |-- web_scraping.py
|-- run_app.py


2. Usage Instructions

2.1 Prerequisites

software should installed:

Python 3.x
Pip (Python package installer)
2.2 Database Initialization
Open a command prompt.

Navigate to the python scrap directory.

bash
Copy code
cd /path/to/project_name/python scrap
Now we have to execute the web scraping script to update the forbes_database.

bash
Copy code
python web_scraping.py
2.3 Running the Application
We have to open command prompt.

Then navigate to the project folder.

bash
Copy code
cd /path/to/project_name
Execute the Flask application.

bash
Copy code
python run_app.py
We have to open a web browser and go to http://localhost:5000 to access the application.

3. HTML Code
3.1 templates/index.html
(Your existing HTML code remains unchanged.)

4. Flask Code
4.1 run_app.py
(Your existing Flask code remains unchanged.)

5. Database Management
5.1 Scraping Data
Run the following command in the python scrap directory to uppdate the forbes_database

bash
Copy code
python web_scraping.py

