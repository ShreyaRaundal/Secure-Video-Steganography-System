# Secure-Video-Steganography-System

## 📌 Project Overview

This project implements a **secure data-hiding and sharing system** by integrating **Steganography**, **Cryptography**, and **Visual Secret Sharing (VSS)**.
It ensures **multi-layered security** for sensitive information by hiding it within files (e.g., images, QR codes, or video frames), encrypting it, and further splitting it into secret shares.

 **Why this system?**
Single-method security systems (only encryption or only steganography) are vulnerable. Our approach overcomes these weaknesses with **multi-level protection**, ensuring confidentiality, integrity, and robustness against unauthorized access.

---

## 🚀 Key Features

* **Multi-Layered Security** → Steganography + Cryptography (MD5 hashing) + Visual Secret Sharing
* **Custom Encoding/Decoding** → Converts text into “meaningful sentences” and retrieves original message via decoding
* **Visual Secret Sharing (VSS)** → Splits secret image/video into shares that reveal the secret only when combined
* **Data Hiding in QR Codes** → Embeds encrypted data inside QR codes
* **User-Friendly Java GUI** → Intuitive interface for hiding and retrieving data

---

## 🛠️ Technologies Used

* **Language:** Java 
* **Database:** MySQL
* **IDE:** Eclipse
* **Connector:** MySQL JDBC
* **OS:** Windows

---

## 📂 Project Setup

### ✅ Prerequisites

* Java JDK 8 or higher
* Eclipse IDE
* MySQL Database
* MySQL JDBC Connector (JAR file)

### ⚡ Installation Steps

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/Secure-Video-Steganography-System.git
   ```

2. **Import into Eclipse**

   * `File > Import > General > Existing Projects into Workspace`
   * Select the cloned project

3. **Setup MySQL Database**

   * Create a new database in MySQL
   * Run SQL script from `/database` folder

4. **Configure Database Connection**

   * Edit `DBConnection.java`
   * Update `URL`, `username`, and `password`

5. **Run Application**

   * Right-click `Main.java` → `Run As > Java Application`

---

## 📊 Project Methodology

The project follows the **Iterative SDLC Model**, allowing step-by-step development with incremental improvements.
Each iteration added new features, tested modules, and refined security mechanisms.

---

## 📐 UML Diagrams

Diagrams are available in the [`/docs/uml`](./docs/uml) folder:

* **Use Case Diagram** – User interactions
* **Class Diagram** – Static structure of system
* **Activity Diagram** – Workflow & processes

---

## 👨‍💻 Contributors

* **Athare Samruddhi Sunil**
* **Kakade Shubhangi Hanuman**
* **Khan Umama Iliyas**
* **Raundal Shreya Narayan**

📌 **Project Guide:** *Prof. R. N. Devray*

---

✨ *This project demonstrates how combining multiple security techniques can create a more reliable and resilient system for data protection.*



<img width="863" height="423" alt="image" src="https://github.com/user-attachments/assets/22d0bbba-b972-418f-a589-961bd27ac5d0" />

<img width="826" height="425" alt="image" src="https://github.com/user-attachments/assets/1a2f5552-dfa0-4099-a52d-5ae9c0d1cd1b" />

<img width="876" height="409" alt="image" src="https://github.com/user-attachments/assets/584f7d61-34ba-4e51-b36c-4d9ee5cef8f6" />

<img width="882" height="405" alt="image" src="https://github.com/user-attachments/assets/7786f1cc-c593-4289-a0aa-701c9fb9cbed" />

<img width="839" height="417" alt="image" src="https://github.com/user-attachments/assets/dfe72832-21ad-4002-8493-482d89844326" />

<img width="829" height="419" alt="image" src="https://github.com/user-attachments/assets/f19d3123-ceed-4754-87df-fe790147c258" />





