# 🎓 Educational Management System on ServiceNow

A fully functional **Educational Management System** built on the **ServiceNow Platform (PDI)** to streamline and automate the admission process, student progress tracking, and centralized student data management — using low-code and no-code capabilities.

---

## 🎬 Demo

📺 **Watch Demo Video**  
🔗 [Click to View on Google Drive](#) *([Demo Video](https://drive.google.com/file/d/1IK-KkvGKIq3eBN5_hscPXYRqqfPmJSlB/view?usp=sharing))*

---

## 👥 Team Members

- **Akash Raj H** – Team Leader  
- **Dhanush B** – Table & Data Management  
- **Delhi Ganesh S** – Script & Form Design  
- **Manoj Kumar S** – Workflow & Role Access

---

## 📌 Project Overview

### 🎯 Purpose

To **digitize and streamline educational workflows** such as admissions, student tracking, and academic performance evaluation using the **ServiceNow platform** — reducing manual effort, eliminating redundancy, and improving overall accuracy and accessibility.

---

## ✨ Key Features

- 🔢 **Auto-Generated Admission Numbers** using Number Maintenance  
- 📍 **Address Auto-Fill** from Pincode (Mandal, City, District)  
- 📊 **Student Progress Tracking** with:
  - Subject-wise marks
  - Auto-calculated Total, Percentage, and Result (Pass/Fail)
- 🔄 **Admission Workflow** (New → Under Review → Approved/Rejected)  
- 🔐 **Role-Based Access** (Admin, Teacher, Student)  
- 🧩 **Modular Structure** for ease of use and maintenance

---

## 🛠️ Tech Stack

| Layer      | Technology                          |
|------------|--------------------------------------|
| Platform   | ServiceNow (Personal Developer Instance) |
| UI         | Form-based modules, Form Design     |
| Logic      | Client Scripts (onChange, onLoad), UI Policies |
| Database   | ServiceNow Tables (`nm_project`, `Admission`, `Student Progress`) |
| Deployment | Cloud-hosted via ServiceNow PDI     |

---

## ⚙️ How to Run the Project

1. 🔗 Go to [developer.servicenow.com](https://developer.servicenow.com)
2. 🛠️ **Create a Personal Developer Instance (PDI)**
3. 📁 In your instance, go to:
   - `System Update Sets → Retrieved Update Sets`
4. ⬆️ **Import** the Update Set located in the `/UpdateSets/` folder (shared with your project files)
5. ✅ **Preview & Commit** the Update Set
6. 🔍 Navigate through the application via the **nm project** menu:
   - `nm_project` (Student Master)
   - `Admission`
   - `Student Progress`

---

## 🖥️ Screenshots / Output

- 🧾 Admission Form with Auto-Fill & Status Flow  
- 📊 Student Progress Form with Calculated Fields  
- 🔢 Admission Numbers Auto-Generated  
- 🔐 Role-Based Views (Admin / Teacher / Student)  
*(Include screenshots here or link to Google Drive)*

---

## 🔮 Future Enhancements

- 📱 Mobile Interface for Students & Teachers  
- 📈 Analytics Dashboard to monitor trends  
- 📧 Notification System (Email/SMS alerts)  
- 🤖 AI Integration (Chatbot for Enquiry Handling)  
- ☁️ Multi-Institution Support via Scoped Apps

---

## ✅ Conclusion

The **nm project** effectively demonstrates the capabilities of **ServiceNow** to solve real-world problems in education. With automated workflows, smart scripting, and scalable design, this application can easily be extended across schools, colleges, and academic groups.

---

> 🛡️ Built with passion on the ServiceNow PDI  
> 💡 Project Type: Academic / Proof-of-Concept  
> 📚 Domain: Educational Technology
