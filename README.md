# 🏠 Loan Verification & Asset Monitoring System

A digital **Loan Verification and Asset Monitoring System** developed during a hackathon to simplify loan application, verification, approval, and monitoring processes.

The application helps stakeholders submit loan-related information and construction/asset images, while enabling managers to verify the submitted information using **geo-tagged images**.

---

## 📌 Project Overview

In traditional loan verification, managers may need to manually collect documents and physically verify construction or assets. This application provides a digital workflow where beneficiaries can submit their information and upload evidence of their construction or assets.

For example, a beneficiary may have previously received a **₹2 lakh loan** for constructing the basement of a house. If an additional **₹3 lakh** is required to continue construction, the beneficiary can submit a new request along with updated construction images.

The uploaded images are processed with **location information (geo-tagging)** using Google Apps Script, allowing the manager to verify the submitted construction/asset information and its location.

---

## 🎯 Objectives

* Digitize the loan verification process
* Simplify beneficiary registration and loan applications
* Enable digital submission of construction/asset evidence
* Support **geo-tagged image verification**
* Provide role-based access for different users
* Help managers monitor and verify loan-related activities
* Improve transparency and reduce manual verification work

---

## 👥 User Interfaces

The system provides three main interfaces:

### 👨‍💼 Manager

* Login securely
* View submitted loan applications
* Review beneficiary details
* View uploaded construction/asset images
* Check geo-location information
* Verify submitted information
* Approve or manage loan requests

### 👤 Stakeholder / Beneficiary

* Register an account
* Login to the application
* Submit personal and loan details
* Apply for a loan
* Upload construction/asset images
* Submit information for verification
* Track the verification process

### 🛠️ Admin

* Manage users
* Manage application data
* Monitor system activities
* Manage overall application workflow

---

## 🔄 Application Workflow

```text
Stakeholder Registration
        ↓
Login
        ↓
Submit Personal & Loan Details
        ↓
Loan Application
        ↓
Upload Construction / Asset Images
        ↓
Google Apps Script
        ↓
Geo-Tag / Location Information
        ↓
Manager Verification
        ↓
Approval / Further Processing
        ↓
Loan Monitoring
```

---

## 📍 Geo-Tagged Image Verification

One of the important features of the application is **location-based image verification**.

When a stakeholder uploads construction or asset images, the application uses **Google Apps Script** to process the submitted information and associate it with geographical location data.

This helps the manager understand:

* Where the asset/construction is located
* What the current construction status is
* Whether the submitted images correspond to the registered location
* Whether additional verification is required

---

## 💡 Example Use Case

### Initial Loan

A beneficiary receives:

**₹2,00,000**

Purpose:

> Construction of the house basement

### Additional Loan Request

After completing the basement, the beneficiary requires:

**₹3,00,000**

Purpose:

> Further construction of the house

The beneficiary can submit the additional loan request and upload updated construction images.

```text
Previous Loan
₹2,00,000
    ↓
Basement Construction
    ↓
Updated Construction Images
    ↓
Additional Loan Request
₹3,00,000
    ↓
Manager Verification
    ↓
Approval / Processing
```

---

## ✨ Key Features

* 🔐 Role-based login
* 👤 Stakeholder registration
* 📝 Loan application
* 📄 Beneficiary information management
* 📷 Construction/asset image upload
* 📍 Geo-tagged image verification
* 👨‍💼 Manager verification
* ✅ Loan approval workflow
* 🛠️ Admin management
* 📊 Loan monitoring
* ☁️ Google Apps Script integration

---

## 🛠️ Technologies Used

| Technology                | Purpose                                |
| ------------------------- | -------------------------------------- |
| HTML                      | User interface                         |
| CSS                       | Styling and responsive design          |
| JavaScript                | Application functionality              |
| Google Apps Script        | Backend processing and automation      |
| Google Sheets             | Data storage/management                |
| Google Maps / Geolocation | Location information                   |
| GitHub                    | Version control and project repository |

---

## 🏗️ System Architecture

```text
              ┌─────────────────────┐
              │     Stakeholder     │
              │ Registration / Loan │
              └──────────┬──────────┘
                         │
                         ↓
              ┌─────────────────────┐
              │   Web Application   │
              └──────────┬──────────┘
                         │
                         ↓
              ┌─────────────────────┐
              │ Google Apps Script  │
              └──────┬────────┬─────┘
                     │        │
                     ↓        ↓
              ┌──────────┐  ┌─────────────┐
              │  Google  │  │ Geo-location│
              │  Sheets  │  │    Data     │
              └────┬─────┘  └──────┬──────┘
                   │               │
                   └───────┬───────┘
                           ↓
                 ┌──────────────────┐
                 │      Manager     │
                 │ Verification &   │
                 │     Approval     │
                 └──────────────────┘
```

---

## 🚀 Project Highlights

* Developed as a **Hackathon Project**
* Implements a complete loan verification workflow
* Supports multiple user roles
* Uses **Google Apps Script** for backend operations
* Enables image-based construction/asset verification
* Incorporates **geo-location information** for verification
* Designed to reduce manual loan monitoring activities

---

## 📂 Project Structure

```text
Loan-Verification-System/
│
├── index.html
├── login.html
├── manager.html
├── stakeholder.html
├── admin.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
├── google-apps-script/
│   └── Code.gs
└── README.md
```

---

## 🔮 Future Enhancements

* Mobile application integration
* Automated loan status notifications
* Advanced document verification
* Digital approval/signature
* Construction progress tracking
* Dashboard with loan analytics
* Improved offline functionality
* Integration with additional mapping services

---

## 👨‍💻 Developed During

**Hackathon Project**

### Project Focus

**Digital Loan Application • Verification • Geo-Tagged Asset Monitoring**

---

## 📜 License

This project was developed for educational and hackathon purposes.
