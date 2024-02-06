# User Guide

# For Kairos Leave App

## Revision History

| Date | Version | Author | Change description |
| --- | --- | --- | --- |
| 02/02/2024 | 1.0.0 | Nhu Phan | Init version |
| 05/02/2024 | 1.0.1 | Dat Nguyen |  |

### Table of contents

## **Introduction**

### **Purpose**

This document provides user detailed steps to use the Kairos Leave
App

### Object uses

- Admin: the most superior user in the system who manages everything regarded to the business. There is only one admin.
- Manager: equivalent to a team lead. Manager manages only his/her own members and their requests.
- Employee: the user with least authorities in the system. An employee can be a contracted employee, a freelancer, a part-timer, an intern.

### Scope:

- Settings (Admin)
- Position management (Admin)
    - Create position
    - List position
    - Delete position
    - Edit position
- Holidays management  (Admin)
    - List holidays
    - Create holidays
    - Edit holidays
    - Delete holidays
- Leave type management  (Admin)
    - List leave type
    - Create leave type
    - Edit leave type
    - Delete leave type
- Department management  (Admin)
    - List department
    - Create department
    - Edit department
    - Delete department
- Employee management  (Admin)
    - List employee
    - Create employee
    - Edit employee
    - View annual leave employee
    - Password recovery for employee
    - Create leave request
    - Switch user account
- Report an issue  (Admin/Manager/Employee)
- List approved leave request (Admin/Manager/Employee)
- Leave request management (Admin/Manager/Employee)
    - Create leave request
        - Send request  (Admin/Manager/Employee)
        - Save draft  (Manager/Employee)
    - List leave request
        - Personal leave request (Manager/Employee)
        - Employee leave request  (Admin/Manager)
    - List draft leave request (Manager/Employee)
    - View request detail (Admin/Manager/Employee)
- Profile (Admin/Manager/Employee)

## **General Description**

Kairos leave app is app for entity to manage leave request for employee, manage information employee, apply for business regulation and legal

## User Guide

### 1. Login

**Step 1:       Using link first login for change password via email**

[Untitled.md](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled.md)

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled.png)

**Step 2:** **Enter new password, confirm password**

Note: Strength valid password must:

- Contain at least 1 uppercase character
- Contain at least 1 special character
- Have at least 1 digit
- Have at least 8 characters

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%201.png)

After change password successfully, system will navigate to login page and send success message

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%202.png)

**Step 3:** **Enter username. password for login page**

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%203.png)

### 2. Settings

**2.1 Working time**

URL: [https://staging.kairos.bymati.vn/settings](https://staging.kairos.bymati.vn/settings)

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%204.png)

Step 1: you can set working time hour per week

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%205.png)

When you finished one shift working time, the selection box working days will active automatically

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%206.png)

Step 2: you can set to synchronize working day. Please check first the checkbox which you want to apply for another day, then check the day you want to apply the synchronization. Then click synchronize button to execute process

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%207.png)

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%208.png)

You can change display view to 24h format or 12 hours

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%209.png)

24h format:

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2010.png)

### 3. Position

**3.1 Create position**

URL: [**https://staging.kairos.bymati.vn/create-position**](https://staging.kairos.bymati.vn/create-position)

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2011.png)

**Please fill required field to create position**

Required field :

- Position name
- Position type (2 role default are manager and employee)
- Annual leave

**Warning**: You cannot create duplicate position

 **3.2 List position**

List position show all position displayed in table includes: 

- Position name (sorted by position name)
- Position type  (sorted by position type)
- Description
- Annual leave
- Status (filter by status)

URL:**[https://staging.kairos.bymati.vn/](https://staging.kairos.bymati.vn/list-position)list-position**

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2012.png)

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2013.png)

  **3.3 Delete position**

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2014.png)

**Step 1:** *Click delete icon to delete position*

**Step 2**: *Popup will show to confirm to delete, click yes to delete, click no to discard*

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2015.png)

**Warning**: You cannot delete position being used

 ****

**3.4 Edit position**

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2016.png)

**Step 1:** *Click edit icon to edit position*

**Step 2:** *Edit information position then click Update button to submit*

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2017.png)

**Step 3:** *if you want to inactive the position, please click active button*

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2018.png)

**Warning**: 

- You cannot rename position to existed position name
- You cannot inactive the position being used

### 4. Department

