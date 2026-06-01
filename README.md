# Serverless React Native CRUD (Firebase Firestore)

## 📌 Overview
A mobile application built with React Native and Expo, showcasing a **Cloud-Native / Serverless** approach by integrating directly with Firebase Firestore for real-time data management.

## ⚙️ Core Features & Architecture
* **Serverless Backend (BaaS):** Eliminates the need for a traditional backend server by utilizing Firebase Firestore (NoSQL document database) for data persistence.
* **Real-Time Synchronization:** Implements Firestore's `onSnapshot` listener to push real-time state updates to the UI, ensuring data consistency across multiple clients without manual polling.
* **Asynchronous Operations:** Fully asynchronous CRUD (Create, Read, Delete) operations handling cloud latency and potential network failures gracefully.
* **Cross-Platform:** Built using Expo to compile natively for both iOS and Android from a single JavaScript codebase.

## 🚀 Relevance for Cloud / SRE
For a Site Reliability Engineer or Cloud Engineer, understanding how modern front-end clients interact with cloud-managed services (like Firebase/AWS Amplify) is crucial. This project demonstrates hands-on knowledge of NoSQL database interactions, asynchronous payload handling, and serverless architecture principles.

*Tech Stack: React Native, JavaScript (ES6), Firebase Firestore (NoSQL), Expo.*
