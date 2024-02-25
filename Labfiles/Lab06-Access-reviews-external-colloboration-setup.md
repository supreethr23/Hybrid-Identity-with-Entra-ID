# Lab 6: Configure Access reviews and external colloboration setup

## Exercise 1: Configure Access reviews

### Task 1: Configure access review

In this task, you will configure an access review in Microsoft Entra ID to review access permissions for Teams and Groups. The access review will include all users and will recur monthly. Reviewers will be selected from a specific user group, and notifications will be sent to all users at the end of the review. The review will auto-apply results to resources and take recommendations if reviewers don't respond. Ensure the settings are accurate before creating the access review.

1. Navigate to **Microsoft Entra ID** and select **Identity governance** under Manage.

1. Select **Access reviews** from the left pane.

1. Select **+ New access review**.

1. On **New access review** page, provide the below settings

   | Setting | Value |
   |--------|------|
   | Select what to review | Teams + Groups |
   | Review scope | select Teams + groups |
   | Groups | search and select **All users** from the lsit |
   | Scope | All users |

1. Select **Next:Reviews**

   | Setting | Value |
   |--------|------|
   | Select reviewers | Selected user(s) or group(s) |
   | Users or groups | click **+ Select Reviewers** and select **ODL_USER XXXX** from the list |
   | Review Recurrence | Monthly |

1. Select **Next:Settings**

   | Setting | Value |
   |--------|------|
   | Auto apply results to resource | Selected the checkbox |
   | if reviewers dont respond | Take recommendation |
   | At end of review, send notification to | click **+ Select Recipients** and select **All users** from the list  |

1. Select **Next:Review + Create** and enter **AccessreviewforAllusers** to the **Review name**

1. Verify the settings once again and select **Create** to create the access review.

### Task 2: Review access to groups and applications in access reviews

1. Sign in to My Access at [myaccess](https://myaccess.microsoft.com/)

1. Select **Access reviews** from the left menu to see a list of pending access reviews assigned to you.

1. After you open My Access under Groups and Apps, you can see:

      * Name: The name of the access review.
      * Due: The due date for the review. After this date, denied users could be removed from the group or app being reviewed.
      * Resource: The name of the resource under review.
      * Progress: The number of users reviewed over the total number of users part of this access review.

1. Select the name of an access review to get started.

1. After it opens, you'll see the list of users in scope for the access review.

1. There are two ways that you can approve or deny access:

    - You can manually approve or deny access for one or more users.
    - You can accept the system recommendations.

1. **Manually review access for one or more users** - follow the below steps

    - Review the list of users and decide whether to approve or deny their continued access.

    - Select one or more users by selecting the circle next to their names.

    - Select Approve or Deny on the bar.

    - If you're unsure if a user should continue to have access, you can select Don't know. The user gets to keep their access, and your choice is recorded in the audit logs. Keep in mind that any information you provide is available to other reviewers. They can read your comments and take them into account when they review the request.

    - The administrator of the access review might require you to supply a reason for your decision in the Reason box, even when a reason isn't required. You can still provide a reason for your decision. The information that you include is available to other approvers for review.

     - Select Submit.

    - You can change your response at any time until the access review has ended. If you want to change your response, select the row and update the response. For example, you can approve a previously denied user or deny a previously approved user.

1. **Review access based on recommendations** - Follow the below steps

    - To make access reviews easier and faster for you, Azure provides recommendations that you can accept with a single selection. There are two ways that the system generates recommendations for the reviewer. One method is by the user's sign-in activity. If a user has been inactive for 30 days or more, the system recommends that the reviewer deny access.

    - The other method is based on the access that the user's peers have. If the user doesn't have the same access as their peers, the system recommends that the reviewer deny that user access.

    - If you have No sign-in within 30 days or Peer outlier enabled, follow these steps to accept recommendations:

    - Select one or more users, and then select Accept recommendations Or to accept recommendations for all unreviewed users, make sure that no users are selected and then select the Accept recommendations button on the top bar.

    - Select Submit to accept the recommendations.