**4.1 Create department**

**URL: [https://staging.kairos.bymati.vn/create-department](https://staging.kairos.bymati.vn/create-department)**

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2019.png)

**Required fields:** 

- Department name
- Presentation color

Step 1: Fill all required fields in department form

Step 2: Choose leader of department (optional)

Note: Leader of department is user who have role manager, has not been assigned to any department yet

**4.2 List department**

**URL: [https://staging.kairos.bymati.vn/list-department](http://localhost:3000/list-department)**

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2020.png)

List department show all department displayed in table includes: 

- Department name (sorted by position name)
- Description
- Supervisor (sorted by supervisor)
- Status (filter by status)

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2021.png)

**4.3 Delete department**

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2022.png)

**Step 1:** *Click delete icon to delete department*

**Step 2**: *Popup will show to confirm to delete, click yes to delete, click no to discard*

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2023.png)

**Warning**: You cannot delete department has member

**4.4 Edit department**

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2024.png)

**Step 1:** *Click edit icon to edit department*

**Step 2:** *Edit information department then click Update button to submit*

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2025.png)

**Step 3:** *if you want to inactive the department, please click active button*

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2026.png)

**Warning**: 

- You cannot inactive the department being used
- You cannot rename department to existed department name

Step 1: Fill start date, end date, holiday name, then click plus icon

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2027.png)

### 5. Leave type

**5.1 Create leave type**

URL: [https://staging.kairos.bymati.vn/create-request](https://staging.kairos.bymati.vn/create-request)

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2028.png)

Required fields: 

- Leave type name
- Number of days (limit day off for leave type)
- Kinds of leave type
    - Minus the number of days off
    - Unpaid
- Presentation color

Step 1: 

- Fill required field
- Check minus the number of days off if you want to that leave type will minus annual leave
- Check unpaid if you want that leave type is unpaid
- Check request to provide documents if you want that leave type request must have attachment
    
    ![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2029.png)
    

- Check subject on leave is for gender

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2030.png)

Step 2: Click submit to create leave days

**Warning**: 

- You cannot create existing leave type name

**5.2 List leave type**

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2031.png)

List leave type show all leave type displayed in table includes: 

- Type of leave (sorted by type of leave)
- Description
- Provide documents
- Minus the number of days off
- Unpaid
- Number of days off
- Status (filter by status)

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2032.png)

Note: For leave type is being used will disabled edit icon and delete icon, you cannot edit or delete this leave type

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2033.png)

**5.3 Delete leave type**

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2034.png)

**Step 1:** *Click delete icon to delete leave type*

**Step 2**: *Popup will show to confirm to delete, click yes to delete, click no to discard*

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2035.png)

**Warning**: You cannot delete leave type ****being used

**5.4 Edit leave type**

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2036.png)

**Step 1:** *Click edit icon to edit leave type*

**Step 2:** *Edit information leave type then click Update button to submit*

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2037.png)

**Step 3:** *if you want to inactive the leave type, please click active button*

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2038.png)

**Warning**: 

- You cannot inactive the leave type **being used
- You cannot rename *leave type* to existed leave type **name

### 6. Holidays

**6.1 Create holidays**

URL: [https://staging.kairos.bymati.vn/create-holidays](https://staging.kairos.bymati.vn/create-holidays)

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2039.png)

Required fields

- Start date, end date
- Holiday name

Step 2: You can continuously create more holiday, or delete created holiday by click delete icon

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2040.png)

Step 3: Click Save button to create holidays

**Warning**: 

- You cannot create a holiday that overlaps with an existing holiday
- You cannot create a holiday name **with ******existed holiday name

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2041.png)

**6.2 List holidays**

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2042.png)

URL: [https://staging.kairos.bymati.vn/holidays?year=2024](https://staging.kairos.bymati.vn/holidays?year=2024)

List holidays show all holidays displayed in table includes: 

- Holidays name (sorted by holidays name)
- Start date (sorted by start date)
- End date (sorted by end date)
- Number of days off (sorted by number of days off)
- Status (filter by status)

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2043.png)

**6.3 Delete holidays**

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2044.png)

**Step 1:** *Click delete icon to delete holiday*

**Step 2**: *Popup will show to confirm to delete, click yes to delete, click no to discard*

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2045.png)

**Warning**: 

