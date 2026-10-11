# Assign-Azure-resource-roles-in-Privileged-Identity-Management

Microsoft Entra Privileged Identity Management (PIM) can manage the built-in Azure resource roles, as well as custom roles, including (but not limited to):

  - Owner
  - User Access Administrator
  - Contributor
  - Security Admin
  - Security Manager

Need to make a user eligible for an Azure resource role.

## PIM with Azure resources

### Assign Azure resource roles

  - Search for and then select Microsoft Entra Privileged Identity Management.

  <img width="780" height="432" alt="image" src="https://github.com/user-attachments/assets/bdb3135e-5f33-4ffb-8649-2c951a723bef" />

  -  Select Azure resources in the left navigation
  -  Choose the Subscription and Resource group needed. Then at bottom of the screen, select Manage resource.

  <img width="778" height="417" alt="image" src="https://github.com/user-attachments/assets/5c19b659-78c5-4d73-841d-3f8a914ff7a9" />

  <img width="769" height="423" alt="image" src="https://github.com/user-attachments/assets/a54e3875-444d-4164-91c4-211d27aa1444" />

  <img width="766" height="416" alt="image" src="https://github.com/user-attachments/assets/efab403a-8ad9-4780-98ce-1f2ced961d5d" />

  - In the left navigation menu, under Manage, select Roles to see the list of roles for Azure resources.
  - Select + Add assignments, select role of the user and then select Admin as the member that will be assigning the role from the organization. Then clcik Next.

    <img width="760" height="419" alt="image" src="https://github.com/user-attachments/assets/95e62ae9-9410-47ac-b66f-b546ceeff735" />

  - Assignment type, select Eligible.

  > Eligible assignments require the member of the role to perform an action to use the role. Actions might include performing a multi-factor authentication (MFA) check, providing a business     justification, or requesting approval from designated approvers.

  > Active assignments do not require the member to perform any action to use the role. Members assigned as active have the privileges always assigned to the role.

  - Specify an assignment duration
  - Select Assign

### Update or remove an existing resource role assignment

  - Open Microsoft Entra Privileged Identity Management
  - Select Azure resources
  - Select the Subscription you want to manage, then select the Resource group, and select Manage resource
  - Under Manage, select Assignments
  - On the Eligible assignments tab, in the Action column, review the available options, then switch to the Active assignments tab where your User account should appear under the role
  - Select Remove
  - In the Remove dialog box, review the information and then select Yes

  > This exercise showed how assigning an Azure resource role through Privileged Identity Management, activated it on demand, and removed the assignment.
