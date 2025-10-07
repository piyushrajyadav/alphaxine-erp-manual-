# 📘 ALPHAXINE ERP - ADMINISTRATOR USER MANUAL

**Version:** 1.0  
**Last Updated:** October 2025  
**For:** System Administrators & HR Managers

---

---

## 1. Introduction

### About Alphaxine ERP
Alphaxine ERP is a comprehensive Enterprise Resource Planning system designed to streamline business operations, human resources, and customer relationship management.

### Administrator Role
As an Administrator, you have full access to all system features and are responsible for:
- Managing employees and their information
- Approving/rejecting leave and timesheet requests
- Configuring organizational structure
- Overseeing CRM workflows
- Generating reports and analytics
- Managing system settings

### System Requirements
- **Browser:** Chrome 90+, Firefox 88+, Edge 90+, Safari 14+
- **Internet Connection:** Stable broadband connection
- **Screen Resolution:** Minimum 1366x768 (1920x1080 recommended)

---

## 2. Getting Started

### 2.1 Logging In

1. Navigate to: `http://93.127.199.72:3000/`
2. Enter your admin credentials:
   - **Email:** your.email@alphaxine.com
   - **Password:** Your secure password
3. Click **"Login"**

**First Login:**
- You will be prompted to change your password
- Create a strong password with:
  - Minimum 8 characters
  - At least one uppercase letter
  - At least one lowercase letter
  - At least one number
  - At least one special character

### 2.2 Dashboard Navigation

After logging in, you'll see the **Admin Dashboard** with:
- **Top Navigation Bar:** Profile, notifications, logout
- **Sidebar Menu:** Access to all modules
- **Main Content Area:** Module-specific content
- **Quick Stats Cards:** Key metrics at a glance

---

## 3. Dashboard Overview

### 3.1 Admin Dashboard Features

The Admin Dashboard displays:

#### Key Metrics Cards
- **Total Employees:** Active employee count
- **Active Employees:** Currently working employees
- **Line Managers:** Employees with managerial roles
- **Departments:** Total departments in organization
- **Designations:** Total job positions
- **Office Locations:** Number of office sites

#### Upcoming Birthdays Widget
- View employees with birthdays in current month
- Send birthday wishes directly

#### Pending Approvals
- Leave requests awaiting approval
- Timesheet submissions pending review
- CRM workflow approvals

#### Quick Actions
- Add New Employee
- Process Payroll
- Generate Reports
- View Attendance

---

## 4. Employee Management

### 4.1 Adding a New Employee

**Navigation:** Sidebar → **Employees** → **Add Employee**

**Steps:**

1. **Basic Information**
   - Employee ID (auto-generated or manual)
   - First Name *
   - Last Name *
   - Email Address *
   - Phone Number
   - Alternative Phone Number

2. **Personal Details**
   - Full Name
   - Gender (Male/Female/Other)
   - Date of Birth
   - Marital Status (Single/Married/Divorced/Widowed)

3. **Employment Information**
   - Department * (select from dropdown)
   - Designation * (select from dropdown)
   - Hire Date *
   - Employee Type (Full-Time/Part-Time/Contract/Intern)
   - Salary
   - Manager ID (if applicable)
   - Office Location
   - Is Line Manager? (Yes/No)

4. **Government IDs**
   - Aadhar Number (12 digits)
   - PAN Number (10 characters)
   - PF Number
   - UAN Number

5. **Bank Details**
   - Bank Name
   - Bank Account Number
   - IFSC Code (if applicable)

6. **Address Information**
   - Street Address
   - City
   - State
   - Postal Code

7. **System Access**
   - User ID (auto-generated)
   - Default Password: `user1234`
   - User must change password on first login

8. Click **"Submit"** to create employee record

**Note:** Fields marked with * are mandatory.

### 4.2 Viewing Employees

**Navigation:** Sidebar → **Employees** → **View Employees**

