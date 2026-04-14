# Skill Exec: Deploy App

## Objective
Act as `@devops` to package the application, install dependencies, and launch the server.

## Execution Steps
1. **Stack_Detection**: Inspect files in `app_build/` to identify the tech stack.
2. **Install_Dependencies**: Navigate to `app_build/` and run the native terminal command (e.g., `npm install`, `composer install`, or `pip install -r requirements.txt`).
3. **Host_Locally**: Execute the start command (e.g., `npm run dev`, `php spark serve`, or `python app.py`).
4. **Report_Success**: Output the exact, clickable localhost URL to the user.
