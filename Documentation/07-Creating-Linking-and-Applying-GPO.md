### Creating, Linking, and Applying a GPO

Created a Group Policy Object (GPO) to configure centralized settings for computers within the Active Directory environment. The GPO was linked to the appropriate Organizational Unit (OU) so that its settings could be applied to the computers and users within that OU.

After configuring the GPO, verified that the policy was successfully applied to CLIENT01.

Tools > GPO

#### Creating the GPO

Created a new GPO using the Group Policy Management Console (GPMC).

![Create GPO](../Screenshots/07-CreateGPO.png)
(../Screenshots/07-it-msg.png)
#### Linking the GPO

Linked the newly created GPO to the appropriate Organizational Unit (OU) containing CLIENT01.

![Link GPO](screenshots/07-link-gpo.png)

#### Configuring the GPO

Edited the GPO settings using the Group Policy Management Editor to define the desired policy configuration.

![Edit GPO](screenshots/07-edit-gpo.png)

#### Applying and Verifying the GPO

Updated the Group Policy settings on CLIENT01 and verified that the GPO was successfully applied.

![GPO Verification](screenshots/07-gpo-verification.png)
