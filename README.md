
# 💬 Real-Time Chat Application

This is a simple real-time chat app built using **Node.js**, **Express**, **Socket.IO**, and **Vanilla JavaScript**. It features a landing page and a chat interface for multiple users to join and communicate in real-time.

---

## 🚀 Features

- Real-time messaging with WebSocket (via Socket.IO)
- User join/leave notifications
- Simple and clean UI
- Hosted assets and static files
- Ready for local network and public access via Ngrok

---

## 🛠 Technologies Used

- **Node.js**
- **Express.js**
- **Socket.IO**
- **HTML5**
- **CSS3**
- **JavaScript**

---

## 📂 Project Structure

```
chatApp/
│
├── css/
│   └── style.css
│
├── assets/
│   └── (images, icons, etc.)
│
├── index.html          # Main chat interface
├── landing.html        # Landing page
├── nodeServer/
│   └── index.js        # Express and Socket.IO server
│
└── README.md           # This file
```

---

## 🧑‍💻 How to Run Locally

1. Clone or download this repository.

2. Navigate to the project folder in your terminal:

```bash
cd "chatApp/nodeServer"
```

3. Install dependencies (if any):

```bash
npm install
```

4. Start the server:

```bash
node index.js
```

5. Open your browser and visit:

```
http://localhost:8000
```

---

## 🌍 Access from Other Devices (Public Hosting)

You can make your app publicly accessible using **Ngrok**.

### ✅ Steps:

1. **Download Ngrok**:  
   [https://ngrok.com/download](https://ngrok.com/download)

2. **Install & Authenticate**:
   Open PowerShell and run:

   ```bash
   C:\path\to\ngrok.exe config add-authtoken YOUR_AUTHTOKEN
   ```

   Replace `YOUR_AUTHTOKEN` with the token from [ngrok.com/dashboard](https://dashboard.ngrok.com/get-started/your-authtoken)

3. **Expose Your Local Server**:

   Run:

   ```bash
   C:\path\to\ngrok.exe http 8000
   ```

4. You’ll get a public URL like:

   ```
   https://random-name.ngrok.io
   ```

   Share this with others to access the app from any device.

---

## 👤 Author

Created by **[Your Name]**

---

## 📃 License

This project is open-source and free to use under the MIT License.
