# Ticket-1003-Facebook-is-gone

# Introduction
This activity simulates an IT Support ticket submitted by a user. Your task is to resolve the issue and document the process, as you would using a ticketing system.  
To troubleshoot this ticket, you will need to import and launch a Virtual Machine named Ticket #1003 using VirtualBox.
# Objectives
Resolve ticket #1003 and document the process.
Equipment/Requirements
Computer with internet connection and VirtualBox installed.
The Ticket #1003 VM (Open Virtual Appliance (OVA) file).

Ticket ID #
1003
User Name
Learner01
User’s email
learner01@TechSolutions.com
Priority
Medium
Category
Network
Status

ESCALATE
Subject
Facebook is gone
Asset
capstone120
Assigned to
Gregg Nicholas
Description
Hey IT Team,

This is Learner01, Social Media Manager. I can't seem to reach Facebook—the Edge browser says, "Hmmm… can't reach this page. Moved permanently to a new web address. 
ERR_ADDRESS_INVALID."

Other websites are working fine. Could you please get me back on the social grind?

Thank you,
Learner01

#Tasks
Upon not being able to visit Facebook website, I first deleted all cookies and cache in the browsers settings. Then I changed the dns server to google in the browsers settings. Then I did an ipconfig /flushdns in windows cmnd. When non of this worked. I checked blocked lists in browser as well as the OS firewall. Finally, I decided this was a job for chrome, downloaded and installed chrome web browser. Where I found that this user is temporarily blocked from Facebook.
# Resolution (Internal-facing)
Started by clearing all cookies and cache in the browser’s settings, which can help remove any stored data causing conflicts. When that didn’t resolve the issue, I changed the DNS server to Google’s DNS within the browser’s settings to rule out DNS configuration issues, followed by running ipconfig flush/dns in Windows Command Prompt to clear and refresh the local DNS cache.
When these steps didn't work, I next checked the browser’s blocked site list and reviewed the firewall settings on the operating system to ensure that Facebook wasn’t being blocked at the system level. With no issues found, I decided to test access through a different browser, so I downloaded and installed Google Chrome.
Upon opening Facebook in Chrome, I discovered that the user was temporarily blocked from Facebook, which explained the access issue. 

# Resolution (Client-facing)
Subject: Update on Your Support Ticket [1002]

Hi Learner01,

I’ve escalated this case as it appears that Facebook has temporarily banned this login. For context, here are the steps I took to troubleshoot the issue:

Cleared all cookies and cache in the browser’s settings.
Changed the DNS server to Google’s DNS within the browser settings.
Ran ipconfig /flushdns in the Windows Command Prompt to refresh the local DNS cache.
Checked the browser’s blocked site list and reviewed the OS firewall settings to ensure Facebook wasn’t being blocked at the system level.
Installed Google Chrome to test access through an alternate browser.
After completing these steps, I found that the user is temporarily blocked from Facebook, which seems to be the root cause. Please advise on the next steps.

Best regards,
Gregg

![Displaying temporary facebook ban](https://github.com/GreggNicholas/Ticket-1003-Facebook-is-gone/blob/main/Screen%20Shot%202024-12-01%20at%2022.26.24%20PM.png?raw=true)