**Features:**
- **Table View:** See all employees in a list
- **Expandable Details:** Click arrow (►) to see complete employee information
- **Profile Pictures:** View employee photos or initials
- **Search & Filter:** Find employees quickly
- **Status Indicators:** Active/Inactive status badges

**Displayed Information:**
- Serial Number
- Profile Photo
- Employee ID
- Name
- Email
- Department
- Designation
- Phone
- Hire Date
- Status
- Actions (Edit, Deactivate, Delete)

### 4.3 Editing Employee Information

**Two Ways to Edit:**

#### Method 1: Inline Editing (Basic Fields)
1. Click **"Edit"** button in the Actions column
2. Fields become editable directly in the table
3. Modify required information
4. Click **"Save"** to update or **"Cancel"** to discard

**Editable in Table View:**
- Employee ID
- First Name / Last Name
- Email
- Department
- Designation
- Phone
- Hire Date

#### Method 2: Expanded View Editing (All Fields)
1. Click the expand arrow (►) next to employee name
2. Click **"Edit"** button in Actions column
3. ALL fields in expanded view become editable, including:
   - Personal Information (5 fields)
   - Government IDs (4 fields)
   - Bank Details (3 fields)
   - Address (4 fields)
   - Organizational Details (5 fields)
4. Make changes to any field
5. Click **"Save"** to update all changes

**Expanded View Sections:**
- **Personal Information:** Name, Gender, DOB, Marital Status, Alt Phone
- **Government IDs:** Aadhar, PAN, PF, UAN
- **Bank Details:** Bank Name, Account Number, Salary
- **Address:** Full address with city, state, postal code
- **Organizational:** Employee Type, Manager, Office Location, Line Manager status
- **Status & Metadata:** Created/Updated timestamps, slug

### 4.4 Deactivating/Activating Employees

**To Deactivate:**
1. Go to **View Employees**
2. Click **"Deactivate"** button for the employee
3. Employee status changes to "Inactive"
4. Employee cannot log in but data is preserved

**To Reactivate:**
1. Find inactive employee
2. Click **"Activate"** button
3. Employee can log in again

### 4.5 Deleting Employee Records

**⚠️ Warning:** This action is permanent and cannot be undone!

1. Go to **View Employees**
2. Click **"Delete"** button for the employee
3. Confirm deletion in popup dialog
4. Employee record is permanently removed

**Best Practice:** Use "Deactivate" instead of "Delete" to maintain historical records.

### 4.6 Changing Employee to Admin

**Navigation:** Sidebar → **System Settings** → **User Management**

**Steps:**
1. Search for the employee
2. Click **"Edit User Role"**
3. Select **"Admin"** from Role dropdown
4. Click **"Update Role"**
5. Employee now has admin privileges

**Alternative Method:**
1. Go to employee's profile
2. Edit User ID field
3. Assign to Admin role group
4. Save changes

---

## 5. Leave Management

### 5.1 Viewing Leave Requests

**Navigation:** Sidebar → **Leave** → **Leave Requests**

**Request Information:**
- Employee Name & ID
- Leave Type (Sick, Casual, Annual, etc.)
- Start Date & End Date
- Total Days
- Reason
- Applied Date
- Current Status (Pending/Approved/Rejected)

### 5.2 Approving Leave Requests

**Steps:**
1. Review leave request details
2. Check employee's leave balance
3. Verify dates and reason
4. Click **"Approve"** button
5. Add approval notes (optional)
6. Confirm approval

**Employee will receive notification of approval.**

### 5.3 Rejecting Leave Requests

**Steps:**
1. Review leave request
2. Click **"Reject"** button
3. **Add rejection reason** (mandatory)
4. Confirm rejection

**Employee will receive notification with rejection reason.**

### 5.4 Managing Leave Types

**Navigation:** Sidebar → **Leave** → **Leave Types**

**Available Leave Types:**
- Sick Leave
- Casual Leave
- Annual Leave
- Maternity Leave
- Paternity Leave
- Emergency Leave
- Study Leave
- Bereavement Leave