- You cannot delete/edit holiday ****being used
    
    Holiday being used is in case of user create leave request before holiday or after holiday at least 1 day
    
- You cannot delete/edit passed holiday

**6.4 Edit holidays**

**Step 1:** *Click edit icon to edit holidays*

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2046.png)

**Step 2:** *Edit information holidays then click Update button to submit*

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2047.png)

**Step 3:** *if you want to inactive the holidays, please click active button*

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2048.png)

**Warning**: 

- You cannot inactive the holidays being used or passed holiday
- You cannot rename holidays to existed holidays **name
- You cannot update range time that overlaps in system

### 7. Employee

**7.1 Create employee**

URL: [https://staging.kairos.bymati.vn/employee/create](https://staging.kairos.bymati.vn/employee/create)

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2049.png)

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2050.png)

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2051.png)

Fields of form:

- **Basic information (required)**
    - Last name
    - First name
    - Phone number
    - Gender
    - Birthday
    - Tax code **(optional when checked not issued yet)**
    - Social insurance code **(optional when checked not issued yet)**
    - Address regular
    - Address temporary
- **Identification document (required)**
    - Identification document (citizen Id, passport)
    
    ![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2052.png)
    
    - Nationality
    
    ![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2053.png)
    
    - Number
    - Issue day
    - Issue place
    - Expired day
    - Upload photo of ID card
- **Employee information (required)**
    - Onboard day
    - Contract end day
    - Status
        - When create user
            
            ![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2054.png)
            
        - When update user
        
        ![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2055.png)
        
    
    - Department **(Optional)**
    - Position
    - Annual leave days
    - Leader **(Optional)**
    - Salary
    - Employee id
    - Company email
    - Personal email
- **Vehicle (Optional)**
    - Vehicle type
    
    ![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2056.png)
    
    - Vehicle brand
    - Vehicle number
- **Emergency Contact**
    - Full name
    - Relation
    
    ![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2057.png)
    
    - Phone number
    - Email
    - Address

Steps:

- Fill all required field then submit to create user

Note:

- **Identification:** must only add limit 2 form for citizen id, passport with unique number.
    - File attachment must be image type.
- **Vehicle:** must only add limit 3 form
    - This field is optional, but when you choose vehicle type, you must fill vehicle brand, and vehicle number.
- **Emergency Contact:** must only add limit 3 form.
- When selected position, annual leave for that position will display, you can revise it.

**Warning**: 

- You cannot create employee with same employee code.
- You cannot create employee with same company email.
- You cannot create employee with same phone number.
- You cannot create employee with same full name, day of birth, gender, personal email.
- If you don’t have position, you cannot create employee

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2058.png)

**7.2 List employee**

URL: [https://staging.kairos.bymati.vn/list-employee](https://staging.kairos.bymati.vn/list-employee)

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2059.png)

List employee show all employee displayed in table includes: 

- Employee code (sorted by employee code)
- Full name (sorted by full name)
- Department (filter by department)
- Role (filter by role)
- Email
- Status (filter by status)
- Search employee name

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2060.png)

Feature in list employee:

- Edit employee
- View annual leave

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2061.png)

- More Options:
    - Password recovery
    - Create leave request
    - Switch user
    
    ![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2062.png)
    

**Warning:** 

- For user with status different from “Working” cannot create request and password recovery

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2063.png)

**7.3 Edit employee**

Similar to form create employee.

A few changes:

- Cannot edit last name, first name, phone number, gender, birthday

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2064.png)

- Status options: Inactive, working, fired, end of contract

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2065.png)

**7.4 View annual leave**

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2066.png)

**7.5 Recovery password**

**Step 1:** Click Password recovery in more options.

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2067.png)

**Step 2:** Click confirm to recovery password. Then user can reset password via email.

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2068.png)

**7.6 Switch user**

**Step 1:** Click switch user in more options.

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2069.png)

**Step 2:** Click confirm to switch user.

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2070.png)

**Step 3:** New session browser is open and you can do as that user.

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2071.png)

### 8. Leave request

**8.1 Create leave request**

### For case admin/manager create leave request for employee

**Step 1:** *Click icon “more” to show options, select create leave request* 

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2072.png)

**Step 2** *Click icon “more” to show options, select create leave request* 

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2073.png)

Step 3: Select type of leave request

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2074.png)

Step 4: Fill start date, end date of request, select time of day request

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2075.png)

