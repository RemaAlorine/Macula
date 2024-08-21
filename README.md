# Macula: Online Engagement Monitoring Platform
![unnamed](https://github.com/user-attachments/assets/358c505f-1cc3-45fe-b783-2136e61194db)

## Overview

Macula is a web-based application designed to monitor student engagement in real-time using computer vision. The platform automates attendance tracking, enhances participation through gamification, and offers real-time feedback to educators.

## Implementation Platform

### Web Application
- **Visual Studio Code:** A lightweight and powerful source code editor with built-in support for JavaScript, TypeScript, and Node.js.
- **MERN Stack:** 
  - **MongoDB** — Document database
  - **Express.js** — Node.js web framework
  - **React.js** — Client-side JavaScript framework
  - **Node.js** — JavaScript web server
- **Postman:** Used for testing the API endpoints, ensuring the robustness of the application.

### User Interface Design
- **Figma:** Utilized to create UI components and mockups for Macula, enabling collaboration and feedback during the design process.

### Algorithms

#### Face Recognition
![Screenshot (233)](https://github.com/user-attachments/assets/86946fed-36a0-4e22-9835-b7869ba4b5b6)
- **face-api.js:** Built on top of TensorFlow.js, used for face detection, recognition, and landmark detection. The algorithm extracts face descriptors and compares them to reference data to determine similarity.

#### Engagement Monitoring and Reports
![Picture2](https://github.com/user-attachments/assets/e68fa4f4-e9c1-4a1c-993b-58bd0e6c10a7)

- **Python Script:** Real-time engagement monitoring using facial landmarks and computer vision techniques. The script tracks eye and mouth movements, head pose, and engagement status, storing the data in a MongoDB database.

## Features
- **Real-Time Face Recognition:** Implemented using `face-api.js` for live video streams.
- **Engagement Monitoring:** Tracks student focus, distraction, and participation levels during sessions.
- **Automated Attendance Tracking:** Monitors and records attendance without manual input.



![Picture3](https://github.com/user-attachments/assets/da95e28d-8b09-4bc1-90d1-43f91509e121)

