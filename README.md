# Employee Raise Issue -- Record Producer & Service Portal Integration

## Project Overview

The **Employee Raise Issue** project is a ServiceNow application that
allows employees to submit issues through a Record Producer integrated
with the Service Portal. Submitted issues are stored in a custom table
and can be reviewed and managed by the appropriate users.

## Objectives

-   Provide employees with a simple way to raise issues.
-   Capture issue details through a Record Producer.
-   Store submitted information in a custom ServiceNow table.
-   Make the issue-submission experience available through the Service
    Portal.
-   Validate that submitted records are created and displayed as
    expected.

## Main Features

-   Custom application and custom table for employee issues.
-   Fields for issue information, including requester, category,
    subcategory, priority, assignment group, short description, and
    state.
-   UI policies and field dependencies.
-   Record Producer for submitting an issue.
-   Service Portal page for accessing the submission experience.
-   Widgets and testing of the submission flow.

## Technology

-   **Platform:** ServiceNow
-   **Main components:** Custom Application, Custom Table, UI Policies,
    Record Producer, Service Portal, Widgets

## Project Phases

1.  **Creating a Custom Application** -- Set up the application.
2.  **Custom Table and Fields** -- Create the table and required fields.
3.  **UI Policies and Dependency** -- Configure field behavior and
    dependencies.
4.  **Record Producer** -- Create the employee issue submission form.
5.  **Service Portal** -- Configure the portal experience.
6.  **Widgets and Adding to Page** -- Configure widgets and add them to
    the relevant page.
7.  **Testing and Validation** -- Test the submission and verify the
    resulting records.
8.  **Conclusion** -- Summarize the completed project.

## Issue Submission Workflow

1.  The employee opens the issue submission form in the Service Portal.
2.  The employee enters the requested issue details.
3.  The employee submits the Record Producer form.
4.  ServiceNow creates a record in the custom issue table.
5.  The submitted record can be reviewed in the table.

## Documentation

Project documentation and phase-wise reports can be kept in the `docs/`
folder. Add the corresponding files there so the links below work.

-   [Main Project Documentation] : https://drive.google.com/drive/folders/1yJlpVWrvZsPCckE1BiPxbc-YJ_dJG87j?usp=sharing


## Project Demo Video

[Watch the Employee Raise Issue project
demo](PASTE_YOUR_VIDEO_LINK_HERE)

> Replace `PASTE_YOUR_VIDEO_LINK_HERE` with the shareable URL of your
> screen-recording video (for example, a Google Drive or YouTube link).
> Make sure the video sharing permission allows viewers to open it.

## Setup and Usage

This project is configured in a ServiceNow instance.

1.  Open the ServiceNow instance and select the relevant application
    scope.
2.  Confirm that the custom table and its fields are available.
3.  Confirm that the UI policies and dependencies are configured.
4.  Open the Record Producer and verify its variables and target table.
5.  Open the Service Portal page and verify that the submission form is
    available.
6.  Submit a test issue and verify that a record is created in the
    custom table.

> Exact instance URLs, credentials, and environment-specific
> configuration are not included in this README.

## Testing

Use a test submission to verify the following:

-   The form is accessible from the Service Portal.
-   Required issue details can be entered.
-   Field behavior and dependencies work as configured.
-   Submitting the form creates a record in the custom table.
-   The saved record contains the submitted information.

## Expected Outcome

Employees can submit issues through the Service Portal, and the
submitted information is stored in the custom ServiceNow table for
review and management.

## Author

Project: **Employee Raise Issue -- Record Producer & Service Portal
Integration**
