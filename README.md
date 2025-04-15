# 🏥 Hospital Management System

A web-based hospital management system built using Django with role-based functionalities for Admin, Doctor, and Patient.

---

## 📌 Functions

### 👨‍💼 Admin
- Signup/Login (No approval required).
- Register, view, approve, reject, and delete doctors (approve those who applied to work in the hospital).
- Admit, view, approve, reject, and discharge patients (discharge after treatment completion).
- Generate/Download invoice PDFs (based on medicine cost, room charge, doctor charge, and other charges).
- View, book, and approve appointments (approve those requested by patients).

### 🩺 Doctor
- Apply for a job in the hospital and login after admin approval.
- View assigned patient details (name, symptoms, mobile number).
- View discharged patients assigned to them (discharged by admin).
- View appointments assigned by admin.
- Delete appointments after attending them.

### 👨‍⚕️ Patient
- Create an account and login after admin approval.
- View assigned doctor details (specialization, mobile number, address).
- View booked appointment status (pending/confirmed by admin).
- Book appointments (approval required by admin).
- View and download invoice PDF (only after being discharged by admin).

---

## ⚙️ How to Run This Project

### ✅ Prerequisites

- Install **Python (3.7.6)**  
  *(Make sure to check "Add to PATH" during installation)*

### ✅ Install Dependencies

Open terminal and run:

```bash
pip install django==3.0.5
pip install django-widget-tweaks
pip install xhtml2pdf
