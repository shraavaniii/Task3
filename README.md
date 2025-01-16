**COMPANY**: CODTECH IT SOLUTIONS  
**NAME**: SHRAVANI ACHAL HENDRE  
**INTERN ID**: CT08DTU  
**DOMAIN**: CYBERSECURITY AND ETHICAL HACKING  
**BATCH DURATION**: 25th Dec to 25th Jan  
**MENTOR NAME**: NEELA SANTOSH  

**Overview of the Project:**
1. Port Scanner:
Functionality:
- Scans a specified range of ports on a target IP address or domain to identify open ports.
- Uses multi-threading to speed up the scanning process by concurrently checking multiple ports.

Process:
- The user inputs the target IP/domain and the range of ports to scan.
- Each port is checked using a separate thread to see if it is open.
- Results are displayed, listing all open ports detected.

Use Case:  
Helps identify open ports that might be vulnerable to attacks or used for unauthorized access.

2. Brute Force Login:
Functionality:
- Attempts to gain access to a web application's login page by trying multiple password combinations for a given username.

Process:
- The user provides the login URL, a username, and a list of passwords.
- For each password, a POST request is sent with the username and password.
- If a login is successful, the correct password is displayed; otherwise, failed attempts are recorded.

Use Case:  
Used to test the strength of a password against brute-force attacks, highlighting the importance of strong, unique passwords.

3. General Features:
Clear Console Function: Clears the console screen to keep the interface clean and organized.
Banner Display: Shows a custom ASCII banner for branding and user experience.
Random User-Agent: Generates a random User-Agent string for each HTTP request, mimicking different browsers to avoid detection by simple security measures.
Failed Attempts Logging: Saves unsuccessful login attempts to a file for later review.

Key Components:
- Multi-threading: Enhances the efficiency of the port scanning by handling multiple ports simultaneously.
- Session Management: Maintains session state during the brute-force login process using Python's requests.Session.
- Error Handling: Gracefully handles network errors and exceptions, providing informative messages to the user.

Example Usage:

1. Port Scanning:
The user selects the port scanner option, inputs the target details, and specifies the port range.
The tool scans and displays open ports or indicates if no open ports are found.

2. Brute Force Login:
The user selects the brute force login option, inputs the target URL, username, and password list.
The tool attempts to log in with each password, reporting success or failure and logging unsuccessful attempts.

3. Main Menu:
Provides an easy navigation menu with options to select the desired tool or exit the application.

Use Case:
- Security Assessment: Helps in identifying vulnerabilities in network services and web applications.
- Educational: Ideal for learning the basics of penetration testing and understanding common security threats.
- Preemptive Testing: Allows developers and administrators to test their systems against common attack vectors before deployment.
