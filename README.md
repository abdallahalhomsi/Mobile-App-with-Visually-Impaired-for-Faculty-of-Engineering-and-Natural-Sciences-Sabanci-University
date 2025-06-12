# Faculty Navigation App

This iOS application helps visually impaired individuals navigate indoor environments using real-time object detection. Built with Swift and powered by YOLO11, the app provides spoken guidance and camera-based detection to help users independently find classrooms and navigate corridors inside the Faculty of Engineering and Natural Sciences (FENS) at Sabancı University.

---

## 🎯 Project Objective

To assist visually impaired individuals with real-time, camera-based indoor navigation by combining object detection and audio feedback in a fully mobile application.

---

## 🧠 Key Technologies

- **YOLO11 (Ultralytics)** – For real-time object detection and corridor identification  
- **Swift (iOS)** – For mobile app development  
- **Roboflow** – For dataset labeling and preprocessing  
- **Google Colab** – For model training  
- **CoreML (.mlpackage)** – For deploying the trained model on iOS  
- **Text-to-Speech (Swift API)** – For voice-based user feedback  

---

## 🛠️ Features

- 🔍 Real-time object detection with YOLO11  
- 📍 Indoor corridor identification using custom-labeled markers  
- 🔊 Voice feedback with tap-based interaction (single, double, triple taps)  
- 📸 On-device detection using the phone’s camera  
- 🧭 Guidance toward classrooms within G Floor at FENS  

---

## 🏗️ Dataset & Model

- **Images Collected**: 667  
- **Environment**: G Floor – FENS, Sabancı University  
- **Labeled Objects**: vending machine, trash bin, printer, painting, doors, fire safety equipment  
- **Model Training**: Conducted in Google Colab, converted to `.mlpackage` for iOS  
- **Corridor Tracking**: Objects were class-labeled to act as spatial markers for identifying current corridor location  

---

## 📱 Interaction

- **Single Tap** – Get current location  
- **Double Tap** – Request direction to a room  
- **Triple Tap** – Cancel navigation or request help  
- The app provides audio feedback to guide users through corridor transitions.

---

## 👨‍💻 Contributors

- **Abdallah Al Homsi** – AI integration, detection pipeline, user interface  
- **Imran Hasanzade** – App structure, testing, and data processing  
- **Sadettin Er** – Dataset collection, training setup, user feedback logic  

---

## 📈 Limitations & Future Work

- Currently limited to G Floor due to dataset constraints  
- Future plans include expanding the dataset to additional floors and buildings  
- Planned enhancements: Indoor map integration, multilingual voice support, and wider model deployment

---

## 📄 Supervisor

This project was completed under the supervision of **Professor Kamer Kaya** as part of the PROJ201 course at Sabancı University.

---

## 📫 Contact

For questions or collaboration:
- 📧 homsiabdullah4@gmail.com  
- 🔗 [LinkedIn](https://www.linkedin.com/in/abdallah-al-homsi-817a7834b)  
- 🧑‍💻 [GitHub](https://github.com/abdallahalhomsi)

---

> Empowering independence through AI and accessibility.
