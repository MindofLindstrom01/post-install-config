<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Installation Steps</h2>

<h3>Step 1.</h3>

![1  search vms](https://github.com/user-attachments/assets/8f347c9d-2c6f-4eb6-bb2d-ccdc6447ae70)

<p>Search for virtual machines in the Azure search bar</p>

<h3>Step 2.</h3>

![2  click create](https://github.com/user-attachments/assets/e9f45eb3-5adb-4d18-91d9-ba355d8af952)

<p>Click create to start the creation of a new Azure virtual machine</p>

<h3>Step 3.</h3>

![3  creating vm](https://github.com/user-attachments/assets/a8933551-d60a-4840-a340-9f69e9a824c9)

<p>Create a new resource group named osTicket. Name the virtual machine osticket-vm. Select Canada Central for the region for space requirements. Select Windows 10 Pro, version 22H2 for the image type. Pick a preferrable size of 2vcpus and 8 GiB of memory.</p>

<h3>Step 4.</h3>

![4  vm user   pass](https://github.com/user-attachments/assets/4ea30ed7-ef86-4bf6-97ae-88b9b7f1f3ef)

<p>Create a username and password for the virtual machine that you will remember. Check the licensing box then select Next</p>

<h3>Step 5.</h3>

![5  next](https://github.com/user-attachments/assets/a4c5502c-7110-433f-b8b5-27412a98894d)

<p>Select Next : Networking ></p>

<h3>Step 6.</h3>

![6  review](https://github.com/user-attachments/assets/1272038b-5da6-4bc5-b751-963cace2cc2e)

<p>Select Review + create</p>

<h3>Step 7.</h3>

![7  create vm](https://github.com/user-attachments/assets/1b8f93ee-a871-4106-b16d-a51fe3b0d45b)

<p>Select create</p>

<h3>Step 8.</h3>

![8  vm created](https://github.com/user-attachments/assets/0b76078c-2bfe-4073-9a5e-b6867504aaf9)

<p>The virtual machine has sucessfully been deployed. Next click go to resource.</p>

<h3>Step 9.</h3>

![9  copy public ip](https://github.com/user-attachments/assets/6532f963-cb25-4139-8140-864e49364589)

<p>Under networking, grab the public IP address to be used in Remote Desktop</p>

<h3>Step 10.</h3>

![10  open remote desktop   add public ip](https://github.com/user-attachments/assets/9aaf1d45-b66b-447d-bf50-d15bd3b69ea3)

<p>Open Remote Desktop Connection and enter the public IP address obtained from the VM. Then click connect</p>

<h3>Step 11.</h3>

![11  more choices](https://github.com/user-attachments/assets/77b1b497-505c-4709-b0a8-3d2b33451842)

<p>Select more choices, use a different account, and then enter the credentials of the VM that you defined earlier. Then click OK</p>

<h3>Step 12.</h3>

![12  link for osticket files](https://github.com/user-attachments/assets/0f494df3-afe9-436d-8de3-134d7746547c)

<p>Download the required files with the link provided <a href="https://drive.google.com/uc?export=download&id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD">here</a></p>

<h3>Step 13.</h3>

![13  download](https://github.com/user-attachments/assets/155bfdfa-8389-4f72-aa81-1688c844c004)

<p>Click download anyway</p>

<h3>Step 14.</h3>

![14  open folder](https://github.com/user-attachments/assets/596b469f-e2d5-456e-a522-bcffbc69a0ef)

<p>Select the folder icon to open the newly downloaded folder</p>

<h3>Step 15.</h3>

![15  click extract](https://github.com/user-attachments/assets/f6ef6912-e67b-4a4a-a318-04d0b3c551da)

<p>Right click the zip file and select extract all</p>

<h3>Step 16.</h3>

![16  extract location](https://github.com/user-attachments/assets/831fc186-a75d-4689-8ca8-c70e6796b709)

<p>Browse or type in Desktop to choose the extraction location then click extract</p>

<h3>Step 17.</h3>

![17  extract complete](https://github.com/user-attachments/assets/db72caa8-3075-4d32-8c1f-53de5ce8f1df)

<p>The newly extracted folder should have now appeared at the designated location</p>

<h3>Step 18.</h3>

![18  open control panel](https://github.com/user-attachments/assets/2e24aad3-2edd-409d-918e-f671fa804fae)

<p>Open control panel by typing it in the Windows search bar</p>

<h3>Step 19.</h3>

![19  go to programs](https://github.com/user-attachments/assets/c3edd406-214a-4f8a-a2f2-89dd38b3fc5c)

<p>Navigate to "Uninstall a program"</p>

<h3>Step 20.</h3>

![20  enabling iis   cgi](https://github.com/user-attachments/assets/80e663d3-ad4a-499a-963f-69976e05c28c)

<p>Click on "Turn Windows features on or off", then enable all of the following inside Internet Information Services as shown in the picture above.</p>

<h3>Step 21.</h3>

![21  open osticket files](https://github.com/user-attachments/assets/d2d1268d-8a4d-4d25-8175-ed9f7cd88c35)

<p>Now open the newly extracted folder osTicket-Installation-files</p>

<h3>Step 22.</h3>

![22  install php manager](https://github.com/user-attachments/assets/ac32a691-f24e-4691-b664-9bb73e90c101)

<p>Double-click and install PHP Manager</p>

<h3>Step 23.</h3>

![23  installation complete](https://github.com/user-attachments/assets/cd292646-8012-42e8-b665-7b373748d2c7)

<p>Close installation prompt</p>

<h3>Step 24.</h3>

![24  install rewrite](https://github.com/user-attachments/assets/c8bf4e73-94d1-4d9f-a2cf-ddf37c80b892)

<p>Double-click and install Rewrite</p>

<h3>Step 25.</h3>

![25  create php folder c drive](https://github.com/user-attachments/assets/a90f2667-9057-4213-94b0-62605305e757)

<p>Create a "PHP" folder within the C: drive</p>

<h3>Step 26.</h3>

![26  click extract php](https://github.com/user-attachments/assets/e813805b-d430-4d38-ba10-02ccf01a25a0)

<p>Right click and extract the php folder</p>

<h3>Step 27.</h3>

![27  exctract to c](https://github.com/user-attachments/assets/9ec2b722-8300-45c6-a15b-c3298e5f1421)

<p>Extract to the newly created PHP folder in the C: drive</p>

<h3>Step 28.</h3>

![28  install c++ visual](https://github.com/user-attachments/assets/be04d04a-c78d-41e1-b8dc-39dbf277309b)

<p>Install Microsoft Visual C++</p>

<h3>Step 29.</h3>

![29  install MySQL](https://github.com/user-attachments/assets/939e0645-0e0f-4382-9505-c5ad1341d575)

<p>Install MySQL Server</p>

<h3>Step 30.</h3>

![30  launch config](https://github.com/user-attachments/assets/8a2463f6-86aa-4367-86d2-b8fc590f71ef)

<p>Select launch check-box and click finish</p>

<h3>Step 31.</h3>

![31  standard config](https://github.com/user-attachments/assets/45f48fbc-9bcd-4058-861e-421b19f49611)

<p>Select standard config and click next</p>

<h3>Step 32.</h3>

![32  sql user   pass](https://github.com/user-attachments/assets/fdb42c93-84d9-4e5f-84c9-32e40889fc12)

<p>Enter a username and password, preferrably root and root for the sake of the lab. Then click next</p>

<h3>Step 33.</h3>

![33  execute](https://github.com/user-attachments/assets/014d186b-8cbc-447c-b49e-ded3c532276c)

<p>Click execute</p>

<h3>Step 34.</h3>

![34  finish](https://github.com/user-attachments/assets/6413f6e8-5ac4-4c16-8edd-91915ec560d0)

<p>Click finish</p>

<h3>Step 35.</h3>

![35  run iis as admin](https://github.com/user-attachments/assets/79c42c89-e5d2-4e3c-ae18-810e6495bca9)

<p>Search IIS Manager in the windows search bar and click run as administrator</p>

<h3>Step 36.</h3>

![36  go to php manager](https://github.com/user-attachments/assets/d3012807-7dd4-4e62-b964-4248ab3a77c6)

<p>Select PHP Manager</p>

<h3>Step 37.</h3>

![37  register php](https://github.com/user-attachments/assets/cd7c6077-fb37-4bdd-868c-41533b15e105)

<p>Click "Register new PHP version" and navigate to the executable shown in the image above, then click OK</p>

<h3>Step 38.</h3>

![38  stop   start iis](https://github.com/user-attachments/assets/58155743-7fc0-4bdd-a7b3-e0f65d33039b)

<p>Right click osticket-vm and select stop. Then click it again and select start.</p>

<h3>Step 39.</h3>

![39  extract osticket](https://github.com/user-attachments/assets/bc5024bb-f106-4441-a2a2-0a00c6dcac0d)

<p>Go back to the osTicket-Installation-Files and extract osTicket</p>

<h3>Step 40.</h3>

![40  click extract](https://github.com/user-attachments/assets/cd301223-5ae3-40b1-852d-b8a5d82e61b6)

<p>Click extract</p>

<h3>Step 41.</h3>

![41  move upload folder](https://github.com/user-attachments/assets/f8d48856-ea32-4912-9ba5-44927284086a)

<p>Go inside the newly extracted folder and drag the "upload" folder to the wwwroot folder shown like in the image above</p>

<h3>Step 42.</h3>

![42  rename to osTicket](https://github.com/user-attachments/assets/7f454d2d-0f2f-4795-9364-c050160f3b7d)

<p>Rename the upload folder to "osTicket"</p>

<h3>Step 43.</h3>

![43  stop   start iis](https://github.com/user-attachments/assets/c85b98b8-b840-429b-9ae7-1a856cd14df9)

<p>Go back to IIS Manager and repeat the stop and start method</p>

<h3>Step 44.</h3>

![44  browse 80](https://github.com/user-attachments/assets/e9957a64-34d7-4315-9597-1fa62968ea92)

<p>Go to osticket-vm dropdown, Sites, Default Web Site, osTicket. Click osTicket then click Browse *:80 (http)</p>

<h3>Step 44.</h3>

![45  results](https://github.com/user-attachments/assets/3c69fb7c-9dfa-4c21-9a1f-cd9a5a0db059)

<p>The osTicket installer web page should now successfully open</p>

<h3>Step 46.</h3>

![46  go to PHP manager](https://github.com/user-attachments/assets/65bb23a2-5a5f-46f2-9300-9e2b98d6959b)

<p>Go back to IIS and select PHP Manager</p>

<h3>Step 47.</h3>

![47  go to enable extensions](https://github.com/user-attachments/assets/ad696c7f-3d86-4997-82bd-a5dfc7ff9d64)

<p>Click "Enable or disable an extension"</p>

<h3>Step 48.</h3>

![48  enable these extensions](https://github.com/user-attachments/assets/172ac0d1-064a-4837-bfa5-e9c568401797)

<p>Enable all of the extensions highlighted in the image above</p>

<h3>Step 49.</h3>

![49  results](https://github.com/user-attachments/assets/84464302-915d-4234-bea5-3b7fbd1723f7)

<p>The extensions should now be enabled when refreshing the osTicket installer web page</p>

<h3>Step 50.</h3>

![50  rename](https://github.com/user-attachments/assets/52a73570-4b83-4de0-9357-3808190b0e2c)

<p>Navigate to the file address highlighted in the image above and rename "ost-sampleconfig.php" to "ost-config.php"</p>

<h3>Step 51.</h3>

![51  go to properties](https://github.com/user-attachments/assets/0bfc0e16-5f59-4f87-a783-28172d3b3970)

<p>Right click the file and go to properties</p>

<h3>Step 52.</h3>

![52  go to security](https://github.com/user-attachments/assets/b204ba14-eebc-46e2-9a39-95c3ea4f2a79)

<p>Go to security then click advanced</p>

<h3>Step 53.</h3>

![53  remove permissions](https://github.com/user-attachments/assets/45e97433-0671-4447-9a2c-43d0c1f5ca9a)

<p>Click disable inheritance then select "Remove all inherited permissions from this object"</p>

<h3>Step 54.</h3>

![54  add new permission](https://github.com/user-attachments/assets/a2c7171c-dcae-4c0b-94f6-6a5f9957a302)

<p>Click "add" to add a new permission</p>

<h3>Step 55.</h3>

![55  everyone](https://github.com/user-attachments/assets/4724a837-eccf-4fe1-ade8-a0100efa2a38)

<p>Click "Select a principal". Then type "everyone", click check names then click OK</p>

<h3>Step 56.</h3>

![56  full control](https://github.com/user-attachments/assets/34eaaef8-8af1-4003-8b99-0ed0dcf975c5)

<p>Select "Full control" then click OK</p>

<h3>Step 57.</h3>

![57  apply](https://github.com/user-attachments/assets/9eefade5-ef2a-4fee-9de3-7dea65c32994)

<p>Click "apply" then click OK</p>

<h3>Step 58.</h3>

![58  continue osticket setup](https://github.com/user-attachments/assets/c9d62a5b-ffdb-4451-bc03-5394c19060cc)

<p>Go to the osTicket web page installer and click Continue</p>

<h3>Step 59.</h3>

![59  admin credentials](https://github.com/user-attachments/assets/4470be56-5c3a-4d4d-844e-be77caf89e06)

<p>Fill out the following credentials and create a admin username and password like the image shown above.</p>

<h3>Step 60.</h3>

![60  install HeidiSQL](https://github.com/user-attachments/assets/e5485459-ff71-4757-a2b0-0bca5dae4fb9)

<p>Install HeidiSQL</p>

<h3>Step 61.</h3>

![61  click install](https://github.com/user-attachments/assets/e57c53a8-8872-4650-bfd1-1b42b4876dea)

<p>Click install</p>

<h3>Step 62.</h3>

![62  finish](https://github.com/user-attachments/assets/724ebbcf-8845-40de-b085-625aebd8cf15)

<p>Select launch HeidiSQL and click finish</p>

<h3>Step 63.</h3>

![63  new connection](https://github.com/user-attachments/assets/e8da80b3-43de-48f0-b9bb-f547035cac2f)

<p>Enter the username and password created for MySQL server. Example: root/root. Then click open</p>

<h3>Step 64.</h3>

![64  create new database](https://github.com/user-attachments/assets/fe8635fe-e08e-4b88-b9d2-7ab883f0ba2f)

<p>Right click Unamed, then go to Create new, Database</p>

<h3>Step 65.</h3>

![65  create](https://github.com/user-attachments/assets/c9591d29-121b-43c1-87ff-9d793ba1f8a3)

<p>Name the database "osTicket" then click OK</p>

<h3>Step 66.</h3>

![66  enter mysql credentials   install](https://github.com/user-attachments/assets/2f0cfc8a-bba5-4f81-bb31-b25cc7ceea3e)

<p>Enter the MySQL credentials like shown in the image above on the osTicket web page installer. Then click install now</p>

<h3>Step 67.</h3>

![67  success osticket install](https://github.com/user-attachments/assets/2ea6003c-5b5b-4044-ad5a-7ed4546021a1)

<p>Congratulations! You have now successfully installed osTicket on the designated machine.</p>
<a href="http://localhost/osTicket/scp/login.php">Help Desk Login Page</a>
<br>
<a href="http://localhost/osTicket/">End User osTicket URL</a>




























