# Employee Portal - Power Apps Solution

A comprehensive employee self-service portal built with Microsoft Power Apps, featuring time tracking, document management, and automated notifications.

## 🎯 Features

### Core Functionality
- Employee self-service time logging
- Manager team view and oversight
- Project management and tracking
- Time log entry with validation
- Historical time log viewing

### Integrations
- **SharePoint**: Document management and viewing
- **Office 365 Outlook**: Automated email summaries
- **Dataverse**: Secure data storage with row-level security

### Security
- Role-based access control (RBAC)
- Employee: User-level access (own records only)
- Manager: Business Unit access (team records)
- Admin: Organization-wide access

## 🛠️ Technologies Used

- Microsoft Power Apps (Canvas App)
- Microsoft Dataverse
- SharePoint Online
- Office 365 Outlook
- Power Fx formulas
- Application Lifecycle Management (ALM)

## 📦 Deployment

Solution can be deployed across environments using the included .zip file.

**Environments:**
- Development
- Test
- Production-ready

## 🔐 Security Implementation

Implemented three-tier security model:
- Row-level security with Dataverse security roles
- User/Business Unit/Organization access levels
- Proper privilege configuration for delegation

## 📊 Data Model

**Tables:**
- Employees
- Projects
- Work Log Entry
- Approvals

## 🚀 Key Learnings

- Canvas App development best practices
- ALM and solution management
- Integration with Microsoft 365 services
- Security role implementation
- Deployment across multiple environments

## 📝 Installation

1. Download the solution file from this repository
2. Import to your Power Platform environment
3. Configure connections (Dataverse, SharePoint, Outlook)
4. Assign security roles
5. Publish and share

## 👤 About

Built as part of Power Platform learning journey. Demonstrates end-to-end application development from design to deployment.

---

**Status:** Production-ready
**Last Updated:** January 2026
