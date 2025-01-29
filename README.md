# Full Stack Chat Application  

## Overview  
This project is a Full Stack Chat Application that combines a robust backend built with Django REST Framework (DRF) and a dynamic front-end developed using ReactJS. The application supports real-time communication, secure authentication, and seamless user interaction, making it a comprehensive chat solution.  

## Features  
- **Backend**  
  - Developed RESTful APIs using **Django REST Framework (DRF)**.  
  - Built a chat server administration API with server filtering, channel management, and related data retrieval.  
  - Integrated real-time chat functionality using **Django Channels** and WebSockets.  
  - Implemented secure token-based authentication for user registration and login with **djangorestframework-simplejwt**.  

- **Frontend**  
  - Designed user-friendly interfaces with **ReactJS**, **React Router**, and **Material-UI**.  
  - Integrated APIs using **Axios** to handle data fetching and CRUD operations.  
  - Implemented dynamic components for chat servers, chat rooms, and message history.  

## Technologies Used  
- **Backend**: Django REST Framework (DRF), Django Channels, djangorestframework-simplejwt  
- **Frontend**: ReactJS, React Router, Material-UI, Axios  
- **Database**: SQLite (or any relational database of choice)  
- **Tools**: Visual Studio Code, Git  

## Installation  

### Prerequisites  
- Python 3.x  
- Node.js and npm  
- Git  

### Backend Setup  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Hami-611/Multi_Chat_Application.git
   ```  

2. Navigate to the `djchat` directory:  
   ```bash
   cd djchat
   ```  

3. Create and activate a virtual environment:  
   ```bash
   python -m venv venv  
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```  

4. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  

5. Run database migrations:  
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```  

6. Start the backend server:  
   ```bash
   python manage.py runserver
   ```  
### Frontend Setup  
1. Navigate to the `reactchat` directory:  
   ```bash
   cd ../reactchat
   ```  

2. Install dependencies:  
   ```bash
   npm install
   ```  

3. Start the development server:  
   ```bash
   npm run dev
   ```
   
## Usage  
1. Access the application at `http://localhost:5173` (frontend).  
2. Use the admin panel at `http://127.0.0.1:8000/admin` to manage chat servers, channels, and users.  
3. Log in, register, and start using the chat application to communicate in real-time.  

## Features in Detail  
- Server Management:  
  - Add, update, and delete chat servers and channels.  
  - Retrieve server details, including related channels and users.  

- Real-time Communication:  
  - Join chat rooms and send/receive messages instantly with WebSocket support.  
  - View message history and active users in chat rooms.  

- Authentication:  
  - Secure user login and registration using token-based authentication.  
  - WebSocket authentication for real-time functionality.  

## Future Enhancements    
- Implement file sharing within chat rooms.  
- Enhance UI/UX with additional themes and layouts.


## Contributions  
Contributions are welcome! Feel free to fork the repository, submit issues, or create pull requests.  

---
 
