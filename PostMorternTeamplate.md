# 0000-00-00 - Postmortem Template

## Description

| Title (3–5 word description of the incident)| Description (2–3 sentences describing the incident. Make it understandable to management and business stakeholders.)     |
|-----------------------|-------------------|
| **Date**              | Date on which the incident began.  This should be the same as the date in the title. |
| **Summary**           | 1-2 sentences summarising the whole incident.  Keep it brief. |
| **Status**            | The current status of the incident.  One of [`Service Up`\|`Service Degraded`\|`Service Down`\|`Service Restored`] |
| **Detection**         | Describe how the incident was detected. Include who, what, where, why, and how.|
| **Custumers Impact**  | Describe which customers were impacted and the exact impact. Include who, what, where, why, and how. If customers reported issues, link those in here as well. |
| **Employees Impact**  | Describe how employees were affected. Include who, what, where, why, and how. |
| **Systems Impact**    | 1-2 sentences summarising the impact that the incident had on our systems. |
| **Resolution**        | Describe how the incident was stabilized. Include who, what, where, why, and how. |
| **Detection**         | The alert that brought the incident onto our radar.  Unless the incident was detected early, this will be the alert that triggered the paging system. |
| **Notification**      | A list of everyone that was notified about the issue.| 
| **Authors**           | A list of everyone involved in writing up the postmortem. |

## Timeline 

A timeline of important events during the course of the incident (Everything should be in the same timezone).

| Time          | Event             | Incident Description |
|---------------|-------------------|----------------------|
| **10/01/2020 00:00:00 UTC**     | Pre-incident      | Add relevant information in chronological order   |
| **10/01/2020 00:00:00 UTC**     | Incident          | Add relevant information in chronological order   |
| **10/01/2020 00:00:00 UTC**     | Post-Incident     | Add relevant information in chronological order   |


## Lessons Learned

### What went well
A bulleted list of things that helped us resolve the incident, or that we managed well during it.  Examples might be minimising client impact, having good documentation that helped to identify the root cause of the incident, or system improvements that made the incident easier to resolve.

### What went wrong
A bulleted list of things that went wrong during the incident.  Poor logging, poor or no documentation, communication issues, and other similar information should go in this section.

### Where we got lucky
A bulleted list of things that we didn't control, but that helped us resolve the incident anyway.  This could include an incident happening outside business hours or someone with knowledge of the incident being on-call, among other things.

## Action Items

Describe what changes have or will be taken to prevent or mitigate this or similar incidents in the future. Changes listed here include but are not limited to: testing, alerting, monitoring, logging, backups, and anything else related. Doing postmortems is an evolving practice inside the organization, so changes to the postmortem process itself should be included as well. Add relevant links to these items tracked in ticketing systems

## Documents / Sources

Links to any documentation that was used to help resolve the incident, written during the incident, or written as a result of the postmortem process, as well as, Links to monitoring, dashboards, logs

## Metrics
|   Metric      | Time              |
|---------------|-------------------|
| When did the incident begin? | first errors recorded |
| When did the incident end? | service restored |
| When did we detect the incident? | alert fired / customer notification |
| Time to Detect | start_time – detect_time |
| Time to Resolve | start_time – end_time |
