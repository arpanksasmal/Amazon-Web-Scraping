# Amazon Web Scraper

This project utilizes Flask and Beautiful Soup to create a web application for scraping Amazon product information based on user input. It fetches data like product descriptions, prices, and ratings, and presents it in a user-friendly format.

## Features

- **Search Amazon Products:** Users can input product names to search for on Amazon.
- **Scraping:** The application scrapes Amazon's website for product information such as description, price, and rating.
- **Presentation:** Retrieved data is presented in a tabular format with clickable links to the respective product pages on Amazon.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.8 or higher installed on your local machine.
- Install the required Python packages using `pip install -r requirements.txt`.

## Usage

1. Run the Flask application by executing `python app.py`.
2. Open your web browser and navigate to `http://localhost:5000`.
3. Enter the name of the product you want to search for in the input field.
4. Click the "Find" button to initiate the search.
5. The application will display a table with the product descriptions, prices, ratings, and clickable links to the Amazon product pages.

## File Structure

- `app.py`: Contains the Flask application code for handling HTTP requests and rendering templates.
- `templates/index.html`: HTML template for the web interface.
- `static/style.css`: CSS stylesheet for styling the web interface.
- `requirements.txt`: Text file listing the required Python packages for installation.

## Deployment

To deploy this project on a web server, follow these steps:

1. Ensure the server environment meets the prerequisites.
2. Clone this repository to the server.
3. Install the required Python packages using `pip install -r requirements.txt`.
4. Set up a web server (e.g., Nginx, Apache) and configure it to serve the Flask application.
5. Start the application using a production-ready WSGI server like Gunicorn: `gunicorn app:app`.

## Credits

- This project was created by Arpan Kumar Sasmal.
- Inspired by - Online tutorials and documentation.
- Guidance from ChatGPT.