**To Add New Leave Type:**
1. Click **"Add Leave Type"**
2. Enter Type Name
3. Set Description
4. Set Active Status
5. Click **"Save"**

### 5.5 Managing Leave Allocations

**Navigation:** Sidebar → **Leave** → **View Leave Numbers**

**Features:**
- View all leave allocations
- Edit leave numbers for employees
- Set carry forward leaves
- Manage yearly allocations

**To Edit Leave Allocation:**
1. Find employee's leave record
2. Click **"Edit"** button
3. Modify:
   - Leave Type (dropdown)
   - Year (dropdown)
   - Number of Leaves (number)
   - Effective Date (date picker)
   - Carry Forward Leaves (number)
4. Click **"Save"**

**To Delete Leave Allocation:**
1. Click **"Delete"** button
2. Confirm deletion

### 5.6 Leave Balance Overview

**Navigation:** Sidebar → **Leave** → **Remaining Leave**

**View:**
- Employee-wise leave balances
- Total allocated leaves
- Used leaves
- Remaining balance
- Carry forward leaves

**Filter Options:**
- By Employee
- By Department
- By Leave Type
- By Year

---

## 6. Timesheet Management

### 6.1 Viewing Timesheets

**Navigation:** Sidebar → **Timesheet** → **Timesheet Management**

**Dashboard Shows:**
- All submitted timesheets
- Employee name and ID
- Date and client information
- Working hours and chargeable hours
- Leave type (if applicable)
- Status (Pending/Approved/Rejected)

### 6.2 Filtering Timesheets

**Available Filters:**
- **Employee:** Search by name or ID
- **Date Range:** From date to date
- **Status:** Pending/Approved/Rejected/All
- **Client:** Filter by client name

**To Apply Filters:**
1. Enter filter criteria
2. Click **"Apply Filters"**
3. Results update automatically

**To Clear Filters:**
- Click **"Clear Filters"** button

### 6.3 Approving Timesheets

**Steps:**
1. Review timesheet details:
   - Employee information
   - Date and client
   - Hours logged
   - Activity description
2. Verify accuracy
3. Click **"Approve"** button
4. Add approval notes (optional)
5. Confirm approval

**Bulk Approval:**
1. Select multiple timesheets using checkboxes
2. Click **"Approve Selected"**
3. Confirm bulk approval

### 6.4 Rejecting Timesheets

**Steps:**
1. Review timesheet
2. Click **"Reject"** button
3. **Enter rejection reason** (mandatory)
4. Confirm rejection

**Employee will need to resubmit corrected timesheet.**

### 6.5 Editing Timesheets

**Admin can edit submitted timesheets:**

1. Click **"Edit"** button on timesheet
2. Modify fields:
   - Employee Name
   - Date
   - Client Name
   - Assignment/Project
   - Working Hours
   - Chargeable Hours
   - Leave Type
   - Status
3. Click **"Update"** to save changes

### 6.6 Deleting Timesheets

**Steps:**
1. Click **"Delete"** button
2. Confirm deletion
3. Timesheet is permanently removed

### 6.7 Exporting Timesheets

**To Export to Excel/CSV:**
1. Apply desired filters
2. Click **"Export"** button
3. Select format (Excel/CSV)
4. File downloads automatically

**Exported Data Includes:**
- Employee Name
- Date
- Client Name
- Assignment
- Working Hours
- Chargeable Hours
- Leave Type
- Status

---

## 7. Attendance Management

### 7.1 Viewing Attendance Records

**Navigation:** Sidebar → **Attendance** → **View Attendance**

**Features:**
- Daily attendance overview
- Employee-wise attendance
- Clock in/Clock out times
- Total hours worked
- Late arrivals and early departures

### 7.2 Marking Attendance

**Manual Attendance Entry:**
1. Select employee
2. Select date
3. Choose status:
   - Present
   - Absent
   - Half-Day
   - On Leave
