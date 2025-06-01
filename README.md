# task-3
1. Install Nessus Essentials
Download Nessus Essentials from the official Tenable website.

Register with a valid email to receive a free activation code.

Install Nessus and enter the activation code during setup.

Wait for plugins to download and compile (this may take some time).

2. Configure the Scan Target
After setup is complete, log in to the Nessus web interface (https://localhost:8834).

Click on "New Scan".

Choose "Basic Network Scan" (or "Advanced Scan" for more control).

Under Targets, enter:

127.0.0.1 or localhost if scanning your own machine.

Or enter your local IP address (e.g., 192.168.x.x).

Optionally, name the scan something like "Localhost Vulnerability Scan".

3. Start a Full Vulnerability Scan
Once your scan configuration is saved, go to “My Scans”.

The scan will begin and may take 30–60 minutes, depending on the system and network.

4. Monitor and Wait for Completion
You’ll see the scan progress in real time.

Nessus will analyze open ports, services, OS, vulnerabilities, and misconfigurations.

5. Review the Scan Report
After completion, click on the scan name to open the results.

You'll see a summary dashboard with:

Total vulnerabilities

Severity breakdown (Critical, High, Medium, Low, Info)

Click on each vulnerability to see:

A detailed description





