# Windows-Diag
Diagnostic Script is designed to automate the process of identifying and reporting common issues on a Windows computer. It consolidates various diagnostic tools and commands into a single batch file, generating a comprehensive, navigable report. The goal is to simplify troubleshooting for IT professionals and users by providing critical system information and detecting common issues.

Functionality:

    Error Log Extraction:
        Pulls critical errors and warnings from the Windows Event Viewer for the past 10 minutes.
        Helps identify recent issues causing system instability.

    Disk Health Check:
        Verifies the fragmentation level of the C: drive.
        Identifies file system errors using chkdsk.

    System Resource Overview:
        Gathers details about CPU and memory usage.
        Displays a list of top resource-consuming processes.

    Driver Status:
        Checks the status of all drivers to detect potential hardware-related issues.

    Installed Software and Updates:
        Lists all installed software.
        Highlights missing or failed updates.

    Final Report:
        Generates a detailed report in text format that is easy to navigate using the keyboard.
        Allows users to access essential diagnostic data in one place.

Key Sections:

    System Health Overview: Displays system uptime, CPU usage, and memory usage.
    Event Log Analysis: Identifies critical events and warnings logged in the last 10 minutes.
    Disk Diagnostics: Checks disk fragmentation and file system integrity.
    Driver Analysis: Lists problematic or outdated drivers.
    Software Inventory: Provides a complete list of installed software and updates.
