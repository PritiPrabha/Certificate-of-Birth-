# 🍼 Online Birth Registration & Monitoring Information Record System  

## 📌 Project Overview  
This is a **frontend-only prototype** of an **Online Birth Registration and Monitoring Information Record System**, developed using **HTML, CSS, JavaScript, and Bootstrap**.  
It provides a **digital platform** where:  
- 🏥 **Hospitals** can upload newborn details and generate a **Hospital ID**.  
- 👨‍👩‍👦 **Parents** can register births using the Hospital ID, track application status, and download certificates.  
- 🏢 **Registrars/Admins** can approve/reject applications and manage records.  

The system uses **LocalStorage** in the browser to simulate database storage and record tracking.  

---

## 🎯 Features  
### Citizen/Parent  
- Register birth using Hospital ID  
- Track application status (Pending, Approved, Rejected)  
- Download digital birth certificate (with dummy QR code)  

### Hospital  
- Upload newborn details (DOB, Gender, Weight, Place of Birth)  
- Auto-generate **Hospital ID** for parents to use during registration  
- View uploaded records  

### Admin/Registrar  
- View all pending applications  
- Approve/Reject applications  
- Generate certificate after approval  

### General  
- Interactive **Home Page** with role-based access  
- Responsive design using **Bootstrap**  
- Works offline (data stored in LocalStorage)  

---

## 🛠️ Tech Stack  
- **HTML5** → Structure  
- **CSS3 + Bootstrap 5** → Styling, responsive layout  
- **JavaScript (Vanilla)** → Form validation, LocalStorage, dynamic UI  


---

## 📂 Project Structure  
