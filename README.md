DVWA Installation and Setup Report
Name: Aguzue Chioma
Course: Cybersecurity
Date: 16 November 2026
Project: Installation of Damn Vulnerable Web Application (DVWA)
Platform: Kali Linux
Virtualization: Oracle VirtualBox

1. Introduction

Damn Vulnerable Web Application (DVWA) is an intentionally vulnerable web application used for cybersecurity learning and web application security practice. It provides a controlled environment for understanding common web vulnerabilities.

2. Tools Used

- Kali Linux
- Oracle VirtualBox
- Docker
- Docker Compose
- Mozilla Firefox
- DVWA

3. Installation Process

The following steps were completed during the installation:

1. Started Kali Linux in Oracle VirtualBox.

2. Installed Docker and Docker Compose.

3. Downloaded the DVWA project from its official GitHub repository.

4. Navigated to the DVWA directory using the terminal.

5. Started DVWA and its database services using:
  
   "sudo docker compose up -d"

6. Verified that both containers were running using:
  
   "sudo docker ps"

7. Opened Firefox and accessed DVWA through:
  
   "http://127.0.0.1:4280"

8. Created the DVWA database using the database setup page.

9. Logged into the application successfully.

4. Results

The installation and configuration were successful.

- DVWA application container: Running.
- Database container: Running.
- Database setup: Successful.
- Application access: Successful.
- Login: Successful.
- Initial security level observed: Impossible.

5. Conclusion

The practical exercise was successfully completed. DVWA was installed and configured on Kali Linux using Docker.

This exercise provided practical experience in deploying a web application, managing Docker containers, and accessing a locally hosted security testing environment.

Note: No vulnerability testing was performed as this practical focused on installation and setup.

6. Evidence

The following screenshots are included as evidence of the practical work:

1. Docker containers running.
3. DVWA database setup page.
4. Successful DVWA login and welcome page.
5. DVWA security level showing Impossible.
   
