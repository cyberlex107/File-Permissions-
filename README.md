<h1>Updating File Permissions</h1>



<h2>Description</h2>
The research team at my organization needs to update the file permissions for certain files and directories within the projects directory. The permissions do not currently reflect the level of authorization that should be given. Check and updating these permissions will help keep their system secure. To complete this task, I performed the following tasks: 
<br />


<h2>Languages and Utilities Used</h2>

- <b>LINUX Commands</b> 
- <b>BASH</b>

<h2>Environments Used </h2>

- <b>LINUX</b> 

<h2>Program walk-through:</h2>

<p align="center">
Check file and directory details: <br/>
<img src="https://imgur.com/A1s4bML.png" height="80%" width="80%" alt="File permissions Steps"/>
<br />
Change file permissions: The organization determined that "other" shouldn't have "write" access to any of their files. To comply with this, I referred to the file permissions that I previously returned. I determined that "project_k.txt" must have the write access removed for "other".   <br/>
<img src="https://imgur.com/oedEBbf.png" height="80%" width="80%" alt="File permissions Steps"/>
<br />
Change file permissions on a hidden files: The research team at my organization recently archived "project_x.txt". They do not want anyone to have "write" access to this project, but the "user" and "group" should have "read" access. <br/>
<img src="https://imgur.com/jULUAPm.png" height="80%" width="80%" alt="File permissions Steps"/>
<br />
Change directory permissions: My organization only wants the "researcher2" user to have access to the "drafts directory" and its contents. This means that no one other than "researcher2" should have "execute" permissions.    <br/>
<img src="https://imgur.com/pfLh3wV.png" height="80%" width="80%" alt="File permissions Steps"/>
<br />
Summary: I changed multiple permissions to match the level of authorization my organization wanted for files and directories in the projects directory. The first step in this was using "ls-la" to check the permissions for the directory. This informed my decisions in the following steps. I then used the "chmod" command multiple times to change the permissions on files and directories.   <br/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
