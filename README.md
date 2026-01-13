# IR-WCMS Auto-Fill Extension

![Status](https://img.shields.io/badge/Status-Private%20Development-orange)
![Chrome](https://img.shields.io/badge/Platform-Chrome%20Extension-blue)
![Manifest](https://img.shields.io/badge/Manifest-V3-brightgreen)
![Tech](https://img.shields.io/badge/Tech-JS%20%7C%20JSON%20%7C%20HTML%20%7C%20CSS-yellow)
![Source](https://img.shields.io/badge/Code-Private-red)

---

🚀 A practical Chrome extension that **automatically fills IR-WCMS form fields** using values entered once — saving time, reducing errors, and eliminating repetitive manual typing.

This public repo contains only a demonstration video.  
The full working code is private and still in development.

---

## 📑 Table of Contents
- Overview
- Why This Project Exists
- Features
- How It Works
- Backend Verification (In Progress)
- Technology Stack
- Installation
- Usage
- Required Inputs
- Error Handling
- Security & Privacy
- Limitations
- Future Plans
- Development Journey
- Acknowledgments

---

## 🌍 Overview
The IR-WCMS Auto-Fill Extension automates input-intensive workflows by:
- Accepting form values only once
- Automatically populating matching WCMS fields
- Minimizing copy–paste effort
- Reducing chances of human error

Built to speed up a real-world process used by many people daily.

---

## 🔎 Why This Project Exists
In real work scenarios, users:
- Pull data from Excel
- Search for each matching WCMS field
- Manually retype every value

This is **slow, repetitive, and tiring**, especially when done multiple times a day.  
This extension streamlines the entire workflow.

---

## ✨ Features
- 🔁 One-time data entry → multiple fields filled
- 📄 Designed specifically for IR-WCMS page layouts
- 🧩 JSON-based field mapping for flexibility
- 🎯 No auto-submit — user stays in control
- ⚠️ Alerts if required inputs are missing
- 🔍 Skips fields that cannot be detected

---

## 🔐 Backend Verification (In Progress)
A backend validation system is currently being built.  
Once completed, it will verify:

- ✔ Email identity  
- ✔ LOA number  
- ✔ Security key/token  

This ensures only authorized users can access auto-fill functionality.

*(Backend logic exists privately and is being integrated.)*

---

## ⚙️ How It Works
1. User opens the extension popup  
2. Enters contract values and details  
3. (Optional) Backend verifies access  
4. Auto-fill logic runs inside WCMS  
5. Matching fields populate automatically  
6. User reviews and submits normally

---

## 🛠 Technology Stack

| Component | Used |
|----------|------|
| Platform | Chrome Extension (Manifest V3) |
| Logic | JavaScript |
| UI | HTML & CSS |
| Data Mapping | JSON selectors |
| Backend | Private REST API (in progress) |

---

## 📦 Installation *(Internal Only)*
1. Open `chrome://extensions/`
2. Enable **Developer Mode**
3. Select **Load unpacked**
4. Choose the extension folder
5. Pin the extension if needed

> Not yet published publicly.

---

## ▶️ Usage
1. Open extension  
2. Input your form values  
3. Click **Auto-Fill**  
4. Verify fields on WCMS  
5. Submit manually when ready

---

## 📋 Required Inputs
Depending on the workflow:
- Email (for backend auth)
- LOA number
- Beneficiary details
- Contract values and dates
- Invoice-related numerical fields

---

## 🧪 Error Handling
- Alerts if required fields are empty
- Stops filling on mismatched page layouts
- Skips missing DOM elements safely
- Displays hints for manual corrections

---

## 🔒 Security & Privacy
- No personal data stored permanently
- No external services used automatically
- Backend (when used) only validates identity
- Nothing sent anywhere without user action
- User fully controls form submission

---

## ⚠️ Limitations
- Works only on supported IRWCMS pages
- Will require updates if IRWCMS UI changes
- Only single-page auto-fill (for now)
- Available on **Chrome desktop** only

---

## 🚧 Future Plans
- Multi-page form completion
- Auto navigation across IRWCMS screens
- Chrome Web Store release
- UI themes (dark/light)

---

## 📓 Development Journey
This project was built using:
- **JavaScript**
- **HTML & CSS**
- **JSON-based mapping**
- **Private backend integration**

It’s important to highlight that this extension was developed **with only basic prior knowledge of HTML and CSS**.  
Every other concept — Chrome Manifest V3, content scripts, DOM mapping, and request handling — was learned gradually.

Development has been strongly supported by:

✨ ChatGPT  
✨ DeepSeek  
✨ Grok  
✨ Online docs & experimentation  

This project is proof that **real-world problems can be solved through curiosity, persistence, and AI-assisted learning.**

---

##  Acknowledgments
- Chrome Extensions documentation
- Web developer community examples
- AI learning tools
- Real workflows that inspired this automation

---

🎯 **This repository contains only a demo video and documentation.  
The full source code remains private while development continues.**

