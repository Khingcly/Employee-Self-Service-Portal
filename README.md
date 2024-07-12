# Employee Self-Service Application

## Overview

The Employee Self-Service Application is designed to streamline HR and managerial processes within a company. Built on the Microsoft Power Platform, this application leverages APIs like Power Automate, SharePoint, OneDrive, and Google Gmail to provide a seamless user experience. 

## Features

### Sign-In Screen
- **Login Validation**: The login button is only activated if the email address ends with the company domain name.
- **Account Lockout**: After three incorrect login attempts, users are logged out.

### Create Account
- **Email-Based Personal Information**: Other personal information fields are automatically populated upon entering the email address.
- **Password Requirements**: Passwords must be at least 8 characters long and include uppercase, lowercase, and symbol characters.

### Notifications
- **Notification Screen**: Users can mark notifications as read and sort them by date or urgency.
- **Leave Request Notifications**: Only available for HR.

### Leave Requests
- **Approval/Reject**: HR and Supervisors can approve or reject leave requests directly from the app.
- **Email Notifications**: HR and Supervisors receive an email from Power Automate to approve or reject leave requests with reasons.
- **Countersigning**: HR can countersign leave requests if they do not meet company policies or guidelines.

### HR Features
- **Create Notifications**: HR can create notifications for employees directly from the app.
- **Onboarding Management**: HR can see, modify, download, or delete onboarding-related documents.

### Onboarding for New Hires
- **Upcoming Events**: View upcoming onboarding events.
- **Onboarding Notifications**: Receive and manage notifications related to onboarding.
- **Document Management**: Upload, modify, or delete documents for the onboarding process.

### Leave Request Feature
- **Leave Accrual**: Leave accrues monthly.
- **User-Friendly UI**: An easy-to-use interface for applying for different types of leave requests.

### Access Control
- **Role-Based Access**: There are three levels of access: Managerial, HR, and Employee.
  - **Managerial**: Access to managerial features.
  - **HR**: Access to HR-specific features.
  - **Employee**: Access to employee-specific features.
- **Restricted Views**: Certain screens and features are only accessible to managers and HR, not to employees.

## Technologies Used
- **Microsoft Power Platform**
- **APIs**:
  - Power Automate
  - SharePoint
  - OneDrive
  - Google Gmail

## Getting Started

### Prerequisites
- Microsoft Power Platform account
- SharePoint site
- OneDrive account
- Google Gmail account

### Installation
1. Clone the repository.
   ```bash
   git clone https://github.com/yourusername/employee-self-service-application.git
   ```
2. Follow the setup instructions for the Microsoft Power Platform and configure the necessary APIs and connections.

### Usage
1. Deploy the application on the Microsoft Power Platform.
2. Configure the application settings to match your company’s domain and policies.
3. Add users and assign them appropriate roles (Managerial, HR, or Employee).

## Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss any changes or improvements.

## License
This project is licensed under the MIT License.

## Contact
For any questions or support, please contact kingsleyandy98@gmail.com.

