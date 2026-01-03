//https://html-css-naciri.carrd.co:

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Segoe UI', sans-serif;
}

body,
html {
  height: 100%;
  overflow: hidden;
}

/* 🔁 Glassy Background Image */
.background {
  position: absolute;
  width: 100%;
  height: 100%;
  background: url('bg.jpg') no-repeat center center/cover;

  z-index: -1;
}

/* 🧊 Glass Login Box */
.login-box {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 350px;
  padding: 40px;
  transform: translate(-50%, -50%);
  background: rgba(255, 255, 255, 0.069);
  border-radius: 15px;
  box-shadow: 0 8px 32px 0 rgba(255, 255, 255, 0.684);
  backdrop-filter: blur(5px);
  -webkit-backdrop-filter: blur(12px);
  border: 1px solid rgba(255, 255, 255, 0.2);
  color: white;
}

.login-box h2 {
  text-align: center;
  margin-bottom: 30px;
}

/* 🖊️ Inputs with Animation */
.login-box input {
  width: 100%;
  padding: 12px;
  margin: 10px 0;
  background: rgba(255, 255, 255, 0.2);
  border: none;
  border-radius: 10px;
  color: white;
  outline: none;
  font-size: 14px;
  transition: 0.4s ease;
  position: relative;
  backdrop-filter: blur(5px);
}

/* ✨ Hover effect on input */
.login-box input:hover {
  background: rgba(255, 255, 255, 0.3);
  box-shadow: 0 0 8px rgba(255, 255, 255, 0.3);
}

/* 💫 Focus effect */
.login-box input:focus {
  background: rgba(255, 255, 255, 0.4);
  transform: scale(1.02);
}

/* 🔡 Placeholder animation */
.login-box input::placeholder {
  color: rgba(255, 255, 255, 0.6);
  transition: 0.3s ease;
}

.login-box input:focus::placeholder {
  transform: translateY(-15px);
  font-size: 12px;
  opacity: 0.8;
}

.vergule{
  margin-top: 10px;
  border-radius: 50%;
}

.login-box button {
  width: 100%;
  padding: 12px;
  margin-top: 20px;
  background: #ffffff20;
  border: none;
  border-radius: 10px;
  color: white;
  font-size: 16px;
  cursor: pointer;
  transition: background 0.6s ease;
}
.login-box button:hover {
  background: rgba(255, 255, 255, 0.4);
  transform: translateY(-2px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.35);
}

.login-box button:active {
  transform: scale(0.98);
}
