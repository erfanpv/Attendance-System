# 🎯 Very Simple Attendance System


## 📖 About

Very Simple Attendance System is a modern, Docker-based attendance tracking solution that combines security with simplicity. Built for organizations that need reliable attendance tracking with device-specific verification.

### Why Choose This System?

- 🔐 **Enhanced Security**: Unique PTP (Personal Token Pin) system for device verification
- ⚡ **Real-time Tracking**: Instant clock in/out with live updates
- 🌟 **User-Friendly**: Clean, intuitive interface for both admins and users
- 🔄 **Flexible Management**: Comprehensive admin controls for user management
- 📊 **Rich Analytics**: Detailed attendance reports and statistics
- 🐳 **Easy Deployment**: Simple Docker-based setup

## 🚀 Quick Start

### One-Click Setup

```bash
# Clone the repository
git clone https://github.com/rakshitbharat/very-simple-attendance.git

# Navigate to project directory
cd very-simple-attendance/source

# Launch with Docker
docker-compose up -d
```

Access your system at `http://localhost:3000`



## 📱 Interface Tour

### Admin Dashboard


- Active users monitoring
- Total check-ins tracking
- Weekly attendance overview
- User management tools
- PTP management system

### User Dashboard

- Current work status
- Today's hours tracking
- Weekly summary
- Monthly attendance calendar
- Personal activity log

## 🛠️ Technical Stack

- **Frontend**: Next.js 14
- **Backend**: Next.js API Routes
- **Database**: PostgreSQL 
- **Containerization**: Docker & Docker Compose
- **Authentication**: Custom PTP System

## 📋 User Guides

### For Administrators

1. **User Management**

   - Add new users
   - Assign roles
   - Manage PTPs
   - Monitor attendance

2. **System Controls**
   - Reset user PTPs
   - Manage devices
   - Generate reports
   - Configure settings

### For Regular Users

1. **First-Time Setup**

   - Login with provided credentials
   - Enter PTP code
   - Register device

2. **Daily Usage**
   - Quick clock in/out
   - View attendance history
   - Check work hours
   - Monitor attendance streak

## ⚙️ Configuration

### Environment Setup

```env
DB_HOST=localhost
DB_PORT=3306
DB_USER=root
DB_PASS=password
```

### Docker Configuration

```yaml
version: "3.8"
services:
  app:
    build: .
    ports:
      - "3000:3000"
```




<div align="center">
  <h3>🌟 Secure Attendance Tracking Made Simple 🌟</h3>
  
  Built with ❤️ for modern organizations
</div>
