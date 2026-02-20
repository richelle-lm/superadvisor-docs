# Notifications 

## Overview
The **Notifications** in **Super Advisor** serves as the command post for advisor activity, ensuring that critical updates regarding tasks, meetings, and client interactions are never missed. The system offers a dual-layer approach to information management: an in-app sidebar for immediate, granular review of specific events, and a robust backend configuration menu for managing email frequency and subscription logic.

Users can toggle between **Realtime** alerts for immediate awareness or **Digest** summaries to minimize distraction. Furthermore, the **Auto-Subscribe** logic allows advisors to automate which households trigger alerts based on their specific relationship (e.g., Primary Advisor status), ensuring that users only receive notifications relevant to their specific book of business.

### Accessing and Filtering In-App Notifications
Access your activity feed directly through the global navigation bar to review updates.

1. Click the **Notification Settings** (bell icon) in the navigation bar.
2. A side pop-up will appear displaying a list of **All Notifications** (distinguished by **Read** and **Unread** statuses).
3. **Filter by Type:** Narrow down the list by selecting specific event categories:
    * Comment Created
    * Meeting Requested
    * Note Created
    * Note Edited
    * Task Assigned
    * User Mentioned
4. **Filter by Date:** Isolate notifications within specific timeframes:
    * **Years:** 2025, 2026
    * **Ranges:** 3M (Last 3 Months), 6M (Last 6 Months), or All.

### Configuring Notification Preferences
To control how and when you receive external alerts (emails), configure your global profile settings.
1. Click on your **User Profile** icon.
2. Select **Notification Settings** from the dropdown menu.
3. Set **Notification Frequency**: Choose how the system delivers updates:
    * **Realtime:** Get notified immediately via email when events occur.
    * **Digest:** Receive a summary email at specific times of the day.
4. Configure **Digest Settings** (*If Digest is selected*):
    * **Digest Times:** Select one or more specific times to receive the summary.
    * **Timezone:** Select your local time from the 418 timezones available to ensure delivery aligns with your working hours.
    * **Additional Options:** Check "Omit read notifications" to exclude items you have already viewed in the app from your email digest.

![Notification Frequency](../../assets/images/general/notification%20-%20digest.png)

### Selecting Notification Types
Customize specifically which events trigger an email notification.

1. Navigate to the **Notification Types** section within **Notification Settings**.
2. Toggle the following options on or off based on your preference:
* **Task Assignments:** When a task is assigned specifically to you.
* **Task Status Updates:** When a task you are subscribed to moves to "In Review" or "Done."
* **Comments:** When someone comments on an item you are subscribed to.
* **Document Uploads:** When documents are uploaded to households you manage.
* **Notes:** When notes are created or edited on items you are subscribed to.
* **Meetings:** When meetings are requested or scheduled.
* **Mentions:** Note: This setting is "Always on." You will always receive an alert when mentioned in a comment or note.

![Notification Types](../../assets/images/general/notification%20-%20types.png)

### Managing Auto-Subscribe Filters
Control the logic for which contacts or households automatically subscribe you to their activity streams. This setting prevents alert fatigue by ensuring you only follow relevant accounts automatically.

![Auto-subscribe Filters](../../assets/images/general/notification%20-%20auto%20-%20subscribe.png)

1. Navigate to the **Auto-Subscribe Filter** section.
2. Select one or multiple criteria for automatic subscription:
* **All contacts:** Auto-subscribes you to activity for any contact/household in the entire organization.
* **Contacts where I am Primary Advisor:** Auto-subscribes you only when you are listed as the Primary Advisor.
* **Contacts for specific Primary Advisors:** Auto-subscribes you when the contact belongs to a specific advisor you select (useful for support staff).
* **Contacts with no Primary Advisor:** Auto-subscribes you to unassigned contacts.

:::note NOTE         
These settings control automatic subscriptions. You can still manually subscribe or unsubscribe to any specific entity (Task, Note, etc.) at any time.
:::