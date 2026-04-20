# Thunderbird-Issues
User experienced interruption in Thunderbird access.

<h2>Skills and Tools:</h2>

-Remote Desktop (AnyDesk)\
-Domain knowledge of networking and security\
-Diagnostic and verification skills\
-User communication and customer-service skills\
-Structured troubleshooting methodology

<h2>Initial information:</h2>

User reported Thunderbird failed to start correctly on system start. A notification takes up most of the screen saying it is unable to connect. It gives a few reasons why, like internet outage or firewall rules, but doesn’t offer a way to correct the issue beyond a try again button.

<img src="https://i.imgur.com/Y9LQ3zC.jpeg" height="30%" width="30%" alt="UDR7"/>

<h3>Identify the Problem: </h3>
Thunderbird is unable to connect to comcast email service
<h3>Establish a Theory of Probable Cause: </h3>

1. <s>Internet disconnect
2. Comcast outage
3. System firewall configuration change</s>
4. Invalid credentials/security flag

<h3>Test the Theory to Determine the Cause: </h3>

1. Checked the Google Home app to see if the router was online.
2. Signed into the Comcast web portal for email service.
3. Check firewall config. No changes from last functional time. 
4. Log in to Comcast and change the password.

<h3>Establish a Plan of Action and Implement the Solution:</h3>

1. Log in to Comcast and change the password.
2. Sign out of Comcast and verify account credentials by logging back in.
3. Close Thunderbird
4. Reopen Thunderbird and wait for attempted log in.
5. When prompted for credentials, use the newly updated password.
6. Successful login and return to expected behavior.

<h3>Verify Full System Functionality and Preventative Measures: </h3>

1. Close Thunderbird and full system reboot.
2. On restart, open Thunderbird and observe expected behavior.
3. No preventative measure for a credential update requirement.

<h3>Document Findings, Actions, and Outcomes: </h3>

1. Documentation (Hi)
2. Inform the user: User is informed of the cause of the issue, the solution, and of the newly updated password information. (note that the user previously gave permission for any password changes)



