🏥 Hospital Receptionist AI Assistant

An AI-powered medical receptionist built with n8n, AI Agent, Docker, and Render, designed to handle patient appointment scheduling in a friendly, professional, and efficient manner.

👉 **Live Demo:** [https://hospital-receptionist.onrender.com](https://hospital-receptionist.onrender.com)  

---

## 🚀 Features
  
-  ✅ Collects all required details for booking appointments:
  Patient Name
  Mobile Number (10 digits)
  Email Address
  Doctor’s Name & Specialization
  Hospital/Clinic Name
  Location (City/Area)
  Appointment Date & Time
  
  ✅ Behaves like a friendly receptionist (remembers details, avoids repeating, validates inputs).
  
  ✅ Stores patient details securely in Airtable.
  
  ✅ Automatically adds confirmed appointments into the clinic’s calendar (Google Calendar/Outlook compatible).
  
  ✅ Dockerized & hosted on Render for quick deployment.
  
  ✅ Provides a demo chat interface that feels natural and conversational.  

---

## 📦 Running Locally with Docker
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/hospital_receptionist.git
   cd hospital_receptionist

   ```

2.Build the Docker image:
```bash
  docker build -t hospital_receptionist .
```

3.Run the container:
```bash
docker run -d -p 8080:80 hospital_receptionist
```

4.Open in browser:
```bash
👉 http://localhost:8080
```
