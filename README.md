Task 3 – Multi-Service Architecture on AWS (Frontend + Backend) 
 **2 AWS services**:
- A **Frontend website** using Amazon S3
- A **Backend API** using EC2 (with Python Flask)
  
 Frontend (S3 Website)
- Created an S3 bucket `task-3-frontend`
- Enabled static website hosting
- Uploaded `index.html` with a button that calls backend
- 

🔹 Backend (EC2 Flask API)
- Launched an EC2 instance (Ubuntu, t2.micro)
- Installed Flask using `sudo apt install python3-flask`
- Created `app.py` returning: “Hello from EC2 Backend!”
- Allowed HTTP traffic on port 80
- 

🔹 Connected Frontend to Backend
- `index.html` sends a fetch request to EC2’s public IP
- Flask API responds with a message

Tools Used
Amazon S3 (Static hosting)
Amazon EC2 (Backend server)
Python Flask (Web framework)
HTML + JavaScript