4. Enter clock in/out times (if present)
5. Add notes (optional)
6. Click **"Save"**

### 7.3 Attendance Reports

**Generate Reports:**
1. Go to **Attendance Reports**
2. Select date range
3. Select employees/departments
4. Click **"Generate Report"**
5. View or download report

**Report Types:**
- Daily Attendance Summary
- Monthly Attendance Report
- Employee Attendance History
- Department-wise Attendance
- Late Arrivals Report
- Absent Employees Report

---

## 8. Payroll Management

### 8.1 Processing Payroll

**Navigation:** Sidebar → **Payroll** → **Process Payroll**

**Steps:**
1. Select pay period (month/year)
2. Review employee list
3. Verify:
   - Basic salary
   - Allowances
   - Deductions
   - Attendance adjustments
   - Leave deductions
4. Click **"Calculate Payroll"**
5. Review calculated amounts
6. Click **"Process & Generate Payslips"**

### 8.2 Generating Payslips

**Individual Payslip:**
1. Go to **Payroll** → **Payslips**
2. Search for employee
3. Select month/year
4. Click **"Generate Payslip"**
5. Download PDF

**Bulk Payslips:**
1. Select pay period
2. Select employees (or all)
3. Click **"Generate All Payslips"**
4. Download ZIP file with all PDFs

### 8.3 Payroll Reports

**Available Reports:**
- Monthly Payroll Summary
- Department-wise Payroll
- Tax Deduction Report
- Bank Transfer Report
- Salary Register

---

## 9. CRM Management

### 9.1 Managing Leads

**Navigation:** Sidebar → **CRM** → **Leads**

**Features:**
- Add new leads
- Edit lead information
- Convert leads to clients
- Track lead status
- Assign leads to employees

**Lead Workflow:**
1. **New Lead** → 2. **Contacted** → 3. **Qualified** → 4. **Proposal** → 5. **Won/Lost**

### 9.2 Managing Clients

**Navigation:** Sidebar → **CRM** → **Clients**

**Client Information:**
- Company name
- Contact person
- Email and phone
- Address
- Industry
- Status (Active/Inactive)

**Actions:**
- Add new client
- Edit client details
- View client history
- Deactivate client

### 9.3 Managing Opportunities

**Navigation:** Sidebar → **CRM** → **Opportunities**

**Opportunity Stages:**
- Prospecting
- Qualification
- Proposal
- Negotiation
- Closed Won
- Closed Lost

**Kanban Board:**
- Drag and drop opportunities between stages
- Visual pipeline management
- Quick status updates

### 9.4 CRM Approvals

**Admin must approve:**
- New client additions
- Large opportunity amounts
- Proposal submissions
- Contract modifications

**Approval Process:**
1. Review submitted item
2. Check all details
3. Approve or Reject with comments
4. Notify submitter

---

## 10. Department & Designation Management

### 10.1 Managing Departments

**Navigation:** Sidebar → **Organization** → **Departments**

**To Add Department:**
1. Click **"Add Department"**
2. Enter:
   - Department Code (e.g., "SD", "FIN")
   - Department Name (e.g., "Software Development")
   - Location
   - Description
3. Click **"Save"**

**To Edit Department:**
1. Click **"Edit"** button
2. Modify information
3. Click **"Update"**

**To Delete Department:**
1. Click **"Delete"** button
2. **Note:** Cannot delete if employees are assigned
3. Reassign employees first

### 10.2 Managing Designations

**Navigation:** Sidebar → **Organization** → **Designations**

**To Add Designation:**
1. Click **"Add Designation"**
2. Enter:
   - Designation Code
   - Designation Name
   - Grade (Junior/Mid/Senior/Lead/Manager)
   - Description
3. Click **"Save"**

**To Edit/Delete:** Same process as departments

### 10.3 Managing Office Locations

**Navigation:** Sidebar → **Organization** → **Office Locations**

**Add Location:**
1. Click **"Add Location"**
2. Enter:
   - Location Name
   - Address
   - City, State, Country
   - Contact Information
