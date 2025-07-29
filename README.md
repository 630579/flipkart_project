# Employee Leave Management System (ELMS)

## Overview
The Employee Leave Management System (ELMS) is a comprehensive web application designed to streamline and automate the process of managing employee leave requests. It provides features for employees to request leave, managers to approve/reject requests, and administrators to manage the system and generate reports.

---
## Features
- **User Authentication**: Secure login for employees, managers, and administrators
- **Leave Request Management**: Submit, view, and track leave requests
- **Approval Workflow**: Managers can approve/reject pending leave requests
- **Leave Balance Tracking**: Automatic tracking of available leave days
- **Reporting**: Detailed reports on leave trends and department statistics
- **Admin Dashboard**: Comprehensive system management tools
- **Responsive Design**: Works on desktop and mobile devices
----
## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
- **Backend**: Python, Flask
- **Database**: SQLite (with SQLAlchemy ORM)
- **Authentication**: Flask-Login
- **Charts**: Chart.js

----
## Installation
1. Clone the repository:
   ```bash
   gh repo clone 630579/flipkart_project
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:
   ```bash
   python app.py
   ```

5. Access the application at `http://127.0.0.1:5000
----
## Usage
### Login Credentials
- **Admin**: username `admin`, password `admin123`
- **Employee**: username `employee`, password `emp123`
- **Manager**: username `manager`, password `man123`

----

### Employee Features
- View leave balances
- Submit new leave requests
- Track request status
- View request history

### Manager Features
- Approve/reject leave requests
- View team leave calendar
- Monitor pending approvals

### Admin Features
- Manage all users
- Configure leave types
- Generate system reports
- Monitor system activity
----
## Screenshots

### Login page
<img width="1920" height="1080" alt="Image" src="https://github.com/630579/flipkart_project/blob/main/login.jpg?raw=true"/>

### Employee Dashboard
<img width="941" height="477" alt="Image" src="https://github.com/630579/flipkart_project/blob/main/employee_dash.jpg?raw=true" />

### Leave Request Form
<img width="944" height="470" alt="Image" src="https://github.com/630579/flipkart_project/blob/main/employee_leave.jpg?raw=true" />

### Manager Approval Dashboard
<img width="949" height="483" alt="Image" src="https://github.com/630579/flipkart_project/blob/main/manager.jpg?raw=true" />

### Reports Dashboard
<img width="935" height="487" alt="Image" src="https://github.com/630579/flipkart_project/blob/main/manager_reports.jpg?raw=true" />

----

## Database Schema
The system uses the following database tables:
- `User`: Stores employee information
- `LeaveType`: Defines different types of leave
- `LeaveRequest`: Tracks all leave requests
- `LeaveBalance`: Maintains leave balances for employees

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---
## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

---
## Contact
For questions or support, please contact the project maintainer at sangalaashok@example.com
