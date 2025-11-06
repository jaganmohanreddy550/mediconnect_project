# 🏥 MediConnect – Salesforce Appointment & Prescription Manager

### 📘 Overview
**MediConnect** is a Salesforce-based healthcare management application designed to simplify appointment scheduling, prescription tracking, and doctor–patient communication.  
Built with Salesforce **Lightning App Builder, Flows, Apex, and LWC**, the system enables hospitals, clinics, and doctors to automate daily operations and enhance patient experience.

---

### 🚀 Features
- **Appointment Management:** Patients can book appointments anytime; doctors can view and manage schedules.
- **Prescription Management:** Doctors can create, update, and send digital prescriptions.
- **Automation with Flows:** Automatic appointment confirmations, reminders, and missed-visit tracking.
- **Role-Based Access:** Admin, Doctor, Receptionist, and Patient roles with tailored permissions.
- **Reports & Dashboards:** Real-time visual analytics for appointments, prescriptions, and performance tracking.
- **Email Notifications:** Sends confirmation and reminder emails to patients and doctors.
- **Integration Ready:** Supports APIs for pharmacy or lab test integrations using Named Credentials and Callouts.
- **LWC Interface:** Modern, responsive UI built with Lightning Web Components.

---

### 🧩 Salesforce Components
- **Custom Objects:**  
  `Patient__c`, `Doctor__c`, `Appointment__c`, `Prescription__c`
- **Automation:**  
  - Record-triggered Flows (auto-confirm appointments)  
  - Scheduled Flows (daily reminders, missed appointments)  
  - Apex Triggers and Batch Jobs  
- **Lightning App Pages:**  
  - Patient Dashboard  
  - Doctor Dashboard  
  - Appointment Management  
  - Prescription Management  
- **Reports & Dashboards:**  
  - Doctor-wise Appointments  
  - Prescription Summary  
  - MediConnect Overview Dashboard

---

### 🧠 Tech Stack
- **Platform:** Salesforce (Developer Edition / Sandbox)
- **Backend:** Apex Classes, Triggers, Batch & Queueable Jobs
- **Frontend:** Lightning Web Components (LWC)
- **Automation:** Salesforce Flow, Process Builder
- **Analytics:** Reports and Dashboards
- **Integration:** REST APIs, Named Credentials, Platform Events

---

### 📊 Reports & Dashboards
| Report | Description |
|--------|--------------|
| Doctor-wise Appointments | Total appointments per doctor |
| Patient Visit Summary | Patient visit history |
| Prescription Summary | Prescription count per doctor |
| MediConnect Overview Dashboard | Combined visual of key metrics |

---

### 🧪 Testing Summary
| Role | Function Tested | Result |
|------|------------------|--------|
| Admin | User creation, reports, dashboards | ✅ Successful |
| Doctor | Appointment & prescription creation | ✅ Successful |
| Receptionist | Appointment booking & confirmation | ✅ Successful |
| Patient | Email notification & record access | ✅ Successful |

All test cases passed with **100% functionality coverage**.

---

### 🎥 Project Demo
📽 **Watch the live demo here:**  
[https://drive.google.com/file/d/1oQpbDQGkpRYXyb-z3sNe8O2f7wy1oWpU/view?usp=drivesdk](https://drive.google.com/file/d/1oQpbDQGkpRYXyb-z3sNe8O2f7wy1oWpU/view?usp=drivesdk)

---

### 📦 Deployment Steps
1. Create or log in to your **Salesforce Developer Org**.
2. Create custom objects: `Patient`, `Doctor`, `Appointment`, `Prescription`.
3. Add relationships, page layouts, and profiles.
4. Import provided **Apex Classes** and **LWC Components**.
5. Set up **Flows** for automation (confirmation, reminders).
6. Configure **Reports and Dashboards**.
7. Deploy via **Change Set** or **SFDX CLI** to production.

---

### 🧰 Tools Used
- **Salesforce Developer Console**
- **Visual Studio Code with SFDX**
- **Salesforce CLI**
- **Data Loader**
- **Change Sets**
- **Lightning App Builder**

---

### 🧑‍💻 Author
**Jammala Jagan Mohan Reddy**  
_B.Tech – Computer Science and Engineering (CSE)_  
KSRM College of Engineering, Kadapa  

---

### 🏁 Conclusion
MediConnect demonstrates how Salesforce can revolutionize healthcare systems by offering a **smart, automated, and secure** solution for hospitals and clinics.  
It simplifies appointment scheduling, strengthens doctor–patient communication, and delivers data-driven insights through powerful dashboards.

---

© 2025 MediConnect Project | Built with 💙 using Salesforce Platform
