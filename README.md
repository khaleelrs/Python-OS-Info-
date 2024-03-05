# Python-OS-Info-

This Python script serves as a comprehensive system monitoring tool, offering detailed insights into various aspects of the host machine's configuration and performance. The script encompasses the following functionalities:

Operating System Information:

Utilizes the platform module to fetch and present details about the operating system, including its version.
Network Information:

Dynamically retrieves and displays crucial network details such as the private IP address, default gateway, and public IP address. The public IP address is obtained through an external API request using the requests module.
Disk Usage Information:

Provides a breakdown of the disk space, presenting the total, used, and free disk space in a user-friendly format. This information is retrieved using the shutil module.
Top Directories by Size:

Employs a recursive approach with os.walk() to calculate and showcase the largest directories in the filesystem. Users can customize the displayed number of top directories.
CPU Usage Monitoring:

Implements the psutil module to continuously monitor and report the CPU usage percentage at 10-second intervals. This real-time feedback on CPU performance aids users in assessing system load and responsiveness.
The script's versatility makes it a valuable tool for both system administrators and general users seeking a comprehensive overview of their system's health and resource utilization. Whether for routine system checks, troubleshooting, or performance optimization, this script offers a holistic solution for monitoring a range of critical system parameters.
