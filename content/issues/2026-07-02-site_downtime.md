---
title: Site downtime - July 8th 2026
date: 2026-07-08 23:17:00
resolved: true
resolvedWhen: 2026-07-09 07:30:00
# Possible severity levels: down, disrupted, notice
severity: down
affected:
  - Website
  - Database
section: issue
---

*Post-mortem*

After a careful review, we have determined that the downtime was caused by a small issue in Anubis
which we use to prevent AI grabbers from looking at our website and also to prove that you aren't a robot. One line in this configuration was causing the website to be unable to redirect to the main page correctly. After a few hours of monitoring,
we have considered the issue resolved.

If the website still does not work for you, please clear your cookies and try again. 

If the issue persists, please contact us on our support channels.

We're again sorry for the inconvenience.

Have a nice day!

---

***Resolved*** - The issue has been resolved. {{< track "2026-07-09 07:30:00" >}}

*Update* - A fix has been implemented and we are monitoring the results. Looks like this has been fixed. If you are able to, please clear cookies and try reconnecting again. {{< track "2026-07-09 02:20:00" >}}

*Monitoring* - We are monitoring the situation until the dev in charge of the system wakes up. {{< track "2026-07-08 23:50:00" >}}

*Investigating* - we got a report that the website was down. We began investigation. {{< track "2026-07-08 23:17:00" >}}
