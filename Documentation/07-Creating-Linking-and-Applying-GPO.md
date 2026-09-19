### Creating, Linking, and Applying a GPO

Created a Group Policy Object (GPO) to configure centralized settings for computers within the Active Directory environment. The GPO was linked to the appropriate Organizational Unit (OU) so that its settings could be applied to the computers and users within that OU.

After configuring the GPO, verified that the policy was successfully applied to CLIENT01.

Tools > GPO

#### Creating the GPO

Created a new GPO using the Group Policy Management Console (GPMC).

Click Create a GPO in this domain, and link it here...

![Create GPO](../Screenshots/07-CreateGPO.png)

Name it: IT message 

![GPO Name](../Screenshots/07-it-msg.png)

Right click > IT message > Edit

![GPO Edit](../Screenshots/07-Edit-it-msg.png)

Computer Configuration > Policies > Windows Settings > Security Settings > Local Policies > Security Options 

![GPO Name](../Screenshots/07-Edit-GPO.png)

#### Test the GPO

![GPO Name](../Screenshots/07-Confirm-GPO.png)
