 
# 🎨 EduLite Frontend


The EduLite frontend is a responsive interface that focuses on speed, clarity, and simplicity to make essential features easily accessible — such as courses , classes .It also supports multiple languages for ease and supports dark mode. The design avoids distractions to support a clear and smooth learning experience.


## 🛠️ Tech 

- HTML , CSS , Javascript
- React JS   
- Tailwind CSS 
- Vite  (Fast and lightweight development server and build tool) 

## 🗂️ Project Structure
 
```
Frontend/
├──EduLiteFrontend/
|     ├──node-modules/
│     ├── public/     
│     │     └── vite.svg    #changed to EduLite logo         
│     ├── src/
│     │   ├── assets/  # Images, logos, etc.
│     │   │      ├── heroimg.png
│     │   │      └── EduTech_Logo.webp
│     │   │
│     │   ├── components/ 
│     │   │        ├── DarkModeToggle.jsx  
│     │   │        ├── Navbar.jsx 
│     │   │        ├── LanguageSwitcher.jsx 
│     │   │        └── Sidebar.jsx  
│     │   │
│     │   ├── pages/  
│     │   │     ├── Home.jsx 
│     │   │     ├── Notifications.jsx
│     │   │     ├── LogInandLogOut.jsx
│     │   │     └── Chats.jsx 
│     │   │   
│     │   ├── i18n/      
│     │   │     ├── locals/
│     │   │     │      ├── ar.json
│     │   │     │      └── en.json 
│     │   │     └── index.js 
│     │   │
│     │   ├── App.css  
│     │   ├── App.jsx  
│     │   ├── index.css           
│     │   └── main.jsx 
│     │   
│     ├── .gitignore
│     ├── index.html
│     ├── package.json
│     ├── package-lock.json
│     └── vite.config.js
└──README.md
```
## 🚀 Getting Started
 
```bash
cd Frontend/EduLiteFrontend
npm install
npm run dev
```
