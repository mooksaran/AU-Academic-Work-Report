# AU Academic Work Report

> A web application designed to digitize and streamline the academic remuneration process for Assumption University (ABAC) lecturers and administrators.

---

## 📌 Project Overview

The **AU Academic Work Report** system aims to modernize the traditionally manual workflow of lecturer compensation by creating a web-based platform. This system enables academic title holders to submit their work records, which are then reviewed and verified by multiple university departments in a structured and secure digital flow.

---

## 🎯 Objectives

- Simplify the submission process for teaching, advising, and research-related work
- Provide role-based workflows for Dean, HR, Academic Affairs, IRAS, and University Committee
- Enable Microsoft ID login for authentication
- Facilitate centralized access to form statuses and remuneration data
- Enhance transparency and reduce paper-based processing

---

## 📂 Features

- Microsoft Login (via Azure AD)
- Academic Work Report Form (AW1)
- Certification of Co-Author's Contribution (AW2)
- Teaching, Advising, and Research categories
- Role-based views for each department
- Verification stages with audit trail
- Simple and responsive UI

---

## 🛠️ Technologies Used

| Technology       | Role                              |
|------------------|-----------------------------------|
| Apache           | Web server                        |
| PHP (v7.4.33)    | Backend development               |
| MariaDB          | Database                          |
| Microsoft Azure  | Authentication with Microsoft ID  |
| HTML / CSS       | Frontend layout                   |

---

## 📁 Folder Structure

```
AU-Academic-Work-Report/
├── README.md
├── LICENSE
├── .gitignore
├── docs/
│   ├── Proposal_SP2_AUAcademicWorkReport.pdf
│   ├── SP2_REPORT_AU_ACADEMIC_WORK_REPORT.pdf
├── forms/
│   ├── AW1-AcademicWorkReportForm.pdf
│   └── AW2-AcademicWorkReportForm.pdf
├── src/
│   ├── backend/
│   │   ├── index.php
│   │   ├── auth_microsoft.php
│   │   └── db_config.php
│   ├── frontend/
│   │   ├── index.html
│   │   └── styles.css
│   └── database/
│       └── schema.sql
├── utils/
│   └── architecture_diagram.png
└── data/
    ├── Users.xlsx
    └── new_users.xlsx
```

---

## 🚀 How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/AU-Academic-Work-Report.git
cd AU-Academic-Work-Report
```

### 2. Setup Environment

- Install [XAMPP](https://www.apachefriends.org/index.html) or any Apache + PHP + MySQL stack
- Place the project under the `htdocs/` directory
- Create a database using the schema from `src/database/schema.sql`
- Update database credentials in `src/backend/db_config.php`

### 3. Run the App

- Start Apache and MySQL from your local server
- Open browser and go to `http://localhost/AU-Academic-Work-Report/src/frontend/index.html`
- Login using your Microsoft ID

---

## 📑 References

- Microsoft Azure Login Docs: https://learn.microsoft.com/en-us/azure/active-directory/develop/
- PHP Documentation: https://www.php.net/manual/en/
- MariaDB Documentation: https://mariadb.com/kb/en/documentation/
- Apache HTTP Server Project: https://httpd.apache.org/
- MLA Citation Guide: https://style.mla.org/

---

## ✍️ Authors

- **Sakar Karmacharya** (6218332)
- **Saranya Sangsuk-iem** (6237407)  
  *Advisor: Ajan Suparwat C.*

---

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.
