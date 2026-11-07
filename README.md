# Case-Management-System

📌 Project Overview

The Vendor Management System (VMS) is a Salesforce-based CRM solution designed to manage customer issues, automate case handling, improve communication, and track case resolution efficiently.

It provides a centralized platform to handle customer complaints related to product defects, billing, warranty, and technical issues.

🎯 Key Features

Customer and Product Management

Automated Case Creation using Email-to-Case and Web-to-Case

Case Assignment and Engineer Management

Salesforce Flow Automation

Automated Email Notifications

Seven-Day Resolution SLA Tracking

Omni-Channel Case Routing

Reports and Interactive Dashboards

Validation Rules for Case Owner Management

🛠️ Technologies Used

Salesforce CRM

Standard Objects: User, Contact, Product, Case

Custom Fields and Formula Fields

Salesforce Flow Builder

Email-to-Case

Web-to-Case

Omni-Channel

Validation Rules

Reports and Dashboards

⚙️ Implementation Details

1. Object Configuration

Configured User, Contact, Product, and Case objects with page layouts, related lists, and custom fields.

2. Case Management

Implemented Email-to-Case and Web-to-Case for automatic case creation, contact association, and case assignment.

3. Flow Automation

Created automated flows for:

Auto Associate Existing Contact

VMS Case Assignment Notification

VMS Case Resolution Notification

VMS Case Closure Notification

4. Validation Rule

Implemented Restrict_Engineer_Reassignment to restrict non-System Administrators from changing Case Owner.

5. SLA Management

Implemented a seven-day resolution target using formula fields to monitor case resolution status.

6. Omni-Channel

Configured Omni-Channel routing to distribute incoming cases to available agents and reduce manual assignment.

7. Reports & Dashboards

Created reports to analyze cases by:

Priority

Status

Issue Type

Resolution Status

Daily Opened and Closed Cases

Developed the VMS Case Management Dashboard to monitor overall case performance.

🔄 Project Workflow

Customer Issue → Case Creation → Contact Association → Case Assignment → Engineer Processing → Resolution → Closure → Dashboard Monitoring

📊 Project Outcomes

Centralized customer issue management.

Improved case tracking and assignment.

Automated notifications and workflows.

Better monitoring of resolution targets.

Improved visibility through reports and dashboards.

🎓 Skills Demonstrated

Salesforce Administration | CRM Configuration | Flow Builder | Case Management | Omni-Channel | Email-to-Case | Web-to-Case | Validation Rules | Reports & Dashboards

👨‍💻 Project Details

Project Name: Vase Management System

Platform: Salesforce CRM

Project Type: Salesforce Administration & Automation

Domain: Customer Relationship Management
