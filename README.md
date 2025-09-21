---

# 🩺 Face Mask Detection

A deep learning–based **Face Mask Detection System** built using **TensorFlow**, **Keras**, and **OpenCV**.
The model detects whether a person is wearing a **mask** or **no mask** in real time through a webcam feed or static images.

---

## 🚀 Features

* Real-time face mask detection using webcam.
* Pre-trained deep learning model with TensorFlow/Keras.
* Uses OpenCV for image processing and face detection.
* Can be applied to images, videos, or live camera streams.

---

## 🛠️ Requirements

Install the required dependencies before running the project:

```
tensorflow>=1.15.2
keras==2.3.1
imutils==0.5.3
numpy==1.18.2
opencv-python==4.2.0.*
matplotlib==3.2.1
scipy==1.4.1
```

Install using pip:

```bash
pip install -r requirements.txt
```

---

## 📊 Results

* The model achieves high accuracy in distinguishing **Mask** vs **No Mask**.
* Example output:

  * ✅ Person with mask → "Mask" (Green Box)
  * ❌ Person without mask → "No Mask" (Red Box)

---

## 📌 Notes

* The dataset can be extended to improve model accuracy.
* Fine-tuning hyperparameters and training for more epochs can yield better results.
* The system can be integrated into CCTV feeds or access control systems for real-world applications.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request with improvements.

---