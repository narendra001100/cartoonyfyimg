# cartoonizer_flask_webapp

In this project we have build a Inage Stylization and Cartoonizer web app in Flask using Python and OpenCV. You only have to upload image you want to stylize and
select from the styles (Image enhancement, cartoon effect, pencil sketch, color pencil sketch, water color, pastel color) for transforming your image.

Sure, here's an updated README file for your project with instructions for setting up and running the application, as well as adding a requirements.txt file:

---

# Cartoonizer Web App

This is a Flask web application for cartoonizing images using various styles.

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/cartoonizer-web-app.git
   ```
2. Navigate to the project directory:
   ```
   cd cartoonizer-web-app
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the Flask application:
   ```
   python app.py
   ```
2. Open your web browser and go to [http://localhost:8080/](http://localhost:8080/) to access the application.

3. Upload an image and select a style from the dropdown menu.

4. Click the "Predict" button to see the cartoonized version of the uploaded image.

## Requirements

- Flask==2.1.0
- numpy==1.21.5
- opencv-python==4.5.4.58
- Werkzeug==2.0.2

Install these dependencies using pip:
```
pip install -r requirements.txt
```

## How it works

- The application uses OpenCV for image processing and Flask for serving the web interface.
- Various cartoonization styles are implemented using different OpenCV functions.
- When an image is uploaded and a style is selected, the corresponding cartoonization function is called, and the resulting cartoonized image is displayed to the user.

## Credits

This project was created by [Narendra,Piyush,HArsh,Jayram].


