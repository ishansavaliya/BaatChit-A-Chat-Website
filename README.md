**BaatChit - A Chat Website**


**Description:-**
BaatChit is a real-time chat application with a focus on seamless communication. Users can join conversations, send and receive messages instantly, and enjoy a responsive, user-friendly interface. The app includes real-time updates and notifications, enabling engaging and efficient communication across various devices.

**Table of Contents**
1. Features
2. Technologies Used
3. Installation
4. Running the Project
5. License

**Features**

**Backend**
- User authentication with JWT
- Secure password handling using bcryptjs
- Cookie management for sessions with `cookie-parser`
- Real-time chat with `socket.io`
- Data persistence using MongoDB and Mongoose

**Frontend**
- Responsive and interactive UI built with React
- State management via Redux
- Real-time messaging interface with `socket.io-client`
- Styled with Tailwind CSS and DaisyUI for a clean, modern look

**Technologies Used**

**Backend**
- **Node.js**
- **Express**
- **MongoDB** (using Mongoose)
- **Socket.io** for real-time communication
- **JWT** for secure authentication
- **dotenv** for environment management

**Frontend**
- **React** for UI
- **Redux** for state management
- **React Router** for dynamic routing
- **Socket.io-client** for real-time messaging
- **Tailwind CSS** and **DaisyUI** for styling

---

**Installation**

1. **Clone the repository:**

   git clone https://github.com/ishansavaliya/BaatChit-a-Chat-Website.git


2. **Navigate to the project directory:**

   cd BaatChit-a-Chat-Website


**Set up the Backend**

1. Navigate to the backend directory:

   cd backend


2. Install backend dependencies:

   npm install


3. Set up environment variables:
   Create a `.env` file in the backend directory and add the following details:

PORT = 
MONGO_URI=
JWT_SECRET_KEY=


**Set up the Frontend**

1. Navigate to the frontend directory:

   cd ../frontend


2. Install frontend dependencies:
   
   npm install
   

---

**Running the Project**

**Backend**

**Development Mode:**
Start the backend server using Nodemon:

cd backend
npm run dev


**Frontend**

**Development Mode:**
Start the frontend server using React Scripts:

cd frontend
npm run dev


---

## License
This project is licensed under the ISC License.

---