3. Click **"Save"**

---

## 11. Shift Management

### 11.1 Creating Shifts

**Navigation:** Sidebar → **Shifts** → **Add Shifts**

**Steps:**
1. Enter Shift Name (e.g., "Morning Shift")
2. Set Start Time
3. Set End Time
4. Set Break Duration (minutes)
5. Select Working Days (Mon-Sun)
6. Click **"Create Shift"**

### 11.2 Assigning Shifts to Employees

**Navigation:** Sidebar → **Shifts** → **Assign Shifts**

**Steps:**
1. Select Shift from dropdown
2. Select Employee(s)
3. Set Effective From Date
4. Set Effective To Date (optional)
5. Click **"Assign"**

**Bulk Assignment:**
1. Select shift
2. Select multiple employees
3. Apply to all selected

### 11.3 Viewing Shift Assignments

**Navigation:** Sidebar → **Shifts** → **View Shifts**

**Features:**
- View all shift assignments
- Filter by shift, employee, or date
- Edit assignments
- Remove assignments

---

## 12. Reports & Analytics

### 12.1 Available Reports

**HR Reports:**
- Employee Master Report
- New Joiners Report
- Exit Report
- Department Strength Report
- Designation Distribution

**Leave Reports:**
- Leave Balance Report
- Leave Taken Report
- Leave Trend Analysis
- Department-wise Leave Report

**Attendance Reports:**
- Daily Attendance
- Monthly Attendance
- Late Arrivals
- Absent Employees
- Attendance Percentage

**Timesheet Reports:**
- Project-wise Timesheet
- Employee Productivity
- Client Billing Report
- Utilization Report

**Payroll Reports:**
- Salary Register
- Bank Transfer Report
- Tax Deduction Report
- Department-wise Payroll

**CRM Reports:**
- Lead Conversion Report
- Sales Pipeline
- Client Acquisition Report
- Revenue Forecast

### 12.2 Generating Reports

**Steps:**
1. Navigate to **Reports** module
2. Select Report Type
3. Set Parameters:
   - Date Range
   - Department/Employee
   - Additional Filters
4. Click **"Generate Report"**
5. View on screen
6. Download (PDF/Excel/CSV)

### 12.3 Scheduling Reports

**Auto-Generate Reports:**
1. Go to report settings
2. Click **"Schedule"**
3. Set:
   - Frequency (Daily/Weekly/Monthly)
   - Recipients (email addresses)
   - Format (PDF/Excel)
4. Click **"Save Schedule"**

**Reports will be auto-generated and emailed.**

---

## 13. System Settings

### 13.1 User Management

**Creating Admin Users:**
1. Go to **Settings** → **User Management**
2. Click **"Add User"**
3. Select Employee
4. Assign Role: **Admin**
5. Set Permissions
6. Click **"Create User"**

**Changing User Roles:**
1. Search for user
2. Click **"Edit"**
3. Change Role (Employee/Manager/HR/Admin/Super Admin)
4. Update Permissions
5. Click **"Save"**

### 13.2 Company Settings

**Navigation:** Settings → **Company Settings**

**Configurable:**
- Company Name
- Logo
- Address
- Contact Information
- Tax IDs
- Financial Year
- Working Days
- Holiday Calendar

### 13.3 Leave Configuration

**Settings → Leave Configuration**

**Configure:**
- Leave types and descriptions
- Annual leave quota per employee type
- Carry forward rules
- Leave accrual rules
- Maximum leaves per request

### 13.4 Attendance Settings

**Settings → Attendance Settings**

**Configure:**
- Work hours per day
- Late arrival threshold
- Early departure threshold
- Overtime calculation rules
- Break time rules

### 13.5 Notification Settings

**Settings → Notifications**

**Email Notifications:**
- Leave approvals/rejections
- Timesheet reminders
- Birthday notifications
- Payroll notifications
- System alerts

