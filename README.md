# 🚗💨 JetRacer Pro: Autonomous Driving with NVIDIA Jetson Nano 🤖🧠

Welcome to the JetRacer Pro Autonomous Driving project! This repository showcases our team’s efforts in building an autonomous driving car using the NVIDIA Jetson Nano. Our goal is to enable the JetRacer to navigate tracks and avoid obstacles using deep learning and real-time decision-making. 🛤️🏁

## 📚 Project Overview

This project uses the NVIDIA Jetson Nano and the JetRacer Pro AI Kit to build an autonomous driving car capable of navigating complex tracks and avoiding obstacles, all powered by deep learning. 🚙💡

## 🧠 Key Features

- **Deep Learning Models**: Trained and tested models like ResNet-18, ResNet-34, and SqueezeNet for real-time navigation. ResNet-18 turned out to be the champion, balancing speed and accuracy! 🥇
- **Data Augmentation**: Applied techniques like brightness adjustment, flipping, and darkness modification to make the models more robust across diverse conditions. 📸✨
- **Edge AI with Jetson Nano**: Real-time inference using the NVIDIA Jetson Nano for low-latency steering control and decision-making. 🌐💨

## 🔧 Hardware Setup

- **NVIDIA Jetson Nano** 🌟
- **JetRacer Pro AI Kit**: Includes a chassis, wheels, IMX219-160 camera, and servo motor. 🛠️
- **WiFi Connection**: Configured using mobile hotspots for reliable communication with the car. 📶

## 🧪 Data Collection & Augmentation

- Collected real-world driving data with the JetRacer navigating various tracks. 🛤️
- Performed data augmentation using OpenCV to simulate different environments and lighting conditions. 🌞🌚

### Dataset Breakdown

| Dataset Type          | Images |
|-----------------------|--------|
| Perfect Route         | 530    |
| Self-Correction       | 180    |
| Obstacle Detection     | 780    |
| Combined (Augmented)  | 2980   |

## 🚀 Model Training & Optimization

- **ResNet-18**: Achieved the best performance with fast inference and accurate steering control.
- **Fine-tuned Driving Parameters**: Adjusted throttle and steering gain for smoother navigation.
- **Model Evaluation**: Assessed models based on the number of valid laps and average lap time. ResNet-18 led the pack! 🏎️

## 🏅 Results

- **Best Model**: ResNet-18 with optimal settings completed 5 perfect laps at an average speed of 6.2 seconds per lap. 🏁
- **Obstacle Avoidance**: Successfully navigated 3 obstacle-free laps with an average speed of 6.5 seconds per lap. 🚧

## 🚧 Challenges & Learnings

- Encountered hardware issues like loose camera holders and Wi-Fi connectivity challenges. 🔧
- Adjusted the Frame Per Second (FPS) for smoother navigation—finding that lower FPS (around 22) resulted in better driving performance. 🎥

## 🤔 Future Directions

- Upgrade the software for compatibility with advanced models like Levit-128.
- Collect more data and explore improved augmentation techniques for greater robustness. 📊
- Enhance obstacle detection with advanced vision techniques for more dynamic environments.

## 📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

## 📫 Contact

- **Oluwadara Adedeji** – University College Dublin  
  oluwadara.adedeji@ucdconnect.ie
- **Sanat Thukral** – Technological University Dublin  
  d18129674@mytudublin.ie
- **Madhuri Sawant** – Technological University Dublin  
  D22130161@mytudublin.ie
- **Nika Gorchakovar** – Dublin City University  
  Nika.gorchakova2@mail.dcu.ie
- **Hong-Hanh Nguyen-Le** – University College Dublin  
  hong-hanh.nguyen-le@ucdconnect.ie
- **Abigail Naa Amankwaa Abeo** – Dublin City University  
  abigail.abeo2@mail.dcu.ie

For any questions or collaboration ideas, reach out to us through the email addresses above.

Happy driving! 🏎️💨
