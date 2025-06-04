# Intelligent Campus Monitoring and Tracking System 🚀

## Project Overview
Our mini project develops an AI-driven facial recognition system to automate real-time student monitoring and enhance campus security. Traditional attendance methods face issues like manual errors and lack of real-time tracking. This system automates student identification at campus entry and exit points, improving accuracy and efficiency.

## Technology & Methodology 🧠
- **Face Detection:** Utilizes Multi-task Cascaded Convolutional Neural Network (MTCNN) for robust detection under diverse conditions.
- **Face Recognition:** Employs the ArcFace deep learning model to generate face embeddings and identify students with high accuracy.
- **Data Processing:** Matches captured face data against a secure student database containing register numbers and photographs.
- **Logging:** Records entry and exit timestamps in MySQL while avoiding duplicate logs within short intervals.

## Web Dashboard & Security 🖥️🔒
- Developed a responsive web dashboard using PHP and Bootstrap.
- Supports role-based access control for Admin, Head of Department (HOD), and Faculty.
- Includes management modules for students, batches, faculty, and departments.
- Provides real-time monitoring and alert notifications for uninformed student movements.

## Alerts & Impact 🔔
The alert system flags students entering or exiting without faculty notification, ensuring timely administrative actions. This reduces manual workload, enhances campus security, and offers scalable monitoring solutions for educational institutions.

## System Flowchart
![System Flowchart](images/System_workflow.pdf)

## Future Enhancements & Opportunities for Optimization ⚙️

While the system effectively automates student monitoring and improves campus security, several enhancements could further elevate its performance and scalability:

- **Adaptability to Challenging Environments:** Enhance accuracy in low lighting, with partial occlusions (e.g., masks, glasses), and evolving facial appearances to ensure consistent recognition in all scenarios.
- **Performance Optimization:** Streamline processing efficiency to better support real-time recognition in high-traffic environments with large student populations.
- **Dynamic Database Management:** Introduce automated checks and update mechanisms to keep student records current and accurate for reliable identification.
- **Strengthened Data Privacy & Security:** Implement advanced encryption and access control strategies to protect biometric data in compliance with privacy regulations.
- **Ethical Deployment & Transparency:** Incorporate clear policies, user awareness features, and consent mechanisms to maintain ethical standards in continuous monitoring environments.

These improvements aim to make the system even more reliable, scalable, and aligned with best practices in security and ethical AI use.




---

This project strengthened our skills in AI, computer vision, and web development, preparing us to deliver innovative automation solutions in education.
