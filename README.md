# Automated Diagnostics - Runbook Automation Solution
The Automated Diagnostics Solution is a collection of prebuilt Automation Jobs that retrieve data for investigation, debugging and diagnosing of incidents. 
These are built to work with PagerDuty's [Runbook Automation](https://www.pagerduty.com/platform/automation/runbook/) or the self-hosted [Process Automation](https://www.pagerduty.com/platform/automation/process-software/) - FKA Rundeck Enterprise.

## Getting Started

### Import the Project
1. Download the latest release from the [releases page](https://github.com/rundeckpro/automated-diagnostics-project/releases).
2. In your Runbook or Process Automation instance, create a new Project: Click on the **P** in the upper-left and then click on **New Project+**.
3. In the **Project Name** field, paste the following: `automated-diagnostics`.
4. Fill in the **Label** field with a user-friendly name for this project. For example: _Automated Diagnostics Jobs_
5. Optionally provide a **Description**
6. In your newly created `automated-diagnostics` Project, click on **Project Settings** in the lower left. Select **Import Archive**.
7. Click on **Choose File** and then choose the `automated-diagnostics-xxxx.jar` file from the downloaded release.
8. Leave all of the toggle-options as their default and then click **Import**.

### Import the Tours

## Example Scenario
The Automated Diagnostics Solution is a collection of prebuilt Automation Jobs that retrieve data for investigation, debugging and diagnosing incidents.  The Jobs are designed to be used with minimal configuration by the customer, such that they can start enhancing their incidents immediately.
