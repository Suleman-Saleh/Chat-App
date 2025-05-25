# 💬 iChat – Real-Time Chat Application

iChat is a real-time chat web application built using HTML, CSS, JavaScript, and Socket.IO. It allows users to send and receive messages instantly in a chat room.

---

## 🚀 Features

- Real-time messaging with Socket.IO
- Typing support with `Enter` and multi-line using `Shift+Enter`
- Simple and responsive UI
- Separate landing page with navigation
- Custom styling using CSS

---

## 🛠️ Technologies Used

| Layer       | Technology                     |
|-------------|--------------------------------|
| Frontend    | HTML5, CSS3, JavaScript        |
| Backend     | Node.js, Express.js (assumed)  |
| Real-time   | Socket.IO                      |
| Fonts       | Google Fonts (Poppins)         |
| Versioning  | Git                            |

---

## 📂 Project Structure

```
chatApp/
├── index.html
├── landing.html
├── assets/
│   ├── css/
│   │   ├── style.css
│   │   └── landing-style.css
│   ├── js/
│   │   └── client.js
│   └── chat.png
└── server.js (not included but assumed for Socket.IO backend)
```

---

## 🔧 Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd chatApp
   ```

2. Install dependencies:
   *(Assuming a `package.json` and `server.js` exist)*
   ```bash
   npm install
   ```

3. Start the server:
   ```bash
   node server.js
   ```

4. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

---

## 📸 Screenshots

![Landing Page](./assets/screenshots/landing.png)
![Chat Page](./assets/screenshots/chat.png)

---

## 📄 License

This project is licensed under the MIT License.
