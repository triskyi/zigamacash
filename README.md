

# Zigamacash 💰

[![Ionic](https://img.shields.io/badge/Ionic-3880FF?style=for-the-badge&logo=ionic&logoColor=white)](https://ionicframework.com/)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=yellow)](https://vitejs.dev/)
[![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?style=for-the-badge&logo=capacitor&logoColor=white)](https://capacitorjs.com/)
 
![zigamacash](https://github.com/user-attachments/assets/5f331781-19f8-4eea-af2a-34797269c392)


**Zigamacash** is a cool smartphone app built on **Ionic** and **React**, turning your phone into a virtual piggy bank. Put your savings behind a lock for a limited duration—because saving should be a reward, not a constraint.

---

## ✨ Features
- **Scheduled Deductions**: Auto-save from your mobile money account (e.g., weekly Fridays).
- **Locked Savings**: Secure funds until a goal or date—break the bank later!
- **Cross-Platform**: One codebase, two platforms (iOS & Android) with Capacitor.

---

## 🛠 Tech Stack
| Tool            | Purpose                          | Logo                                                                 |
|-----------------|----------------------------------|----------------------------------------------------------------------|
| **Ionic**       | Cross-platform UI & native magic | ![Ionic](https://img.shields.io/badge/Ionic-3880FF?style=flat&logo=ionic&logoColor=white) |
| **React**       | Dynamic, component-driven UI     | ![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black) |
| **Vite**        | Lightning-fast builds            | ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=yellow) |
| **Capacitor**   | Native iOS/Android deployment    | ![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?style=flat&logo=capacitor&logoColor=white) |

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (LTS recommended)
- [Git](https://git-scm.com/)
- [Ionic CLI](https://ionicframework.com/docs/cli):  
  ```bash
  npm install -g @ionic/cli
  ```

### Installation
1. **Clone the Repo**:
   ```bash
   git clone https://github.com/coodic/zigamacash.git
   cd zigamacash
   ```
   *Replace `coodic` with your GitHub username!*

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Run Locally**:
   ```bash
   ionic serve
   ```
   Hit `http://localhost:8100` in your browser to see the magic.

### Building for Mobile
- Add platforms:
  ```bash
  ionic cap add android
  ionic cap add ios
  ```
- Build & run:
  ```bash
  ionic cap run android
  ionic cap run ios
  ```
  *Requires Android Studio or Xcode.*

---




### Guidelines
- **Code Style**: React hooks & functional components FTW.
- **Testing**: Try `ionic serve` or a device build.
- **Scope**: Think savings features, mobile money (e.g., MobileMoney,AitelMoney), or UI polish.
- **Issues**: Peek at [Issues](https://github.com/coodic/zigamacash/issues) or suggest ideas.

### Cool Ideas to Contribute
- 🎨 A savings goal visual (progress bar or piggy animation).
- 🔌 Mock API for mobile money deductions.
- 🛡️ Better error messages or UX tweaks.

---

## 📂 Project Structure
```plaintext
zigamacash/
├── src/              
│   ├── pages/        
│   └── App.tsx       
├── public/           
├── package.json      
└── README.md         
```

---

## 📜 License
MIT License—see [LICENSE](LICENSE) for the fine print. 

---

## 📬 Contact
Got questions? Hit us up on [GitHub Issues](https://github.com/coodic/zigamacash/issues) or ping the lead, [coodic](https://github.com/coodic).

**Save smart, save with Zigamacash!** 🐷💸

---

