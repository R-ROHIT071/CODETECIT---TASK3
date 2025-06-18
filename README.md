Task 3 – Multi-Service Architecture on AWS (Frontend + Backend) 
 **2 AWS services**:
- A **Frontend website** using Amazon S3
- A **Backend API** using EC2 (with Python Flask)
  
 Frontend (S3 Website)
- Created an S3 bucket `task-3-frontend`
- Enabled static website hosting
- Uploaded `index.html` with a button that calls backend
- ![Image](https://github.com/user-attachments/assets/68c164cc-62ac-46db-af7e-ea9ba4bc4130)

🔹 Backend (EC2 Flask API)
- Launched an EC2 instance (Ubuntu, t2.micro)
- Installed Flask using `sudo apt install python3-flask`
- Created `app.py` returning: “Hello from EC2 Backend!”
- Allowed HTTP traffic on port 80
- ![Image](https://github.com/user-attachments/assets/72b17167-3f58-4957-9698-b1cd99a68bf5)

🔹 Connected Frontend to Backend
- `index.html` sends a fetch request to EC2’s public IP
- Flask API responds with a message

Tools Used
Amazon S3 (Static hosting)
Amazon EC2 (Backend server)
Python Flask (Web framework)
HTML + JavaScript

further attachment :-> 
-![Image](https://github.com/user-attachments/assets/6d5df212-a71e-4ddb-bb4b-372938b4647b)
-![Image](https://github.com/user-attachments/assets/1a28b1d8-ad1a-4373-9de0-71bb1e4eafd9)
-![Image](https://github.com/user-attachments/assets/2f93fee7-a59d-484a-8404-eb387154619a)
-![Image](https://github.com/user-attachments/assets/6610c2c1-7db3-4af8-a2e2-1ec15f3a0898)


