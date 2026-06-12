<h1>What is Active Directory?</h1>
<img width="137" height="77" alt="giphy" src="https://github.com/user-attachments/assets/b71e2960-3c33-4cb6-88ba-4ee81152916a" />
<p>Active Directory is the backbone of the corporate world. It simplifies the management of devices and users within a corporate environment. </p>

<h2>Key Concepts</h2>

<p>A Windows Domain centralises the administration of users and computers into a single managed environment.  </p>
<p>Active Directory: The central repository storing all objects (users, computers, groups, etc)</p>
<p>Domain Controller: The server running AD services; handl;es all authentication</p>

<h2>Active Directory Basics</h2>

<p>Users: Are one of the most common object types in AD. Users are one of the objects known as security principals, meaning they can be authenticated by the domain and assigned privileges. </p>
<p>Machines: Another type of object within AD. For every computer that joins the AD domain, a machine object will be created. </p>

<h2>Active Directory Users and Computers</h2>

<p>Checking our machine, we can see an organizational unit called Matrix. Under Matrix, we can see five OUs for IT, Management, Marketing, R&D, and Sales.</p>
<img width="274" height="133" alt="1" src="https://github.com/user-attachments/assets/6b932831-c817-4759-80fa-da9d955a28c0" />
<p>Let's now look at the users within the enterprise. In the picture, you can see all users and the departments they're in. </p>
<img width="893" height="630" alt="2" src="https://github.com/user-attachments/assets/e5f84370-d339-45b5-86b6-e130943c8016" />

<h2>Managing Users in AD</h2>

<p>One of the cool things you can do in AD is to give specific users control over some OUs. The process is called delegation, and it allows you to grant users specific privileges to perform advanced tasks on OUs without needing a domain administrator to step in. </p>
<p>In the image, I added Christine to the delegation group and now I can give her permissions nobody else can have.</p>
<img width="890" height="621" alt="3" src="https://github.com/user-attachments/assets/fe2c9719-7935-4d1e-b189-5f593f01c12c" />
<img width="731" height="447" alt="4" src="https://github.com/user-attachments/assets/9875f6ef-ee5b-4d9f-bf29-bbf8a21cf5ef" />
