# PumpTill Pro — Fuel Reading Ledger

A secure, role-based web application for managing fuel pump readings and station operations. Built for fuel stations to track daily pump readings, monitor movement (usage), and maintain operational records.

## 🎯 Features

### For Administrators
- **Full System Access**: Manage all records across all stations and attendants
- **Analytics Dashboard**: Real-time KPIs, trends, and performance metrics
- **Ledger Management**: View, edit, delete, and export all records
- **User Management**: Create and manage administrator and client accounts
- **Security Logs**: Monitor all system activities and user actions
- **Data Export**: Export records in JSON format for reporting

### For Clients
- **Record Submission**: Submit daily fuel pump readings securely
- **Personal Ledger**: View only their own submitted records
- **Reading Calculator**: Automated opening reading calculations based on movement data
- **Session Security**: Auto-logout after 20 minutes of inactivity

## 📊 Core Functionality

### Reading Calculator
- **Closing Readings**: Record the current pump readings (sale & litres)
- **Movement Data**: Enter the sales/litres movement for the shift period
- **Auto-Calculate**: System automatically derives opening readings:
  - Opening Sale = Closing Sale − Sale Movement
  - Opening Litres = Closing Litres − Litres Movement

### Record Management
- Station/pump identification
- Attendant assignment
- Shift tracking (Morning, Afternoon, Evening, Night)
- Comprehensive notes and remarks
- Timestamp recording for each entry

## 🔐 Security Features

- **Role-Based Access Control**: Separate interfaces for Admins and Clients
- **Session Management**: 20-minute auto-logout on inactivity
- **Authentication**: Username/password login with demo credentials
- **Audit Logging**: All actions logged with timestamp and user info
- **Data Integrity**: Browser-based storage with export capability

## 🚀 Getting Started

### Demo Access

**Administrator Account:**
```
Username: admin
Password: Admin@2024
```

**Client Accounts:**
```
Username: client1 or client2
Password: Client@2024
```

### Usage

1. Visit: [https://markngeno277-droid.github.io/PumpTillPro/](https://markngeno277-droid.github.io/PumpTillPro/)
2. Select your role (Administrator or Client)
3. Enter credentials
4. Log in securely

## 📁 Project Structure

```
pumptill-pro/
├── index.html        # Complete application (HTML + CSS + JavaScript)
└── README.md         # This file
```

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Styling**: Custom design system with CSS variables
- **Charts**: Chart.js for analytics visualization
- **Fonts**: Google Fonts (IBM Plex Mono, DM Sans, Space Grotesk)
- **Storage**: Browser LocalStorage (Client-side)

## 📱 Responsive Design

The application is fully responsive and works seamlessly on:
- Desktop computers
- Tablets
- Mobile devices

## 🎨 Design System

**Color Palette:**
- Teal: Primary brand color (#077a6e)
- Amber: Secondary action color (#c47b1e)
- Red: Danger/alert color (#b53030)
- Blue: Tertiary accent (#2457b3)

## 📈 Future Enhancements

Potential improvements for future versions:
- Backend database integration for persistent data storage
- Advanced reporting and PDF export
- Mobile app version
- Multi-station/branch support
- Real-time data synchronization
- Email notifications
- Two-factor authentication
- API for third-party integrations

## 📝 License

Private project. All rights reserved.

## 👨‍💻 Developer

**markngeno277-droid** — [GitHub Profile](https://github.com/markngeno277-droid)

---

**Last Updated**: July 2, 2026  
**Current Version**: 1.0.0
