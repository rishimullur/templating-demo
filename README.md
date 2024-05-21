# templating-demo

This is a simple page that demonstrates the use of a base template (`_base.html`) and a child template (`index.html`) that extends the base template.

## Prerequisites

- Python 3.x
- Flask

## Installation

1. Clone the repository:
2. Navigate to the project directory:
3. Install flask incase it is not installed

## Usage

1. Run the Flask app
```
python app.py
```
2. Open your web browser and visit `http://localhost:5000` to view the personal homepage.

## Project Structure

- `app.py`: The main Flask application file that defines the route and renders the `index.html` template.
- `templates/`: This directory contains the HTML templates for the project.
  - `_base.html`: The base template that defines the overall structure of the web pages.
  - `index.html`: The child template that extends the `_base.html` template and provides the content for the personal homepage.
- `requirements.txt`: A file that lists the required Python packages for the project.
- `README.md`: This file, providing an overview and instructions for the project.

## Customization

You can customize the HTML templates (`_base.html` and `index.html`) to suit your needs. The `_base.html` template can be used to define common elements across multiple pages, such as a header, footer, or navigation menu. The `index.html` template can be used to define the content specific to your homepage.
