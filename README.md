# Detection-Lab
Objective



Create a new dashboard panel named Firewall Exception Added to monitor Windows Firewall exception rules that have been added. The panel should display the Time, Computer, Profile Changed, Rule Name, and Rule ID, with results sorted in ascending order from the earliest to the latest event.

Skills Learned

•  Researched and identified the correct Windows Security Event ID (4946) for newly added Windows Firewall exception rules. 

•  Investigated Windows Security Event Logs to detect firewall configuration changes and validate newly created firewall exceptions. 

•  Developed a SOC dashboard panel to monitor Windows Firewall rule additions and improve visibility into endpoint security events. 

•  Parsed and displayed critical security event fields, including Time, Computer, Profile Changed, Rule Name, and Rule ID, to support incident investigations. 

•  Organized security events chronologically to establish an accurate timeline for threat analysis and forensic review. 

•  Applied log analysis techniques to identify changes to Windows Firewall policies that could indicate unauthorized system modifications. 

•  Enhanced SOC monitoring by creating a dashboard that enables analysts to quickly detect and investigate firewall rule additions. 

•  Strengthened familiarity with Windows Security auditing, endpoint telemetry, and security event correlation through hands-on detection engineering exercises.

Tools Used 

•	Splunk Enterprise – Created the dashboard panel, searched Windows Security logs, and visualized firewall rule additions.

•	Splunk Search Processing Language (SPL) – Queried Event ID 4946 and extracted relevant event fields for analysis.

•	Windows Security Event Logs – Collected and analyzed security audit events related to Windows Firewall changes.

•	Windows Firewall with Advanced Security (WF.msc) – Generated and validated firewall rule additions within the Windows environment.

•	Windows Event Viewer – Verified Event ID 4946 and reviewed the associated event details.


Steps
Create a New Serach 


Example 1 <img width="810" height="329" alt="image" src="https://github.com/user-attachments/assets/2f5d542a-c720-4982-ad00-6e2b028eeaab" />

look up Event ID for windows firewall exception list event id
Confirmed Event ID is 4946 (added),

Example 2 <img width="663" height="120" alt="image" src="https://github.com/user-attachments/assets/321fe6df-e46f-46d3-8ec7-4c8f53b3e08e" />

Opened Splunk and looked for Host for windows with event code 4946

Example 3 <img width="762" height="237" alt="image" src="https://github.com/user-attachments/assets/aedc4fc9-927e-4534-a591-a04a5bd16192" />

I then sorted the information by the request of the SOC manager ( time, Computer, Profile Changed, Rule Name, and Rule ID) 

Example 4 <img width="1804" height="807" alt="image" src="https://github.com/user-attachments/assets/47fb84d4-3e88-45c9-b559-6cceb5aa659e" />

One Last thing, Sort alerts by the earlist time 

Example 5 <img width="1804" height="807" alt="image" src="https://github.com/user-attachments/assets/ef108b4c-f4ce-4dc3-b70f-26a96186e4fd" />

Save to Existing Dashbboard 

Example 6<img width="544" height="308" alt="image" src="https://github.com/user-attachments/assets/85389cc2-8a3e-4d6f-9ec3-8834f18bd843" />




