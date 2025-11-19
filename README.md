# NERP - Enterprise Resource Planning Desktop Application

A comprehensive **Enterprise Resource Planning (ERP)** desktop application designed for modern businesses. NERP provides a complete solution for managing employees, salaries, inventory, archives, and organizational data with an intuitive, Arabic-friendly interface.

## 🌟 Overview

NERP is a full-featured desktop application that combines the power of modern web technologies with the convenience of a native desktop experience. Built with Electron, it runs seamlessly on Windows 10 and Windows 11, providing a robust, secure, and user-friendly solution for enterprise resource management.

## ✨ Key Features

### 👥 Human Resources Management
- **Employee Management** - Complete employee profiles with photos, personal information, and employment details
- **Department & Section Management** - Organize employees by departments, sections, and administrations
- **Nationality & Bank Management** - Manage employee nationalities and banking information
- **Employee Records** - Track employee history, assignments, and status

### 💰 Salary & Payroll System
- **Advanced Salary Calculations** - Complex salary equations with variables and constants
- **Salary Tables** - Flexible salary table management
- **Payroll Processing** - Automated salary calculations and bulk operations
- **Salary History** - Track salary changes and history per employee
- **Global Operations** - Bulk salary updates and calculations

### 📦 Inventory Management
- **Product Management** - Complete product catalog with pricing, quantities, and stock levels
- **Inventory Tracking** - Monitor stock levels, reorder points, and storage conditions
- **Supplier & Customer Management** - Manage providers, customers, and business relationships
- **Categories & Groups** - Organize products by categories, groups, and cost centers
- **Manufacturers & Countries** - Track product origins and manufacturers

### 📁 Archive & Document Management
- **Digital Archive System** - Secure document storage with encryption
- **Folder Organization** - Hierarchical folder structure for document organization
- **Entity Register** - Manage internal and external entities
- **Document Types** - Categorize documents by type of action
- **File Upload & Management** - Upload, encrypt, and manage documents securely
- **Text Extraction** - OCR capabilities for extracting text from images

### 📊 Reports & Analytics
- **Dynamic Report Builder** - Create custom reports with drag-and-drop interface
- **Calculated Fields** - Add custom calculations and formulas to reports
- **Excel Export** - Export reports to Excel format
- **Print-Ready Layouts** - Professional report formatting for printing
- **Data Visualization** - Tables, charts, and visual representations

### 🔐 Security & Access Control
- **User Management** - Create and manage user accounts
- **Role-Based Access Control (RBAC)** - Granular permission system
- **Secure Authentication** - JWT-based authentication with password encryption
- **Audit Logs** - Track all user actions and system changes
- **Data Encryption** - Encrypted file storage for sensitive documents

### 💬 Communication
- **Real-Time Chat** - Internal messaging system with real-time updates
- **Online Users** - See who's currently online
- **Message History** - Complete chat history and search

### ⚙️ System Features
- **Auto-Start** - Configure application to start with Windows
- **Automatic Updates** - Built-in update system for seamless upgrades
- **Backup & Restore** - Automated and manual backup system
- **Email Integration** - Configure email settings for notifications
- **Theme Customization** - Customize application colors and appearance
- **RTL Support** - Full right-to-left language support for Arabic

## 🖥️ System Requirements

- **Operating System**: Windows 10 or Windows 11
- **Architecture**: 64-bit (x64)
- **Disk Space**: Minimum 500 MB for application and data
- **Memory**: 4 GB RAM recommended

## 📥 Installation

### Easy Installation Process

