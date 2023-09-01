><h1>Add and manage users with Linux commands  </h1>


<h2>Description</h2>
Another important concept in security is authentication. Authentication is the process of a user proving that they are who they say they are in the system.

When managing this, as a security analyst I will need to ensure

- not all users get access to the system, <br>
- new users (those who are new to the organization or a group) are added to the system, and <br>
- current users who change groups or leave the organization are deleted from the system.
<br />


<h2> Scenario </h2>
A new employee with the username <i>researcher9</i> joins an organization. I have to add them to the system and continue to manage their access during their time with the organization.


<h2>Add a user:</h2>
Adding or removing users and groups are tasks that require root (super user) privileges and we can only do this with the use of the <i>sudo</i> command.<br>

<img src="https://github.com/Bridgetanntighe/ActiveDirectoryLab/assets/134883216/e013dd2b-5ccd-41f9-b21f-d23331ec5f372" height="80%" width="80%" alt="Active Directory Lab"/>

<h2>Assign file ownership:</h2>
The new employee, <i>researcher9</i>, will take responsibility for <i>project_r</i>. In this task, I will make them the owner of the <i>project_r.txt</i> file.<br>
The <i>project_r.txt</i> file is located in the <i>/home/researcher2/projects</i> directory, and owned by the <i>researcher2</i> user.<br>

<img src="https://github.com/Bridgetanntighe/ActiveDirectoryLab/assets/134883216/813dcde0-f7bb-42ab-9130-1c0b83816deb" height="80%" width="80%" alt="Active Directory Lab"/>

<h2>Add the user to a secondary group:</h2>
A couple of months later, this employee's role at the organization has changed, and they are working in both the Research and the Sales departments.<br>

In this task, I will add <i>researcher9</i> to a secondary group <i>(sales_team)</i>. Their primary group is still <i>research_team</i>.<br>
<b><i>Note</b>:Options for Linux commands are case-sensitive</i>
<img src="https://github.com/Bridgetanntighe/ActiveDirectoryLab/assets/134883216/98defd4f-0ea7-49cd-a9d2-68618fed5d1c" height="80%" width="80%" alt="Active Directory Lab"/>

<h2>Delete a user:</h2>
A year later, <i>researcher9</i>, decided to leave the company. In this task, I must remove them from the system.<br>

Show below the command to delete and the output message
<img src="https://github.com/Bridgetanntighe/ActiveDirectoryLab/assets/134883216/c9e9370e-0de3-46a0-86b9-f162055665af" height="80%" width="80%" alt="Active Directory Lab"/>


<h2>Conclusion </h2>
This demonstates practical experience using basic Linux Bash shell commands to <br>
- add a new user,<br>
- add a user to a group, <br>
- change user permissions on files, and <br>
- delete a user.

