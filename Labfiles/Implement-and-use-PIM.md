# Lab 3: Implement and use Privileged Identity Management

## Task 1 - Assign Azure resource roles

1. Sign in to [https://entra.microsoft.com](https://entra.microsoft.com) using a Global Administrator account.

2. Search for and then select **Privileged Identity Management.**

3. In the Privileged Identity Management page, in the left navigation, select **Micrososft Entra roles.**

4. In the left navigation menu, under **Manage**, select **Roles** to see the list of Entra roles.

8. On the top menu, select + **Add assignments**.

9. In the Add assignments page, select the **Select role** menu and then select **Gloabl Administrator.**

10. Under **Select member(s),** select **No member selected**.

11. In the Select members pane, select the following users and then chose **Select**.
    
    

13. Select **Next**.

14. On the **Settings** tab, under **Assignment type**, select **Eligible**.

   - **Eligible** assignments require the member of the role to perform an action to use the role. Actions might include performing a multi-factor authentication (MFA) check, providing a business justification, or requesting approval from designated approvers.

   - **Active** assignments do not require the member to perform any action to use the role. Members assigned as active have the privileges always assigned to the role.

14. Specify an assignment duration by changing the start and end dates and times.

15. When finished, select **Assign**.

16. After the new role assignment is created, a status notification is displayed.

## Task 2 - Update or remove an existing resource role assignment

Follow these steps to update or remove an existing role assignment.

1. Open **Microsoft Entra Privileged Identity Management**.

2. Select **Azure resources**.

3. Select the subscription you want to manage to open its overview page.

4. Under **Manage**, select **Assignments**.

5. On the **Eligible assignments** tab, in the Action column, review the available options.

6. Select **Remove**.

7. In the **Remove** dialog box, review the information and then select **Yes**.
