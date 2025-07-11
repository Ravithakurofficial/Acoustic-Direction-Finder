Acoustic Direction Finder (ADF) 🌐
A web-based Acoustic Direction Finder (ADF) tool deployed via Railway. This application processes audio input and visualizes the direction of the sound source in real time.

🚀 Live Demo
Access the live application here:
https://acoustic-direction-finder-adf-design.up.railway.app/

🧩 Features
Real-time Direction Detection: Determines sound source direction using browser audio APIs.

Interactive UI: Visual directional indicators update dynamically based on detected audio input.

Robust Backend: Spring Boot handles audio data processing and coordinates calculations.

Modern Frontend Stack: Built with Thymeleaf, HTML, CSS, and JavaScript for responsive UI.

Firebase Integration: Stores and retrieves session data or user configurations.

Geocoder Support: Optionally maps geolocation metadata tied to sound direction tracking.

📋 Tech Stack
Backend: Spring Boot

Frontend: Thymeleaf templates, HTML, CSS, JavaScript

Database/Real-Time Data: Firebase

Location Processing: Geocoder APIs

Deployment: Railway (https://railway.app)

🔧 Getting Started (Local Setup)
Note: Deployment on Railway is already live. For local development, follow these steps:

Clone the Repository

bash
Copy
Edit
git clone https://github.com/Ravithakurofficial/Acoustic-Direction-Finder.git
cd adf-app
Configure Environment

Create an application.properties file in src/main/resources and add:

ini
Copy
Edit
spring.datasource.url=jdbc:mysql://<host>:<port>/<db>
spring.datasource.username=<username>
spring.datasource.password=<password>
firebase.apiKey=<your-firebase-api-key>
geocoder.apiKey=<your-geocoder-api-key>
Run the Application

bash
Copy
Edit
./mvnw spring-boot:run
Use Locally
Open http://localhost:8080 in your browser to test the direction finder features.

✅ Usage Instructions
On the live site or local environment:

Allow access to your microphone.

Speak or play a tone.

Observe the live directional indicator UI respond in real time.

Explore stored session data, logs, or geolocation overlays via the Firebase-connected sections.

🧪 Testing
Unit & Integration Tests
Run using Maven:

bash
Copy
Edit
./mvnw test
Frontend Behavior

Open dev tools console to view live logs and coordinate updates.

Confirm sound direction matches expected source orientation.

🛠️ Deployment
Railway Integration

Linked GitHub repo triggers automatic deployment on main branch.

Environment variables (Firebase, DB, Geocoder, etc.) set up via Railway dashboard.

CI/CD
Implemented via Railway’s Deploy Hooks or GitHub Actions for smooth updates.

🙌 Contributing
Contributions are welcome! To contribute:

Fork the repository and create a feature branch (git checkout -b feature/X)

Implement enhancements or bug fixes

Submit a pull request detailing your changes

📝 Future Enhancements
Support for multi-channel or directional microphone arrays.

AI‑driven source classification (e.g. voice vs. ambient noise).

3D UI visualization (e.g. WebGL sphere pointer).

Mobile-friendly responsive layout and mobile browser mic access.

📫 Contact & Support
For questions or feedback, please reach out to your-thakurravikumar400@gmail.com
