# Detection-Lab
Objective



Create a new dashboard panel named Firewall Exception Added to monitor Windows Firewall exception rules that have been added. The panel should display the Time, Computer, Profile Changed, Rule Name, and Rule ID, with results sorted in ascending order from the earliest to the latest event.

Skills Learned


reated and customized dashboard panels to visualize Windows security events.
Queried and filtered Windows Event Logs using Splunk Search Processing Language (SPL).
Monitored Windows Firewall activity by identifying newly added firewall exception rules.
Extracted and displayed key event fields, including Time, Computer, Profile Changed, Rule Name, and Rule ID.
Sorted search results chronologically to improve event analysis and investigation.
Built dashboards to support Security Operations Center (SOC) monitoring and threat detection.
Analyzed Windows endpoint activity to identify configuration changes and potential security risks.
Improved log analysis skills by working with Windows security event data and field extractions.
Developed dashboards that enhance visibility into system changes and support incident investigations.
Applied Splunk best practices for creating clear, actionable security monitoring dashboards.

[Bullet Points - Remove this afterwards]


Steps
Create a New Serach 

Example 1 
<img width="810" height="329" alt="image" src="https://github.com/user-attachments/assets/2f5d542a-c720-4982-ad00-6e2b028eeaab" />

look up Event ID for windows firewall exception list event id
Confirmed Event ID is 4946 (added),
Example 2 
<img width="663" height="120" alt="image" src="https://github.com/user-attachments/assets/321fe6df-e46f-46d3-8ec7-4c8f53b3e08e" />

Opened Splunk and looked for Host for windows with event code 4946
Example 3 
<img width="762" height="237" alt="image" src="https://github.com/user-attachments/assets/aedc4fc9-927e-4534-a591-a04a5bd16192" />

I then sorted the information by the request of the SOC manager ( time, Computer, Profile Changed, Rule Name, and Rule ID) 
Example 4 
<img width="1804" height="807" alt="image" src="https://github.com/user-attachments/assets/47fb84d4-3e88-45c9-b559-6cceb5aa659e" />

One Last thing, Sort alerts by the earlist time 
Example 5 
<img width="1804" height="807" alt="image" src="https://github.com/user-attachments/assets/ef108b4c-f4ce-4dc3-b70f-26a96186e4fd" />

Save to Existing Dashbboard 
Example 6
<img width="544" height="308" alt="image" src="https://github.com/user-attachments/assets/85389cc2-8a3e-4d6f-9ec3-8834f18bd843" />




