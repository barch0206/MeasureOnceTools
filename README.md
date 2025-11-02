# 🧰 Measure Once Tools

Measure Once Tools brings together a complete set of on-site calculation and measurement aids in one responsive web app.  
From material estimations to load calculations and leveling aids — the suite empowers professionals to make quick, precise decisions **without switching apps or waiting for slow tools**.

The platform takes full advantage of native device capabilities (like the camera, magnetometer, and gyroscope) through secure browser APIs to simulate real-world measurement and assistive tools.

---

## 🏗️ Architecture Overview

```

React Frontend  →  Browser APIs  →  Render Deployment

```

**Frontend (React)**  
- Houses all calculators, converters, and visual guides  
- Uses modular React components for each tool  
- Optimized with lazy loading and code splitting  
- Delivers <1s tool load time on modern devices  

**Browser API Integrations**  
- Uses **gyroscope**, **camera**, and **magnetometer** for interactive measurement  
- Performs all calculations client-side for speed and privacy  

**Deployment**  
- Fully static React app  
- Dockerized and deployed to **Render** for scalability and ease of updates  

---

## 🧠 Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | React.js, Vite / Create React App |
| UI / Styling | Tailwind CSS |
| Browser APIs | Camera, Magnetometer, Gyroscope, Accelerometer |
| Containerization | Docker |
| Hosting | Render Cloud |
| Version Control | GitHub |

---

## 📁 Project Structure

```

measure-once-tools/
│
├── src/
│   ├── components/          # Individual calculators and widgets
│   ├── utils/               # Shared formulas and helper functions
│   ├── assets/              # Icons, logos, and tool images
│   └── App.jsx
│
├── public/
│   ├── index.html
│   └── measure-once-logo.png
│
├── Dockerfile
├── package.json
└── README.md

````

---

## ⚡ Performance

- ⚙️ **Optimized load time:** <1 second  
- 📱 **Mobile-first design:** Fits perfectly on phones and tablets  
- 🧮 **100% client-side computation:** No backend latency  
- 🧊 **Containerized:** Runs identically in all environments  

---

## 📸 Screenshots
![1000002337](https://github.com/user-attachments/assets/e43365c6-c5e6-4b8c-b9d2-10eccc471d8d)
![1000002338](https://github.com/user-attachments/assets/45a017fe-f7b3-4e38-b684-5c956420b707)
![1000002335](https://github.com/user-attachments/assets/8b7694cf-7020-4340-ae91-1b6827cfda7b)
![1000002336](https://github.com/user-attachments/assets/b926421a-1c9a-4716-be1e-06b6f3fe057c)

---

## 💡 Future Enhancements

* Offline PWA support for field use
* AI-based estimator for material usage and wastage prediction
* Collaborative mode for sharing project calculations
* Integration with export formats (PDF / CSV)

---
