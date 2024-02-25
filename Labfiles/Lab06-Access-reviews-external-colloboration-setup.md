# Lab 6: Configure Access reviews and external colloboration setup

## Exercise 1: Configure Access reviews

### Task 1: Configure access review

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

