# QA Summary Panel

## Overview
QA Summary Panel is a powerful Jira app designed to give teams real-time visibility into QA status, issue progress, and quality trends. It centralizes QA notifications, analytics, and recent changes, making it easy to track and improve release quality directly within Jira.

## The Problem
Jira users often struggle to:
- Quickly see which issues have passed, failed, or been reopened in QA
- Track QA status changes and trends across multiple issues or epics
- Get timely notifications about QA bottlenecks or all-clear moments
- Customize which QA events are most important to their workflow

## How QA Summary Panel Solves It
- Aggregates QA status for all issues in an Epic or Story
- Provides instant notifications for failed, reopened, or all-clear QA states
- Displays transition counts and recent QA status changes
- Offers customizable settings for notifications and panel content
- Seamlessly integrates with Jira issue fields and workflow

## Workflow: Step-by-Step
1. **Install the App**
   - Find QA Summary Panel on the Atlassian Marketplace and install it to your Jira Cloud site.
2. **Set Up QA Status Field**
   - On each issue (Story, Bug, Task and subtask ..), set the QA Status field (Custom Field) to PASS, FAILED, or REOPEN as your team reviews work.
3. **View the QA Summary Panel**
   - Open any Epic or parent issue. The QA Summary Panel will display:
     - Pass/fail/reopen counts
     - Recent QA status changes
     - Transition history and trends
     - All-clear or warning banners
4. **Customize Notifications and Display**
   - Go to the app’s settings panel to choose which notifications, warnings, and lists are shown.
5. **Monitor and Take Action**
   - Use the panel to spot bottlenecks, celebrate all-clear moments, and keep your team release-ready.
6. **Remove the App (if needed)**
   - Go to Jira > Manage Apps, find QA Summary Panel, and click Uninstall.

## Installation
1. Go to the [Atlassian Marketplace](https://marketplace.atlassian.com/) and search for "QA Summary Panel".
2. Click **Get it now** and follow the prompts to install on your Jira Cloud site.

## Setup
- After installation, ensure the QA Status field(Custom field) is available on your issue types.
- Configure the app’s settings to match your team’s workflow and notification preferences.

## Viewing the Panel
- Open any Epic or parent issue in your Jira project.
- The QA Summary Panel will appear, showing real-time QA insights and analytics.

## Understanding and Using the QA Status Custom Field

### Why is the QA Status Field Important?
The **QA Status** custom field is the backbone of the QA Summary Panel. It allows your team to track the quality assurance state (PASS, FAILED, REOPEN, etc.) for each issue. The panel aggregates these values to provide real-time insights, analytics, and notifications across your project.

### How to Locate the QA Status Field
- Open any Jira issue (Story, Bug, Task, etc.).
- Look for the **QA Status** field in the issue details section (usually on the right side).
- If you see the field, you can set its value to reflect the current QA state of the issue.

### What if the QA Status Field is Missing?
If you don’t see the QA Status field in EPIC or Story or bug , task or sub tasks

1. **Check Field Configuration:**  
   - Go to In the bottom right of a Ticket > Configure > Field Configurations.
   <img width="681" height="434" alt="image" src="https://github.com/user-attachments/assets/4b47d777-0166-4409-84ef-c1f464e4b9df" />
   <img width="690" height="424" alt="image" src="https://github.com/user-attachments/assets/73fc190c-78b2-4bdc-9b47-2527f740e4d6" />

   - Ensure **QA Status** is added to the relevant screens and issue types.
2. **Add the Field:**  
   - Go to Jira Settings > Issues > Custom Fields.
   - Click **Add custom field**, search for **QA Status**, and add it to your project screens.
3. **Permissions:**  
   - Make sure you have permission to edit issue fields in your project.

### The Importance of the QA Status Field
- **Accurate Reporting:** The QA Summary Panel relies on this field to display pass/fail/reopen counts and trends.
- **Team Collaboration:** Ensures everyone is on the same page regarding QA progress.
- **Automated Insights:** Without this field, the panel cannot provide real-time QA analytics or notifications.

**Tip:**
Encourage your team to update the QA Status field as part of their workflow. This ensures the QA Summary Panel always reflects the latest project quality state.

## Removing the App
- Go to **Jira Settings > Apps > Manage Apps**.
- Find **QA Summary Panel** and click **Uninstall**.

## Support
For help, feature requests, or bug reports, contact:  
[apps@concertidc.com](mailto:apps@concertidc.com)

## Learn More
- [Company Website](https://www.concertidc.com/)
- [Marketplace Listing](https://marketplace.atlassian.com/apps/641867327)

