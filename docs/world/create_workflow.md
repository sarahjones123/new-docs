
# Contact History

The **Contact History** tab allows you to view, create, and manage interactions with the entity.

## Creating a new contact

Contacts reflect phone, walk-in, call out, and other direct interactions between an entity and the organization.

1. Go to the **CRM > Contact History** tab of an entity.
2. Click **New Touchpoints > New Contact**. The Contact template opens below the Touchpoints grid.
3. Complete the following fields:

	1. **Call Log ID**: System-generated unique number.

	2. **Due**: Select the date when the issue was closed or will be closed (based on the Completed setting).

	3. **Priority**: Select the contact priority.

	4. **Call Number**: Enter the phone number of an entity.

	5. **Completed**: Select Open or Closed to indicate if the issue was resolved.

	6. **From**: Select the contact entity.

	7. **Assigned To**: Select the CoreAdmin assignee (the default is the person currently logged into V3locity).

	8. **Topic**: (Required) Select the topic for the contact.

	9. **Type**: (Required) Select the contact format.

	10. **Description**: Enter information about the contact.

4. Click **Save**. The completed contact record appears in the Touchpoints grid.


## Creating a new meeting
1. Go to the **CRM > Contact History** tab
2. Click **New Touchpoints > New Meeting**. The **Adhoc Meeting Wizard** starts on step 1 - Select Contact or Type.

    !!! note "Note"

        The **Select Contact** step appears only for entities, such as an Employer, who have more than one contact available. Select the check boxes for the contacts attending the meeting, then click Next. The Adhoc Meeting Wizard moves to step 2 - Type.

    [Twemoji]: https://twemoji.twitter.com/
    [emoji search]: ../reference/icons-emojis.md#search

4. On the Type step, complete the following fields:
	1. **Topic**: (Required) Indicates the Subject of the meeting.
	2. **Type**: (Required) Indicates the meeting type.
	3. **Location**: Physical or virtual address for the meeting.
	4. **Sublocation**: Additional meeting location directions, if applicable.
	5. **Objective**: (Required) Purpose of the meeting.
	6. **Description**: Additional meeting information.
	7. **Send Invite**: Use this checkbox to send meeting invite.
	8. **Invite Recepients**: Use this dropdown to select recepients for meeting invite as required.
	9. **Communication Template**: Template used to send the meeting information. Click Set to select a document template for the meeting communication.
	10. **Joint Flag**: Use this checkbox to indicate joint flag.
	11. **This is a Virtual Meeting**: Use this checkbox to indicate the meeting held vitually.
	12. **Attendee**: Selected person attending the meeting.
	13. Scroll down to complete additional information for the meeting, if any.
5. Click **Next**. The Adhoc Meeting Wizard moves to step 3 - Schedule.
6. Select a date you want from the **Find Date** calendar datepicker, then click Retrieve. The Meetings grid displays timeslots for the selected date.
7. Select the **Counselor Requested** checkbox, if applicable.
8. From the available timeslots, select the meeting time you want to schedule, then click **Confirm**. 
9. Click **OK**. The meeting appears in the Touchpoints grid and on the CRM > Calendar tab of an entity.

## Changing or Canceling Meetings

Scheduled meetings can be changed or cancelled when needed.

1. Go to the **CRM > Contact History** tab of an entity.
2. In the **Touchpoints** grid, click the meeting you want change or cancel. The meeting details appear below the Touchpoints grid.
3. At the bottom of the meeting details, click **Edit**.
4. Click one of the following as needed:
	5. **Cancel Meeting**: Opens a Confirm dialog box. Click OK to cancel the meeting.
	6. **Reschedule Meeting**: Opens the Schedule step in the Adhoc Meeting Wizard. Follow steps 5-8 as needed from the topic Creating New Meeting.