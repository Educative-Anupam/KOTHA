# 🎙️ KOTHA - Text to Speech Converter

**KOTHA** is a feature-rich **Text-to-Speech (TTS) Converter** built using **HTML, CSS, and JavaScript**.  
It not only converts text into natural speech using the **Web Speech API**, but also provides:  
- Voice customization (speed, pitch, and voice selection)  
- Play / Pause / Resume / Stop controls  
- Speech download option (IBM Watson TTS integration)  
- User authentication (Sign Up, Login, Forgot Password) with **localStorage + password hashing**  
- A modern UI with **hamburger menu navigation**  

---

## ✨ Features
- 📝 **Text-to-Speech Conversion** → Input text and listen instantly  
- 🎛️ **Controls** → Adjust speed & pitch  
- 🎙️ **Voice Selection** → Choose from browser-supported voices  
- ⏯ **Playback Options** → Listen, Pause, Resume, Stop  
- 💾 **Download Speech** → Save speech as `.wav` (powered by IBM Watson TTS API)  
- 🔐 **Authentication System** → Sign Up, Login, Logout, Forgot Password  
- 🔒 **Secure Password Storage** → Salted + Hashed with `crypto-js`  
- 📱 **Responsive UI** with hamburger menu  

---

## Visual Demo
1. Front Page
   <img width="1920" height="920" alt="Screenshot 2025-08-26 195545" src="https://github.com/user-attachments/assets/a01e58bf-3d68-452b-8d4a-cbc60f7bd1e3" />

2. About
   <img width="1920" height="916" alt="Screenshot 2025-08-26 195645" src="https://github.com/user-attachments/assets/88c68c5b-173a-4b08-94be-55482bded900" />


4. Contact
   <img width="1920" height="923" alt="Screenshot 2025-08-26 195709" src="https://github.com/user-attachments/assets/ba3fa983-d501-4abc-a524-e715406816ff" />

5. Sign up & Log in Page
   <img width="1920" height="916" alt="Screenshot 2025-08-26 195807" src="https://github.com/user-attachments/assets/28bee5b9-7162-4c32-99b6-6c17a5f7f896" />


   <img width="1920" height="920" alt="Screenshot 2025-08-26 195746" src="https://github.com/user-attachments/assets/fd9b2864-d9d1-4409-b9de-50517970ffd7" />


## 📂 Project Structure
KOTHA/
│── index.html # Main application
│── sph.css # Stylesheet
│── images/
│ └── kotha-logo.png
│── README.md # Documentation


---

## 🚀 How to Use
1. Open the app in your browser.  
2. Type text in the textarea.  
3. Choose **voice, speed, and pitch**.  
4. Use the buttons:
   - ▶ **Listen**
   - ⏸ **Pause**
   - ⏯ **Resume**
   - ⏹ **Stop**
   - 💾 **Download** (save as audio file)  
5. Use the **Login/Signup** modal to create an account (stored in localStorage).  

---

## 🌍 Live Demo
👉 [KOTHA - Text to Speech Converter](https://educative-anupam.github.io/KOTHA/)  

---

## 🛠️ Technologies Used
- **HTML5** → Structure  
- **CSS3** → Styling  
- **JavaScript (Web Speech API)** → TTS functionality  
- **IBM Watson TTS API** → Speech download  
- **crypto-js** → Password hashing & salting  
- **LocalStorage** → Save user data locally  

---

## 📌 Future Enhancements
- Multi-language TTS support  
- Backend authentication with database  
- Export speech as MP3 with better quality  
- Dark mode for UI  

---

## 📜 License
This project is licensed under the **MIT License** – free to use and modify.  

---

💡 *KOTHA brings your text to life with voice!* 🎤
