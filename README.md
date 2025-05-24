# Flet App Deployment on PythonAnywhere

This project is a Flet application prepared for deployment as a web app on PythonAnywhere.

## Setup

1. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Running the App Locally

Run the app with:
```bash
python main.py
```
This will start the Flet app in web browser mode.

## Deployment on PythonAnywhere

1. Upload your project files to PythonAnywhere.

2. Create a virtual environment and install dependencies as above.

3. Run the app using a console with:
   ```bash
   python main.py
   ```

4. The app will open in a web browser tab on PythonAnywhere.

## Notes

- The app is configured to run in web mode (`ft.app(target=main, view=ft.WEB_BROWSER)`).
- Window size settings have been removed as they are not applicable in web mode.
- All images are loaded via URLs, so no local static files are required.

For more information, see the [Flet documentation](https://flet.dev/docs/).
