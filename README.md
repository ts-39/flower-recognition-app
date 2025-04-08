# Flower Recognition App

This project is a web-based application designed to recognize and classify different types of flowers from user-uploaded images. It leverages machine learning techniques to provide accurate predictions.

## Features

- **Image Upload**: Users can upload images of flowers through the web interface.
- **Flower Classification**: The application processes the uploaded image and predicts the type of flower.
- **Web Interface**: A user-friendly web interface built with Django allows seamless interaction.

## Prerequisites

Before setting up the project, ensure you have the following installed:

- Python 3.x
- pip (Python package installer)

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/ts-39/flower.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd flower
   ```

3. **Install Required Packages**:

   All necessary packages are listed in the `requirements.txt` file. Install them using:

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply Migrations**:

   Set up the database by applying migrations:

   ```bash
   python manage.py migrate
   ```

5. **Run the Development Server**:

   Start the Django development server:

   ```bash
   python manage.py runserver
   ```

   The application will be accessible at `http://127.0.0.1:8000/`.

## Usage

1. **Access the Web Interface**:

   Open your browser and navigate to `http://127.0.0.1:8000/`.

2. **Upload an Image**:

   Use the provided upload feature to select and upload an image of a flower.

3. **View Prediction**:

   Once uploaded, the application will process the image and display the predicted flower type.

## Project Structure

- **flower/**: Contains the main application code, including models, views, and templates.
- **mysite/**: The project configuration directory, containing settings and URLs.
- **media/**: Directory where uploaded images are stored.
- **manage.py**: Django's command-line utility for administrative tasks.
- **requirements.txt**: Lists the Python packages required for the project.

## Contributing

Contributions are welcome! If you'd like to improve this project, please fork the repository and submit a pull request.
