# food-detection

### Frontend Setup:

Install Dependencies: In the frontend/ folder, they need to run the following command to install the required dependencies:

cd frontend
npm install


This should start the app on their machine, typically accessible at http://localhost:3000.

### Backend Setup:
Create a Virtual Environment (Optional but recommended): In the backend/ folder, they should create and activate a Python virtual environment:

cd backend
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

Install Dependencies: Next, they need to install the required Python packages. In the backend/ folder, they should run:

pip install -r requirements.txt

### Run the Backend: They can now run the backend server with:
uvicorn main:app --reload
### Run the Frontend: To start the frontend server, they can run:
npm run dev

This will start the backend server, typically accessible at http://localhost:8000
