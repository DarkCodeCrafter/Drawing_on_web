# Drawing Application with Flask

This is a simple web-based drawing application built using Flask, HTML, CSS, and JavaScript. Users can draw on a canvas, select different colors, clear the canvas, and download their drawings as images.

## Features
- 🎨 **Draw on a canvas** using the mouse
- 🌈 **Change brush colors** (Black, Red, Blue, Yellow, Green)
- 🧹 **Clear the canvas**
- 📥 **Download the drawing as a PNG image**

## Installation & Setup
### Prerequisites
Ensure you have **Python 3** installed.

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/DarkCodeCrafter/drawing-app-flask.git
cd drawing-app-flask
```

### 2️⃣ Install Dependencies
Create a virtual environment and install the required packages:
```sh
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install flask pillow
```

### 3️⃣ Run the Application
```sh
python app.py
```
The app will run on **http://127.0.0.1:5000/**.

## Project Structure
```
.
├── static/
│   ├── style.css  # Styles for the UI
│   ├── script.js  # JavaScript logic
│   └── drawing.png  # Saved drawings (generated dynamically)
├── templates/
│   └── index.html  # Frontend UI
├── app.py  # Flask backend
├── README.md  # Project documentation
```

## API Endpoints
| Route  | Method | Description |
|--------|--------|-------------|
| `/` | GET | Load the drawing page |
| `/save` | POST | Save and download the drawing |

## Usage
1. Open the web application.
2. Use the mouse to draw on the canvas.
3. Click color buttons to change the brush color.
4. Click **Clear** to reset the canvas.
5. Click **Download** to save your drawing.

💡 **Built with Flask & Love ❤️**

