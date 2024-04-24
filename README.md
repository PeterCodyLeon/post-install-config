
![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/ebe91775-55c0-4c17-b51c-0dd7329980ed)


Post Installation Setup
-----------


In addition to emails, clients/users can also use an online form to create tickets. Help topics helps maps online inquiries to a department and assigns priority without the need for the user to select a department or/and ticket priority. This gives you ability to route inquiries without exposing internal departments.



-----------
Environments and Technologies Used

Windows 10

Internet Information Services (IIS)



Installation Steps

Step 1 : Log into osticket using the credentials you made. 



![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/73293075-cc67-4291-87a3-12b4d2525ae7)



![image](https://github.com/PeterCodyLeon/osticket-prereqs/assets/161895166/9f5bd5d8-b2f7-4761-a958-45d8389ce1a3)

-----------

Step 2: Configure Roles

Make sure you are in the Admin panel (check the top-right of the screen to see which panel you are in)
If it says "Agent," you are in the Admin panel

Select the Agent tab > Roles > Add New Role

Name: Supreme Admin

Select Permissions tab and check every box under the "Tickets," "Tasks," and "Knowledgebase" sections

Select Add Role

![aw](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/a3d47e98-7377-4d94-9bcb-bf7ae3bb0279)

![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/8a05d621-c0de-4573-b16e-3e1f02c0cfd2)


![project 1](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/cab65cec-aaca-4c59-b385-cf7aebf866ca)
-----------

Step 3: Configure Departments

Ensure you are still in the Admin panel

Select the Agent tab > Departments > Add New Department

Name: System Administrators

Select Create Department

![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/c63ebd21-b31f-4a1a-854e-f30b6b081a85)


![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/bd7904ec-e4d5-4419-9c9b-99c29aa0d765)

-----------


Step 4: Configure Teams

Select the Agent tab > Teams > Add New Team

Name: Level II Support

Go to the Members tab and select yourself in "Select Agent" dropdown menu, then select create team

![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/c7b02b19-894c-4af1-ba8a-495bd7da9e83)


![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/a3648c83-0e1c-4758-81b7-41b4a2c63e05)


![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/80dd8eeb-ea5c-417d-aa94-94ad1d496f44)

-----------

Step 5: Allow Anyone to Create Tickets

Select Settings > User Settings

Make sure the following box is unchecked:

Registration Required: Require registration and login to create tickets


![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/ba04427e-69ef-48f3-a498-fab424510a23)


