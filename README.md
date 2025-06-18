# 🗳️ Smart Election Voting System using Face Recognition

A secure, face recognition–based voting system built using Python, OpenCV, and K-Nearest Neighbors (KNN). It enables real-time voter authentication, prevents duplicate voting, and ensures accurate, tamper-proof voting records.
---
## 🚀 Features

- Real-time face detection and recognition using webcam
- Secure registration and authentication of voters
- Prevents duplicate voting via Aadhaar number mapping
- Records vote details (Aadhaar, vote, date, time) into `Votes.csv`
- Basic UI with background image using OpenCV
- Text-to-speech feedback using Windows SAPI (win32com)
---
## 🛠️ Technologies Used
- **Language:** Python
- **Libraries:** OpenCV, NumPy, scikit-learn (KNN), Pickle, CSV, win32com (SAPI), OS
---
![Image](https://github.com/user-attachments/assets/1439702c-ad0d-41cd-ad1c-20f41f74dc8a)
## 📁 Project Structure
```bash
.
├── data/                   # Directory to store registered face data (created at runtime)
├── Votes.csv               # CSV log of votes with Aadhaar number, vote, date, and time
├── add_faces.py            # Script to register user's face and store face data
├── give_vote.py            # Voting interface: detects, authenticates, and logs the vote
├── background.png          # Background image used for the OpenCV-based UI
├── requirements.txt        # List of Python dependencies
├── README.md               # Project documentation (this file)

