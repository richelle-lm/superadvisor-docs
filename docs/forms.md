# Forms

## Overview

The **Forms** module empowers your team to gather structured data from clients efficiently. Instead of relying on back-and-forth emails or manual data entry, you can create customized digital questionnaires for everything from risk assessments to new account applications.

Forms can be sent directly to clients for self-completion or used internally by your team to ensure all necessary data is captured during meetings. This module tracks the lifecycle of every form—from draft to submission—ensuring no information is lost.

## Dashboard Views

The main Forms dashboard provides a clear overview of all data collection activities.

![Forms Dashboard](./assets/images/forms/forms-dashboard.png)

Status Tabs:

    * All: A comprehensive list of every form record.
    * Draft: Forms that are being built or have been started but not yet sent.
    * Submitted: Completed forms returned by clients or finished by the team.
Forms List: The table displays key details for tracking progress:
    * Template Name: The specific questionnaire used (e.g., "Risk Profile 2024").
    * Target: The recipient (Client or Household) the form is assigned to.
    * Status: Current state (e.g., Sent, Viewed, Submitted).
    * Submitted at: The timestamp of completion.

## How to Manage Templates

Before sending a form, you must define the questions.

1. Navigate to Forms > Manage Templates.
2. Click Create Template or select an existing one to edit.
3. Basic Info: Enter the Name and Description for the template.
4. Add Questions:
    * Click Add Field to insert a new question block.
    * Edit Question: Type your query text.
    * Edit Description: Add helper text for the respondent.
    * Field Type: Choose the input format: Text, Text Area, Number, Date, Currency, Checkbox, Single Select, Multi-select, URL.
5. Data Mapping: For each new field, decide where the data goes:
    * Track in form only: Data lives only in this submission record.
    * Save to custom fields: Data automatically updates the client's profile record.
6. Save your template.

### How to Send a Form

1. Click the Send Form button on the dashboard.
2. Select Recipient: Choose "Who will receive this form?" by searching for a specific client or contact.
3. Select Template: Choose the appropriate form template from your library.
4. Set Due Date: Specify "When is this due?" to give the recipient a deadline.
5. Choose Completion Method:
    * Client completes: The system emails the form link to the client for them to fill out remotely.
    * Team member completes: The form opens immediately for you or a colleague to fill out (e.g., during a live meeting).
6. Click Send (or Start for internal completion).