**Enable/Disable per type:**
- ☑ Email notifications
- ☑ In-app notifications
- ☑ SMS notifications (if configured)

---

## 14. Troubleshooting

### 14.1 Common Issues

#### Cannot Log In
**Solution:**
1. Verify correct email and password
2. Check if account is active
3. Clear browser cache
4. Try "Forgot Password" link
5. Contact IT support

#### Employee Not Showing in List
**Solution:**
1. Check if employee is marked as Active
2. Verify department assignment
3. Refresh the page
4. Check filters applied

#### Leave Balance Not Updating
**Solution:**
1. Verify leave allocation is created for current year
2. Check effective date of allocation
3. Approve pending leave requests
4. Refresh leave balance calculation

#### Timesheet Approval Not Working
**Solution:**
1. Verify timesheet status is "Submitted"
2. Check if you have approval permissions
3. Clear browser cache
4. Try different browser

### 14.2 Error Messages

**"Session Expired"**
- Log out and log in again
- Session timeout after 2 hours of inactivity

**"Permission Denied"**
- Contact Super Admin to grant required permissions
- Verify your role has necessary access

**"Data Not Saved"**
- Check internet connection
- Verify all required fields are filled
- Try again after refreshing page

### 14.3 Getting Help

**Support Channels:**
1. **Email:** support@alphaxine.com
2. **Phone:** +91-XXXX-XXXX
3. **Help Desk:** Available in system (top right corner)
4. **Documentation:** This manual and online help

**When Contacting Support, Provide:**
- Your name and email
- Description of the issue
- Steps to reproduce
- Screenshots (if applicable)
- Browser and OS version

---

## 15. Best Practices

### 15.1 Security

✅ **DO:**
- Change your password regularly (every 90 days)
- Use strong, unique passwords
- Log out after use, especially on shared computers
- Report suspicious activity immediately
- Review user access permissions regularly

❌ **DON'T:**
- Share your login credentials
- Write down passwords
- Leave your computer unlocked
- Use the same password across systems

### 15.2 Data Management

✅ **Best Practices:**
- Back up critical reports regularly
- Archive old data yearly
- Verify data accuracy before processing payroll
- Maintain audit trails
- Document all configuration changes

### 15.3 Employee Management

✅ **Guidelines:**
- Complete employee profiles thoroughly
- Update information promptly
- Use "Deactivate" instead of "Delete" for ex-employees
- Maintain proper documentation
- Conduct regular data audits

### 15.4 Approval Workflows

✅ **Tips:**
- Review requests within 48 hours
- Provide clear reasons for rejections
- Maintain consistency in decisions
- Document exceptions
- Communicate decisions promptly

---

## 16. Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| Search | `Ctrl + K` or `Cmd + K` |
| Go to Dashboard | `Alt + D` |
| Quick Add Employee | `Alt + E` |
| Logout | `Alt + Q` |
| Help | `F1` |
| Refresh Data | `F5` |

---

## 17. Appendix

### A. Glossary

**Active Employee:** Employee currently employed and able to log in  
**Chargeable Hours:** Hours that can be billed to client  
**Carry Forward:** Unused leaves moved to next year  
**Clock In/Out:** Attendance timestamp recording  
**Dashboard:** Main overview screen with key metrics  
**Designation:** Job title or position  
**Line Manager:** Employee who manages other employees  
**Payslip:** Salary payment document  
**Status:** Current state (Active/Inactive/Pending)  
**Timesheet:** Record of work hours and activities  
**UAN:** Universal Account Number (PF)

### B. Contact Information

**Alphaxine Technologies**  
Email: admin@alphaxine.com  
Website: www.alphaxine.com  
Support: support@alphaxine.com  

**System Administrator:**  
Email: sysadmin@alphaxine.com  

**HR Department:**  
Email: hr@alphaxine.com  

---

## 18. Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | October 2025 | Initial release |

---

**© 2025 Alphaxine Technologies. All rights reserved.**

*This manual is confidential and intended for authorized administrators only.*
