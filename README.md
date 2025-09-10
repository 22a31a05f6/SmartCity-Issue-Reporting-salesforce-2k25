# 🏙️ Smart City Issue Reporting & Resolution System  

## 📌 Project Overview  
The **Smart City Issue Reporting & Resolution System** is a digital platform that enables citizens to report civic issues such as potholes, garbage, drainage, and broken streetlights through an online portal.  
Built on **Salesforce Experience Cloud**, this solution streamlines the entire process of issue reporting, assignment, escalation, and resolution. It enhances **transparency, accountability, and service efficiency** by automating workflows and providing real-time dashboards for supervisors.  

---

## 👥 Team Members  
- **P. Nikhitha Sowmya (Team Lead)** – 22A31A05F6  
- T. Reshma Sri – 22A31A0522  
- N. S. Deepika – 22A31A43D9  
- K. Triveni – 22A31A05E6  
- N. Sireesha – 22A31A05F1  

**Institution:** Pragati Engineering College, Surampalem  
**Date:** 12-07-2025  

---

## 🎯 Objectives  
- Provide a **centralized citizen portal** for reporting and tracking issues.  
- Automate **case creation, routing, and escalation** using Salesforce.  
- Send **real-time email notifications** to keep citizens informed.  
- Offer **reports and dashboards** for monitoring performance.  
- Improve **urban governance through technology**.  

---

## 🔑 Key Features  
- ✅ **Citizen Portal** (Experience Cloud) with new issue and reopen case options.  
- ✅ **Automated Case Creation** via Flows.  
- ✅ **Assignment Rules** to route issues by type (Potholes → Roads Dept, Streetlights → Electrical Dept, etc.).  
- ✅ **Email Alerts** for case updates (Received, In Progress, Resolved).  
- ✅ **Escalation Rules** for overdue issues.  
- ✅ **Reopen Case Functionality** (after 7 days of closure).  
- ✅ **Reports & Dashboards** for supervisors to track trends and workloads.  

---

## 🛠️ Salesforce Components Used  
- Experience Cloud Site  
- Standard **Case Object** (with custom fields)  
- Screen Flows & Record-Triggered Flows  
- Assignment Rules, Escalation Rules, Auto Response Rules  
- Email Templates & Alerts  
- Custom Profiles, Roles, Queues, Permission Sets  
- Reports & Interactive Dashboards  

---

## 📊 Data Model – Custom Fields in Case  
| Field Name       | Data Type     | Description                          |
|------------------|--------------|--------------------------------------|
| Issue Type       | Picklist     | Pothole, Garbage, Streetlight, etc.  |
| Location         | Text         | Location of issue                    |
| Urgency          | Picklist     | High / Medium / Low                  |
| Attachment       | URL          | Proof (image or document)            |
| Citizen Contact  | Phone        | Contact number                       |
| Citizen Email    | Email        | For acknowledgment                   |
| Citizen Name     | Text         | Used in email templates              |
| Description      | Long Text    | Detailed description of issue        |

---

## 🚀 Workflow  
1. Citizen submits a new case or requests to reopen an existing one.  
2. Case is auto-created in Salesforce.  
3. Assignment rules route it to the correct department.  
4. Email notifications update citizens at each stage.  
5. Escalation rules trigger for overdue cases.  
6. Dashboards track overall progress and performance.  

---

## 📸 Screenshots  
- Citizen Portal Landing Page  
- Issue Submission Form  
- Case Reopen Form  
- Success & Error Screens  
- Reports & Dashboards  

(*Add screenshots in a `/screenshots` folder in this repo*)  

---

## 📈 Reports & Dashboards  
- **Tabular Reports** grouped by issue type and department.  
- **Donut & Bar Charts** showing workload distribution.  
- **Stacked Graphs** tracking resolution times.  
- Supervisor dashboards for **real-time monitoring**.  

---

## 🌐 Deployment  
- **Portal Name:** Smart City Portal  
- **Live Site (Developer Org – may expire):** [Smart City Portal](https://reshmasri-dev-ed.develop.my.site.com/s/)  

---

## 📥 Project Files  
- 📄 [Full Documentation PDF](./THE_SMART_CITY_ISSUE_REPORTING.pdf)  
- 📸 Screenshots folder  

---

## 🔮 Future Scope  
- Integration with **mobile applications** for on-the-go issue reporting.  
- AI-based **issue prioritization** for critical cases.  
- **GIS integration** to map issues geographically.  
- Public dashboards for greater transparency.  

---

## ✨ Conclusion  
The Smart City Issue Reporting & Resolution project demonstrates how **Salesforce Experience Cloud and automation tools** can transform civic issue management. By combining user-friendly portals, automated workflows, and data-driven dashboards, the solution ensures **efficient service delivery, citizen satisfaction, and improved governance**.  

---