Step 5: Upload attach files (if any) by click “Click to upload” button

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2076.png)

Step 6: Click send to approve request

**Warning**: 

- You cannot create employee with same employee code.

### For case Manager/ Employee create own leave request

URL: [https://staging.kairos.bymati.vn/create-leave-request](https://staging.kairos.bymati.vn/create-leave-request)

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2077.png)

Steps create own leave request:

- Similar to the steps to create leave request for role admin/ manager with employee

**Warning:** 

- For save draft button:
    - There is no need to enter all form information before clicking save
    - After successfully saving the draft, you will return to the list of draft request. You can continue to edit the draft request or delete the created draft request.
- For send button:
    - This request will be validating status
    - Manager request: request is sent to admin
    - Employee request: request is sent to admin and direct manager

**8.2 List draft leave request (manager/employee)**

URL: [https://staging.kairos.bymati.vn/list-draft-leave-request](https://staging.kairos.bymati.vn/list-draft-leave-request)

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2078.png)

List draft request show all draft request displayed in table includes: 

- Leave types (filter by leave types)
- From date (sorted by from date)
- To date (sorted by to date)
- Duration (sorted by duration)
- Status (filter by status)

**8.3 Delete draft leave request**

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2079.png)

**Step 1:** *Click delete icon to delete holiday*

**Step 2**: *Popup will show to confirm to delete, click yes to delete, click no to discard*

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2080.png)

**8.4 Edit draft leave request**

**Step 1:** *Click edit icon to edit draft leave request*

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2081.png)

**Step 2:** *Edit request then save draft or send directly*

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2082.png)

**8.5 List leave request**

URL: [https://staging.kairos.bymati.vn/schedule](https://staging.kairos.bymati.vn/schedule)

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2083.png)

List leave request show all leave request displayed in table includes: 

- Employee code (sorted by Employee code)
- Full name (sorted by full name)
- Department (filter by department)
- Role (filter by role)
- Start date (sorted by start date)
- End date (sorted by end date)
- Number of leaves (sorted by number of leaves)
- Type of leaves (filter by type of leaves)
- Status (filter by status)

Notes:

- For Admin: list request show all requests of all employee of company
- For Manager/Employee: show all requests of employee of own department

**8.6 Leave request detail**

**Step 1:** Click to detail icon

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2084.png)

**Step 2:**

For request with status : Validating

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2085.png)

**For Admin/Manager view employee request**

Do actions:

- Return request: fill reason form return request then click send button

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2086.png)

- Reject request: fill reason form return request then click send button

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2087.png)

- Approve: click approve button

**For Manager/Employee view own request**

- Return request: fill reason form return request then click send button
    
    User can cancel or edit leave request then re-send to admin/manager
    

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2088.png)

- Approve/Reject/Cancel request

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2089.png)

### 9. Profile

**Step 1:** Click to avatar , dropdown will display options, please select personal information

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2090.png)

**Step 2:** If you want to edit your profile, you must click Edit button beforehand .

URL: [https://staging.kairos.bymati.vn/information](https://staging.kairos.bymati.vn/information)

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2091.png)

**Step 3:** You can update your avatar, time settings for your account

**Step 4:** After you edit your profile, then click Submit button to update your profile

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2092.png)

### 10. Notification

You can check your notification by click to this icon

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2093.png)

### 11. Report an issue

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2094.png)

**Step 1:** If you have any problem, please click to “Report an issue” in sidebar

**Step 2:** Please fill required field (content, URL, email)

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2095.png)

**Step 3:** if you want to upload more file, please click Upload file button

Note: system limits for uploading is 10 files

**Step 4:**  Please click “Send” button to send your issue to technical support

### 12. Change password

**Step 1:** Click avatar will show dropdown, then click “Change password”

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2096.png)

**Step 2:** Enter current password, new password, confirm password

Note for strength password:

- Contains at least 1 uppercase character
- Contains at least 1 special character
- Has at least 1 digit
- Have at least 8 characters

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2097.png)

Step 3: After fill all field, please click “Update” button

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2098.png)

Step 4: After fill all field, please click “Update” button. Modal confirmation will display. Click to Yes to confirm change password

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%2099.png)

### 13. Logout

Click avatar will show dropdown, then click to log out

![Untitled](User%20Guide%20438fb711eb224c369a3880c15549bdda/Untitled%20100.png)