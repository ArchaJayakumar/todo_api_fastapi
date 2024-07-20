# Simple To-Do API with FastAPI

A simple To-Do API built with FastAPI.

## Setup

Follow these steps to set up and run the project:

```sh
# Clone the repository
git clone https://github.com/ArchaJayakumar/todo-api-fastapi.git

# Navigate to the project directory
cd todo-api-fastapi

# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate

# Install dependencies
pip install fastapi uvicorn

# Run the project
uvicorn main:app --reload
