# Employee-Recognition-and-Rewards
A Custom Salesforce-based solution using standard automation.  Automates employee data evaluation using formula fields  and workflow rules. Calculates task and attendance performance. Auto-assigns appropriate rewards with zero manual effort  Enables dashboards for leadership visibility

# Employee Recognition &  Rewards(Salesforce Project)

## 📌 Project Overview
The **Employee Rewards & Recognition Tracker** is a Salesforce Admin-based application that enables structured recognition of employees and automated rewards distribution.  
This project was built entirely with **Salesforce Admin tools (no Apex, no external apps)**.

---

## 🚀 Features
- **Employee Data Management** – Custom object to store employee details with fields for name, department, performance score, attendance %, and task completion %.
- **Top Performer Identification** – Automatically identifies top 4–5 employees every 6 months based on performance criteria.
- **Automated Rewards** – Assigns rewards (Vacation, Hike, Bonus, Coupons) using Salesforce Flows.
- **Email Notifications** – Sends automated reward emails to top performers.
- **Reports & Dashboards** – HR and Leadership can view top performers, department breakdowns, and trends.
- **Access Control** – Profiles and permissions configured (Admin, HR Manager, Employees).

---

## ⚙️ Tools & Features Used
- **Object Manager** → Custom objects and fields
- **Profiles** → Access control
- **Flows** → Automated reward assignment + email alerts
- **Reports & Dashboards** → Data visualization
- **Email Templates** → Reward notifications

---

## 🛠️ Implementation Steps
1. **App Creation**  
   - Created Employee Recognition Tracker App (Classic + Lightning)
   - Tabs: Home, Employees, Dashboards, Reports

2. **Custom Object**  
   - `Employee Data` with fields:
     - Employee Name
     - Employee ID
     - Attendance Percentage
     - Task Completion Percentage
     - Performance Score
     - Reward Type
     - Rank

3. **Profiles & Users**  
   - HR Manager profile
   - System Admin, HR Manager, and Employees with specific permissions

4. **Flow Automation**  
   - **Scheduled Trigger Flow** runs every 6 months  
   - Identifies top 4 performers (Attendance > 90%, Performance > 0.9, Tasks > 90%)  
   - Assigns rewards by rank (Vacation, Hike, Bonus, Coupons)  
   - Sends reward emails

5. **Reports & Dashboards**  
   - Reports:
     - Recognized Employees
     - Top Performer Count by Department
     - Attendance vs Task Completion
   - Dashboard:
     - Employee Recognition Dashboard (with bar, pie, line charts)

---

## 📊 Sample Reports/Dashboard
- **Recognized Employees Report**
  | Employee Name | Department | Score | Reward | Rank |
- **Dashboard Charts**
  - Top Performers by Department
  - Attendance vs Task Completion
  - Reward Distribution

---

## ✅ Testing
| Test ID | Description | Expected Result | Status |
|---------|-------------|-----------------|--------|
| TC_01 | Custom object & field creation | All fields visible in object | Passed |
| TC_02 | Filter qualified employees | Correct list returned | Passed |
| TC_03 | Email sent to winners | 4 emails sent to top performers | Passed |

---

## 🔒 Security
- Only **Admins & HR Managers** can view dashboards and assign rewards.
- Employees can only see their own recognition.

---

## 🛠️ Tech Stack
- **Platform**: Salesforce Developer Edition
- **Tools**: Object Manager, Flows, Reports & Dashboards
- **Data**: 50 sample employees, 5 high performers

---

## 📂 Repository Contents
- `docs` → Project Report, PPT
- `data` → Sample Employee Data
- `flows` → Flow Diagrams
- `dashboards` → Dashboard screenshots

---

## 📜 License
This project is released under the MIT License.

### 1️⃣ Clone the repository  
- bash
https://github.com/vaishnavipabbineedi/Employee-Recognition-and-Rewards
