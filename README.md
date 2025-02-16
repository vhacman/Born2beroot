# Born2beroot

## 🚀 Overview
Born2beroot is a system administration project focused on learning the fundamentals of virtualization, Linux system management, and essential security practices. The project involves creating a virtual machine running Debian Linux with specific security configurations.

## 📋 Key Components

### Virtual Machine Setup
- Created using Oracle VirtualBox
- Based on Debian GNU/Linux
- Implements LVM (Logical Volume Management) for flexible disk space management
- Includes partitioned storage following project requirements

### Security Features
- UFW (Uncomplicated Firewall) configuration
- Strong password policy using `libpam-pwquality`
- SSH service running on port 4242
- Root login disabled
- AppArmor enabled for enhanced security
- Secure user management and sudo configuration

### System Monitoring
- Custom monitoring script displaying:
  - System architecture
  - CPU physical/virtual cores
  - Memory usage
  - Disk usage
  - CPU load
  - Last boot time
  - LVM status
  - Active connections
  - User information
  - Network status
  - Sudo command history

### Bonus Features
- Functional WordPress website
- Service management (Lighttpd, MariaDB, PHP)
- Additional service configuration

## 🛠️ Technical Details

### Password Policy
- Minimum 10 characters
- Contains uppercase and lowercase letters
- At least one number
- No more than 3 consecutive identical characters
- Username not included in password
- 7 characters different from previous password
- Password expires every 30 days
- Minimum 2 days between password changes
- Warning 7 days before expiration

### Sudo Configuration
- Failed attempts limited to 3
- Custom error message
- Command logging enabled
- TTY required
- Secure paths defined

### System Services
- SSH configured for secure remote access
- UFW configured with necessary ports
- Monitoring script runs every 10 minutes via crontab

## 🎯 Learning Outcomes
- Understanding of Linux system administration
- Implementation of system security measures
- User and group management
- Service configuration and management
- Virtualization concepts
- Disk partitioning and LVM
- Basic web server setup
- System monitoring and maintenance

## 📝 Notes
This project was completed as part of the 42 school curriculum, focusing on practical system administration skills and security best practices. The implementation strictly follows the project requirements while providing hands-on experience with real-world system administration tasks.

