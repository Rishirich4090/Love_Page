# Project Setup and Run Instructions

This project is a simple static website consisting of HTML, CSS, and JavaScript files.

## Running the Project

### Option 1: Open in Browser Directly
1. Navigate to the project directory.
2. Open the `index.html` file in your preferred web browser by double-clicking it or right-clicking and selecting "Open with".

### Option 2: Serve with a Simple HTTP Server (Recommended for full functionality)
Serving the project via a local HTTP server can help avoid issues with some browser security restrictions.

#### Using Python (if installed)
1. Open a terminal or command prompt.
2. Navigate to the project directory.
3. Run the following command:

For Python 3.x:
```bash
python -m http.server 8000
```

For Python 2.x:
```bash
python -m SimpleHTTPServer 8000
```

4. Open your browser and go to `http://localhost:8000`.

#### Using VS Code Live Server Extension
1. Install the Live Server extension in VS Code.
2. Open the project folder in VS Code.
3. Right-click on `index.html` and select "Open with Live Server".

## Project Structure

- `index.html` - Main entry point of the website.
- `style.css` - Stylesheet for the website.
- `script.js` - JavaScript functionality.
- Other HTML files (`no1.html`, `no2.html`, `no3.html`, `yes.html`) - Additional pages.

## Notes

- No additional setup or dependencies are required.
- You can modify the HTML, CSS, and JS files to customize the website.