1. **Download the Installer**
   - Visit the [Releases](https://github.com/mohfrea/Nerp-releases/releases) page
   - Download the latest `NERP-setup.exe` file

2. **Run the Installer**
   - Double-click the downloaded installer
   - Follow the installation wizard
   - The installer will guide you through the setup process

3. **First Launch**
   - Launch NERP from the Start Menu or Desktop shortcut
   - The application will automatically:
     - Set up the database
     - Run initial migrations
     - Create default admin user
     - Restart once to complete setup

4. **Login**
   - Use the default credentials:
     - **Username**: `admin`
     - **Password**: `admin123`
   - **Important**: Change the password after first login

That's it! The application is ready to use. No additional configuration or database setup required.

## 🚀 Getting Started

### First Steps

1. **Change Default Password**
   - Go to **Profile** → **Change Password**
   - Set a strong password for the admin account

2. **Configure General Settings**
   - Navigate to **Settings** → **General Settings**
   - Configure organization name, contact information, and other details

3. **Set Up Users & Roles**
   - Go to **Users** to create additional user accounts
   - Configure **Roles** with appropriate permissions
   - Assign roles to users based on their responsibilities

4. **Import or Add Data**
   - Use **Excel Import** to bulk import employees, products, or other data
   - Or manually add data through the respective modules

## 📚 Main Modules

### Evidence Management
Centralized data management for all reference information:
- **Employee Evidence**: Banks, Administrations, Sections, Nationalities
- **Salary Evidence**: Salary Tables, Variables, Constants, Equations
- **Archive Evidence**: Document Types, Entities, Folders
- **Inventory Evidence**: Manufacturers, Countries, Categories, Cost Centers, Providers, Customers, Groups, Inventories, Units

### Core Operations
- **Employees**: Complete employee management and profiles
- **Salaries**: Salary calculations and payroll processing
- **Archives**: Document management and archival system
- **Inventory**: Product and stock management
- **Reports**: Custom report generation and analytics

## 🔧 Application Features

### Data Management
- **Excel Import/Export** - Seamless data exchange with Excel files
- **Bulk Operations** - Perform operations on multiple records at once
- **Advanced Search** - Powerful search and filtering across all modules
- **Global Updates** - Update multiple records simultaneously

### User Experience
- **Modern UI** - Beautiful, responsive interface built with Material-UI
- **Arabic Language Support** - Full RTL support with Arabic interface
- **Keyboard Shortcuts** - Efficient navigation with keyboard shortcuts
- **Responsive Design** - Works on different screen sizes

### System Integration
- **Portable Database** - Bundled MongoDB - no separate installation needed
- **Auto-Start** - Start with Windows for always-available access
- **System Tray** - Minimize to system tray for background operation
- **Background Services** - MongoDB and backend run automatically

## 🔒 Security Features

- **Encrypted Storage** - Sensitive files are encrypted at rest
- **Secure Authentication** - Industry-standard JWT authentication
- **Role-Based Permissions** - Fine-grained access control
- **Audit Trail** - Complete logging of all system activities
- **Data Validation** - Input validation and sanitization
- **XSS Protection** - Protection against cross-site scripting attacks

## 💾 Backup & Restore

### Automatic Backups
- Configure automatic backups in **Settings** → **Backup**
- Set backup frequency and retention policy
- Backups include database and all files

### Manual Backup
- Create backups on-demand from Settings
- Export complete application data
- Restore from backup files when needed

## 🆘 Support & Troubleshooting

### Common Solutions

**Application Won't Start:**
- Ensure Windows 10/11 is up to date
- Run as Administrator if needed
- Check Windows Defender settings

**Database Connection Issues:**
- The application manages MongoDB automatically
- If issues persist, restart the application
- Check system tray for running services

**Performance Issues:**
- Close other resource-intensive applications
- Ensure sufficient disk space
- Check available RAM

### Getting Help

- **Documentation**: Check the built-in documentation in the application
- **Issues**: Report problems through GitHub Issues
- **Community**: Join discussions in the Issues section

## 🛠️ Technology Stack

### Frontend
- React - Modern UI framework
- Material-UI - Component library
- React Query - Data management
- React Router - Navigation
- Vite - Build tool

### Backend
- Node.js - Runtime environment
- Express.js - Web framework
- MongoDB - Database
- Mongoose - Database modeling
- Socket.io - Real-time communication

### Desktop
- Electron - Desktop framework
- Auto-updater - Update system
- Portable MongoDB - Embedded database

## 📝 License

This project is licensed under the ISC License.

## 👨‍💻 Author

**Mohamed Friaa**  
**Numedia**

---

**📋 Ready to get started?** Download the latest release from the [Releases](https://github.com/mohfrea/Nerp-releases/releases) page and follow the easy installation process above.

---

_Built with modern web technologies for a seamless desktop experience_
