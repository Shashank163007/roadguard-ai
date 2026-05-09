RoadGuard AI
RoadGuard AI is a real-time, AI-powered road safety assistant designed to enhance driver awareness through computer vision and audible feedback.

Live Demo: https://hackathon-blond-nine.vercel.app/app.html

Features
Real-Time Object Detection: Utilizes TensorFlow.js and the COCO-SSD model to identify pedestrians, vehicles (cars, trucks, buses, motorcycles), traffic signals, and road obstacles in real-time.

Intelligent Voice Alerts: Provides audible warnings for critical threats, such as pedestrians ahead or sudden obstacles, with a priority-based queue system.

Dynamic Risk Scoring: Calculates a live "Risk Score" (0-100) based on the proximity and type of objects detected in the camera feed.

Lane Departure Monitoring: Analyzes the road surface to detect lane markings and alerts the user if the vehicle appears to be drifting.

Night Mode Optimization: Automatically monitors environment luminance levels to maintain detection accuracy in low-light conditions.

Heads-Up Display (HUD): A futuristic interface showing live FPS, object counts, alert history, and a visual risk gauge.

Tech Stack
Frontend: HTML5, CSS3 (Custom HUD styling), JavaScript (ES6+).

AI/ML: TensorFlow.js and the COCO-SSD pre-trained model for browser-based inference.

Authentication: Firebase Auth (Email/Password and Google Sign-in).

Deployment: Vercel.

Repository Structure
index.html: The secure access portal (Login).

signup.html: User registration interface.

app.html: The core application containing the detection engine and HUD.

vercel.json: Deployment and routing configuration.

.gitignore: Specifies files and directories to be ignored by Git (e.g., .vercel).

Usage
Authentication: Users must log in or sign up via the secure portal to access the system.

Activation: Once logged in, click the [ ACTIVATE SYSTEM ] button to grant camera and audio permissions.

Monitoring: The system will begin scanning the feed. Visual bounding boxes will appear around detected objects, and voice alerts will trigger based on proximity and threat level.
