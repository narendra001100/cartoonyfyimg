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

![Screenshot (1)](https://github.com/narendra001100/cartoonyfyimg/assets/168404066/f1719fa1-e31a-46a5-a82f-5bf9da47c41e)
![Screenshot (2)](https://github.com/narendra001100/cartoonyfyimg/assets/168404066/212236ed-0aea-4650-9210-336f9b1819f2)

![Screenshot (3)](https://github.com/narendra001100/cartoonyfyimg/assets/168404066/61bcb8a1-09e8-4169-b109-441504242843)

![Screenshot (4)](https://github.com/narendra001100/cartoonyfyimg/assets/168404066/37e509f8-9c98-461e-ab93-046229066ff9)

![Screenshot (5)](https://github.com/narendra001100/cartoonyfyimg/assets/168404066/19b7dc69-a3d7-4030-8504-7add6b8cea6f)

![Screenshot (6)](https://github.com/narendra001100/cartoonyfyimg/assets/168404066/73cd522a-878a-449e-834a-c8f8402c5cbe)

![Screenshot (7)](https://github.com/narendra001100/cartoonyfyimg/assets/168404066/f496d0cf-8d01-448f-9ad9-bf7cb5978f99)







- The application uses OpenCV for image processing and Flask for serving the web interface.
- Various cartoonization styles are implemented using different OpenCV functions.
- When an image is uploaded and a style is selected, the corresponding cartoonization function is called, and the resulting cartoonized image is displayed to the user.

## Credits

This project was created by [Narendra,Piyush,HArsh,Jayram].


