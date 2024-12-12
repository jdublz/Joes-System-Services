**Joe's System Services (JSS or Jdubz)**
Multi-function PowerShell tool. 

**Overview**
Joe's System Services (JSS) is an all-in-one, Windows-based administrative tool designed to streamline IT management tasks. With an intuitive GUI built in PowerShell and Windows Forms, JSS (or Jdubz tool) provides a suite of features for managing printers, certificates, task scheduling, system configurations, and more. The dashboard is designed to simplify complex administrative tasks and boost productivity for **ALL** IT professionals.

**Features**
**1. Printer Management**
Printer Selection and Filtering:
Connect to print servers and retrieve a list of available printers.
Search and filter printers dynamically by name for quick access.
Driver Installation:
Install printer drivers for a single PC or multiple PCs using file-based input.
Requires credentials for privileged operations, ensuring secure driver deployment.
Detailed Printer Information:
Retrieve printer details such as IP address, driver name, and more.
Credential Management:
Allows administrators to enter elevated credentials for driver installations.

**2. Task Scheduler**
Schedule tasks across single or multiple PCs.
Select common administrative tasks, including:
Group Policy Updates.
Windows Updates.
Google Updates.
Customizable scheduling with:
Date and time selection for future task execution.
Immediate task execution option.
Feedback through a progress bar and status updates.

**3. Miscellaneous Utilities**
Text-to-Speech Broadcast:
Send a spoken message to remote machines.
Desktop Manipulation:
Rotate screens by 90 degrees or reset to default orientation.
Mouse Sensitivity Adjustment:
Automate mouse sensitivity changes remotely.
Caps Lock Toggle:
Enable or disable Caps Lock remotely.
Create Fake Files:
Generate placeholder files for testing on remote desktops.

**4. Certificate Manager**
View and manage user certificates.
Load certificates with detailed expiration and owner information.
Remove selected certificates securely with confirmation prompts.

**5. Game Tab**
Joe’s Clicker Game:
Fun distraction for breaks, featuring:
A cookie clicker game with upgrades and auto-clickers.

**6. Weather Information**
Retrieve current weather conditions for multiple predefined locations.
Display temperature, short forecasts, and icons.

**7. System Overview**
General system information at a glance:
Greeting with the current user name.
Date and time display.
Quick action buttons for restarting the PC or opening Task Manager.
Motivational quotes for inspiration.

**8. Settings**
Dark Mode Toggle:
Switch between light and dark themes for all tabs.
Reorder Tabs:
Customize the tab order to prioritize frequently used features.

**9. Help Tab**
Detailed instructions and guidance for using the dashboard.
Support link to Joe’s GitHub repository for troubleshooting.

**Requirements**
Operating System: Windows 10 or later.
PowerShell Version: 5.1 or higher.
Admin Privileges: Required for certain tasks like printer driver installation or certificate removal.

**Installation**
Clone the repository or download the PowerShell script files.
Open a PowerShell terminal with administrator privileges.
Run the main script:
powershell
Copy code
.\JoesSystemServices.ps1
The GUI will launch automatically.

**Usage**
Navigate through the tabs to access different functionalities.
Perform tasks like driver installation, certificate management, and scheduling by following the on-screen instructions.
Use the Settings Tab to customize the appearance and layout.
Refer to the Help Tab for further guidance.
Known Issues and Limitations
Some tasks require elevated privileges and will prompt for admin credentials.
Network connectivity is required for certain features, such as weather information and remote operations.

**Future Improvements**
Add integration with third-party APIs for enhanced system diagnostics.
Expand task scheduling to include custom scripts and more system utilities.
Considering to allow credential swapping from user to admin account to prevent the need to log-out/in each time you require admin access for a process.

**Contributing**
Contributions are welcome! If you encounter a bug or have a feature request, open an issue, message me on Linked-in, or submit a pull request on the GitHub repository.

**Support**
For issues, visit the GitHub repository: GitHub Repository

**License**
See the LICENSE file for details.
