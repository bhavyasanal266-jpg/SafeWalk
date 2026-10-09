SafeWalk – AI-Powered Smart Cane for Visually Impaired People

SafeWalk is a smart walking stick project designed to improve the safety, mobility, and independence of visually impaired individuals. The proposed system combines sensors, embedded systems, computer vision, and assistive technology to help users detect obstacles, receive navigation guidance, and communicate during emergencies.

The project explores how Artificial Intelligence (AI), the Internet of Things (IoT), and real-time feedback can make everyday navigation safer and more accessible.

📌 Table of Contents

- "Introduction" (#-introduction)
- "Problem Statement" (#-problem-statement)
- "Objectives" (#-objectives)
- "Key Features" (#-key-features)
- "Technology Stack" (#-technology-stack)
- "System Architecture" (#-system-architecture)
- "How It Works" (#-how-it-works)
- "Project Structure" (#-project-structure)
- "Installation and Setup" (#-installation-and-setup)
- "Expected Outcomes" (#-expected-outcomes)
- "Future Enhancements" (#-future-enhancements)
- "Team" (#-team)
- "References" (#-references)

🌟 Introduction

Navigation can be challenging for visually impaired individuals because of obstacles, changes in terrain, traffic, and unfamiliar surroundings. Traditional mobility aids provide essential support but may not offer electronic obstacle alerts, GPS-based guidance, or emergency communication.

SafeWalk proposes an intelligent assistive cane that combines ultrasonic sensors, embedded hardware, navigation technologies, and voice-based feedback to help users become more confident and independent while moving through their surroundings.

🎯 Problem Statement

Traditional walking sticks primarily depend on physical contact to identify obstacles. Users may also face difficulties detecting certain obstacles, navigating unfamiliar locations, and contacting others during emergencies.

SafeWalk aims to address these challenges through sensor-based obstacle detection, voice-guided navigation, location tracking, and emergency notifications.

🎯 Objectives

- Detect nearby obstacles and provide timely alerts.
- Explore AI-based object recognition for identifying relevant objects in the user's surroundings.
- Provide voice-assisted navigation and location guidance.
- Support GPS-based location tracking.
- Enable emergency communication through connected services.
- Develop a lightweight, accessible, and power-efficient assistive solution.

✨ Key Features

1. Obstacle Detection

Ultrasonic sensors are proposed to measure the distance to nearby obstacles and trigger appropriate alerts.

2. AI-Based Object Recognition

Computer vision can be used to identify objects in the environment and support more informative navigation assistance. YOLOv5 is a candidate model for object detection, subject to implementation and testing.

3. Voice Assistance

Speech-based feedback is intended to communicate relevant information to the user without relying solely on visual output.

4. GPS-Based Navigation

GPS and mapping services are proposed to support location awareness and navigation in unfamiliar areas.

5. Emergency Communication

A GSM module and Telegram API are proposed for transmitting location information or emergency notifications to designated contacts.

6. Real-Time Alerts

A vibration motor and speaker can provide tactile and audio alerts to help the user respond to detected obstacles.

«Development status: These are proposed system capabilities. Individual features should be marked as implemented only after the corresponding hardware or software has been developed and tested.»

🛠️ Technology Stack

Category| Technologies
Programming| Python, C/C++ as applicable
Artificial Intelligence| Computer vision, YOLOv5 as a candidate object detection model
Sensors| Ultrasonic sensors
Embedded Systems| ESP32 microcontroller
Navigation| GPS, Google Maps API
Voice Assistance| Vosk speech recognition
Communication| SIM7600 GSM module, Telegram API
User Feedback| Speaker, vibration motor
Development Tools| Visual Studio Code, Git, GitHub

The final technology stack may change during development according to hardware compatibility, testing, and implementation requirements.

🏗️ System Architecture

The proposed system follows this general workflow:

1. Input: Sensors collect distance information, while a camera may capture images of the surrounding environment.
2. Processing: The microcontroller processes sensor readings, and a compatible computing platform can process camera input using computer vision.
3. Decision-making: The system determines which obstacle or navigation alert should be provided.
4. Feedback: Audio and vibration alerts communicate relevant information to the user.
5. Navigation and communication: GPS, GSM, and connected services can support location tracking and emergency notifications.

⚙️ How It Works

1. The user carries the SafeWalk smart cane while walking.
2. Ultrasonic sensors measure the distance to nearby obstacles.
3. The processing system evaluates sensor readings and identifies situations that require an alert.
4. A speaker or vibration motor provides feedback to the user.
5. Where the relevant components are implemented, GPS and mapping services assist with navigation.
6. Emergency communication can send a notification to a designated contact when the corresponding feature is configured.

AI-based object recognition is an additional component that can be integrated and evaluated as development progresses.

💻 Installation and Setup

The setup instructions will depend on the final hardware configuration and the software modules implemented.

Prerequisites

- Python, if required by the implemented software modules.
- Compatible microcontroller and sensors.
- Required libraries and dependencies for the selected modules.
- API credentials for any external services used.

Getting Started

Clone the repository:

git clone https://github.com/YOUR-USERNAME/SafeWalk.git
cd SafeWalk

Replace "YOUR-USERNAME" with your GitHub username.

Install dependencies only after the project’s "requirements.txt" has been created and populated:

pip install -r requirements.txt

Important: These commands prepare the repository and install listed Python dependencies. The project cannot be run end-to-end until the actual source code, configuration, hardware connections, and module-specific instructions are added.

📈 Outcomes

- Improved awareness of nearby obstacles.
- More accessible audio and tactile feedback.
- Support for location-aware navigation.
- A potential emergency communication mechanism.
- A foundation for further research into affordable assistive technology.

These outcomes are design goals and require practical testing to evaluate their effectiveness.

🚀 Future Enhancements

- Integrate and evaluate YOLOv5-based object detection.
- Explore improved obstacle detection using additional sensors or LiDAR.
- Enhance voice-guided navigation and speech processing in noisy environments.
- Improve IoT connectivity and emergency communication.
- Optimize battery consumption and portability.
- Conduct usability testing with appropriate accessibility and safety considerations.

👩‍💻 Team

SafeWalk – Mini Project, Computer Science and Engineering

Mohandas College of Engineering and Technology (MCET)

Project team:

- Athira S.
- Karthikeyan B. J.
- Bhavya Sanal
- Chaithanya P. B.

Project guide: Prof. Nishadha S. G.

📚 References

1. Apu, A. I., Nayan, A. A., Ferdaous, J., & Kibria, M. G. (2022). IoT-Based Smart Blind Stick. Proceedings of the International Conference on Big Data, IoT, and Machine Learning.
   https://www.researchgate.net/publication/356782700_IoT-Based_Smart_Blind_Stick

2. Gbenga, D. E., Shani, A. I., & Adekunle, A. L. (2017). Smart Walking Stick for Visually Impaired People Using Ultrasonic Sensors and Arduino. International Journal of Engineering and Technology.
   https://www.researchgate.net/publication/320836040_Smart_Walking_Stick_for_Visually_Impaired_People_Using_Ultrasonic_Sensors_and_Arduino

3. Wahab, M. H. A., et al. (2011). Smart Cane: Assistive Cane for Visually-Impaired People. International Journal of Computer Science Issues.
   https://www.ijcsi.org/papers/IJCSI-8-4-2-21-27.pdf


SafeWalk explores the potential of AI and embedded technology to make mobility safer, more accessible, and more independent for visually impaired individuals.
