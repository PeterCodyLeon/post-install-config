![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/1388cd14-d787-4154-9738-eb8757144c62)
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


Step 6: Configure Agents

Select the Agent tab > Add New Agents

Name: Jane Doe

Email : jane.doe(@)osticket.com

Username: jane.doe

Click Set Password and uncheck the box that says "Send the Agent a Password Reset Email"

Set your passowrd and ensure that it has secure credentials.

Uncheck the box that says "Require Password Change at Next Login"

Click select password

![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/6b844424-1e5a-4556-bf39-6bf93b9cd12a)

![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/59b42166-ad95-4cbc-b6ba-3a0c7118a79e)


Select the Access tab

Under Primary Department:

Select the Department dropdown menu > System Administrators

Select the Role dropdown menu > Supreme Admin

Extended Accesss

Select Department > Support > Add > Supreme Admin

Select Team tab

Select Team dropdown menu > Level II Support

Select Add

Select Create

![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/74fd9e9b-a553-4308-9b85-82dc53adfb0d)


![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/80969693-d89e-4f4d-83a3-698f524e90c5)


Create another agent John Doe.

Follow the same steps as above, except make some changes to the Primary Department

Select the Department dropdown menu > Support

Select the Role dropdown menu > View Only

Extended Accesss

Select Department > Support > Save Changes


<img width="576" alt="project2 5" src="https://github.com/PeterCodyLeon/post-install-config/assets/161895166/c83589be-5433-4d93-99a9-6a03773b4e32">


![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/c2c53693-3792-4177-8330-e9508246b3d2)


Step 7: Configure Users

Select the Users tab to create a user

Email Address: Karen(@)osticket.com

Full Name: Karen Karen

Select Add User

![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/4f7e12d7-84e7-4985-9876-f9a654ab1a78)


![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/d683b68c-da60-4d68-84c7-789fb11769b3)


Select the User tab again to create another user

Email Address: Ken(@)osticket.com

Full Name: Ken Ken

Select Add User

![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/c834c58c-c50e-4183-801c-f0adfd02e028)


Step 8: Configure Service Level Agreements (SLA)

I will create three  

Go to the Admin Panel then select the Manage tab > SLA > Add New SLA Plan


1: Name: SEV-A

   Grace Period: 1

   Schedule dropdown menu: 24/7

   Select Add Plan

![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/aabf0bf6-3e93-4391-9cdc-6d570f2347ab)

![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/3b5541e8-e2a2-4eb8-8e19-85d82a880251)


2: Name: SEV-B

  Grace Period: 4
 
  Schedule dropdown menu: 24/7

  Select Add Plan
    
![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/83a312ff-1a9c-40fc-91fd-b76e246091cc)


3 :  Name: SEV-C 

   - Grace Period: 8
  
   - Schedule dropdown menu: Monday - Friday 8AM - 5PM with U.S. Holidays
  
   - Select Add Plan

     ![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/4401b776-2bb6-4261-959f-1faee8bbeab8)
     


   Step 9: Configure Help Topics
     
Help topics helps maps online inquiries to a department and assigns priority without the need for the user to select a department or/and ticket priority. This gives you ability to route inquiries without exposing internal departments.

We will create four Help Topics

Select the Manage tab > Help Topics > Add New Help Topic

Business Critical Outage

Personal Computer Issues

Equipment Request

Password Reset

Select Add Topic for each topic.

 1. ![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/942629b3-5355-46bf-9a87-2e07296b9495)

 2. ![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/1c5472a8-ef60-44ac-ba71-4433fc05404a)

 3. ![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/6234b95c-d392-4f43-a5b8-40e2716cc476)

 4. ![image](https://github.com/PeterCodyLeon/post-install-config/assets/161895166/2603893f-1d92-42b3-8a39-035a7904bc02)

