# Project 07 – Flow Designer

## Objective

Demonstrate the ability to automate business processes in ServiceNow using Flow Designer without writing code.

---

## Skills Demonstrated

- Flow Designer
- Workflow Automation
- Triggers
- Actions
- Conditions
- Approvals
- Notifications
- Task Automation

---

## What is Flow Designer?

Flow Designer is ServiceNow's low-code/no-code automation tool. It allows administrators to automate business processes using drag-and-drop logic instead of scripting.

---

## Example Automation

### New Hardware Request

**Trigger**

A user submits a catalog request for a new laptop.

---

## Flow Process

1. User submits the request.
2. Flow starts automatically.
3. Manager approval is requested.
4. If approved:
   - Create a catalog task.
   - Assign the task to Desktop Support.
   - Notify the technician.
5. Desktop Support prepares the laptop.
6. Notify the user that the laptop is ready.
7. Close the request after delivery.

---

## Flow Components

### Trigger

- Service Catalog Request Created

### Conditions

- Request Type = New Laptop

### Actions

- Request Manager Approval
- Create Catalog Task
- Assign Task
- Send Email Notification
- Update Request Status
- Close Request

---

## Business Benefits

- Faster request fulfillment
- Fewer manual tasks
- Consistent processes
- Reduced human error
- Improved user experience
- Better SLA compliance

---

## Lessons Learned

Flow Designer allows organizations to automate repetitive work while maintaining consistent business processes and reducing manual effort.

---

## Future Improvements

- Add screenshots from my ServiceNow Personal Developer Instance.
- Build multiple automated flows.
- Demonstrate approval workflows.
- Add integrations with Microsoft Teams or Slack.
- Include Flow execution history and testing results.
