

# 🕵️‍♂️ Thief Detection Syatem

A real-time object detection web application built with **Next.js 15**, **Tailwind CSS v4**, and **TensorFlow.js**. The app monitors a webcam feed and triggers a visual alert (red bounding box) specifically when a **person** is detected in the frame.

## 🚀 Features

* **Real-time Detection:** High-speed object detection using the `COCO-SSD` model.
* **Targeted Alerts:** Specifically identifies "person" entities and changes the UI state to alert the user.
* **Responsive Dashboard:** A sleek, dark-mode interface that scales to fit laptop and desktop screens.
* **Optimized Performance:** Uses `onUserMedia` to ensure the camera resolution matches the canvas display for pixel-perfect bounding boxes.

---

## 🛠️ Tech Stack

* **Framework:** [Next.js 15+](https://nextjs.org/)
* **Styling:** [Tailwind CSS v4](https://tailwindcss.com/)
* **Machine Learning:** [@tensorflow/tfjs](https://www.tensorflow.org/js) & [@tensorflow-models/coco-ssd](https://github.com/tensorflow/tfjs-models/tree/master/coco-ssd)
* **Webcam Handling:** [react-webcam](https://www.npmjs.com/package/react-webcam)

---

## 📦 Installation

1. **Clone the repository:**
```bash
git clone https://github.com/milanprajapati571/theif-detection.git
cd theif-detection

```


2. **Install dependencies:**
```bash
npm install @tensorflow/tfjs @tensorflow-models/coco-ssd react-webcam

```


3. **Run the development server:**
```bash
npm run dev

```



---



## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

---
