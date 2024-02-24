# Lab 1: Setup Hybrid Identity with On-Prem AD and Entra ID

## Task 1: Active Directory Setup

1. Launch the Server Manager program, press the Windows Logo Key and search for “Server Manager”. An application should show up on the list. Click on it to launch the program.
2. Look for “Manage” on the top right of the menu bar. Click on it and then select “Add Roles and Features.” A pop-up window will open immediately. This pop-up window is the installer wizard that guides you with the roles and features setup.
3. On the left side of the window, you’ll see a list of all the checkpoints you encounter in this stage. Click “Next”.
4. At the “Installation Type” checkpoint select “Role-based or feature based installation” radio button and then click “Next”.
5. On the “Server Selection” checkpoint, select “Select a server from the server pool” radio button. This lists a server installed on your machine. Please, click on the desired server once to select it and click “Next.”
6. At the “Select Server Roles” checkpoint, select the role for the server. In the centre of the window, there is a list of all the roles that you can assign to your server machine. Search for “Active Directory Domain Services”.
7. Next, a pop-up window will be displayed. This is the checkpoint for adding new features. Navigate on the “Add features” button at the bottom of the window and a list of available features will be displayed.
8. Next simply click “next” without making modifications to any other settings.
9. You will be redirected to the adding “Active Directory Domain Services” feature once the previous step is complete. On the installer wizard window, click “Next”.
10. You’ll see a summary of your selected options here. Have a look at them carefully, and if you think you’ve made a mistake at any of the earlier checkpoints, you can go back and fix it by clicking “previous.” Then, click “Install” button, once you’re satisfied with your selections at the “Confirmation” checkpoint.
11. The wizard will then begin installation. The time of install depends on your machine’s hardware configuration and what features you’ve selected to be installed. Please make sure not to interrupt the installation. Once the installation is complete, click the “Close” button.
12. Relaunch “Server Manager” if you have already closed it. On your Server Manager dashboard, you’ll should see a yellow triangle warning sign on the top right of the window near the menu bar. This sign appears only if Active Directory Domain Services was properly installed.
13. Click on the warning sign and a dropdown list will show you the required actions termed “post-deployment configuration.”
14. Look for the “Promote this server to a domain controller” option and click on it.
