# Building a Data Analysis & Visualisation Web App

A Django-based web application that allows users to upload a CSV file, analyze the data using Pandas, and visualize the results using ChartJS.

## Technologies Used

- **Python** – Core programming language  
- **Django** – Web framework for building the app  
- **Pandas** – Data analysis and manipulation  
- **ChartJS** – Data visualization in the browser  

## Project Description

This project demonstrates how to build a full-stack data analytics and visualization web app from scratch using Python and Django.

The application allows users to:
- Upload a CSV file in a predefined format
- Parse and analyze the data using Pandas
- Display the data in a tabular format on a webpage
- Generate and visualize charts using ChartJS

Throughout the project, you'll go through the typical software development process:
1. Start by reading a Software Requirements Specification (SRS) document that outlines client expectations.
2. Set up the development environment and install Django.
3. Learn the basics of Django, including views, templates, and models.
4. Implement CSV file handling and convert the file content into a Pandas DataFrame.
5. Perform data analysis and pass the results to the frontend.
6. Render visualizations with ChartJS for a dynamic user experience.

This project is a great example of integrating multiple technologies to create a complete, interactive web application.


## Installation


### Prerequisites

- Python 3.7 or higher
- Node.js (version 14 or higher recommended)
- pip (Python package manager)
- npm (comes with Node.js)

### Setup Steps

```bash
# Clone the repository
git clone https://github.com/your-username/data-analysis-visualization-app.git
cd data-analysis-visualization-app

# Create and activate virtual environment
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

# Install Python dependencies
pip install -r requirements.txt

# Install front-end dependencies
npm install

# Run Django migrations and start the server
python manage.py migrate
python manage.py runserver
```

To run this project locally:

```bash
# Clone the repository
git clone https://github.com/your-username/data-analysis-visualization-app.git
cd data-analysis-visualization-app

# Create and activate virtual environment
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations and start the server
python manage.py migrate
python manage.py runserver
```



## Usage

1. Open your browser and go to `http://127.0.0.1:8000/hello/`.
2. Upload a CSV file using the upload form.
3. View the parsed data in a table.
4. Scroll down to see interactive charts generated from the data.



## Features

- CSV upload functionality
- Data table display using Django templates
- Interactive charts with ChartJS
- Clean separation of logic and presentation using Django's MVC pattern
- Real-world development flow using a mock SRS document


## Contributing

Contributions are welcome.  
If you’d like to improve this project, please fork the repo and submit a pull request.  
For major changes, open an issue first to discuss what you’d like to update.
