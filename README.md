<p align="center">
<img src="https://i.imgur.com/d6oiorN.png"/>
</p>

<h1></h1>
This tutorial explains how to create a virtual machine in Azure with the Windows Operating System.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- An account with Microsoft Azure

<h2>Instructions</h2>

<p>
<img src="https://i.imgur.com/m0so2rd.jpg" height="80%" width="80%" />
</p>
<p>
When you log in to your Azure account, the first item to open will be the resource group link. If you cannot find it then you can search in the search bar within Azure and type "Resource Groups". The next step is to click on "Create New Resource Group" which will pop up the previous image. You can decided a name for the group, in my example I used "Test1". I used a region in the United States where I live but you can choose any region, make sure to remember which region you chose.
</p>
<br />

<p>
<img src="https://i.imgur.com/M8NHehQ.jpg" height="50%" width="50%" />
</p>
<p>
You can skip to the "Review and Create" tab, which should give you a green validation passed prompt. Afterwards you can click on "Create" to finish creating your resource group.
</p>
<br />

<p>
<img src="https://i.imgur.com/3UbAI8N.png" height="80%" width="80%" />
</p>
<p>
After creating the resource group, click on the search bar to find Virtual Machines. In my screen I have it under recent since I have opened it before however if you are new then you have to type it in the search bar to find it.
</p>
<br />

<p>
<img src="https://i.imgur.com/pkWmNLD.png" height="80%" width="80%" />
</p>
<p>
<img src="https://i.imgur.com/p1NzcVN.png" height="80%" width="80%" />
<p>
Once you open up the virtual machine screen as shown above, click on create "Azure Virtual Machine".
</p>
<br />

<p>
<img src="https://i.imgur.com/JHmkzm5.png" height="80%" width="80%" />
</p>
<p>
In this step you can select the resource group, in my case I created the test1 earlier. You can choose the one you created.
</p>
<br />

<p>
<img src="https://i.imgur.com/W33JUIn.png" height="80%" width="80%" />
</p>
<p>
In this section you have to choose a name for the Virtual Machine. For my example I chose "Labuser".
</p>
<br />

<p>
<img src="https://i.imgur.com/52btKiV.png" height="80%" width="80%" />
</p>
<p>
Try to match the region with the one you chose earlier, for my example it was US East. Leave the Availability option and Security type as is, no changes required.
</p>
<br />

<p>
<img src="https://i.imgur.com/0DPzmdE.png" height="80%" width="80%" />
</p>
<p>
In the Image section, search for Windows 10 Pro. This section is very important since it is where you can decide what Operating System to install.
</p>
<br />

<p>
<img src="https://i.imgur.com/Ch4D1kY.png" height="80%" width="80%" />
</p>
<p>
In this section for size, it is recommended to get one similiar to the one I chose in the image above. The price beside it is the estimated cost if you leave the system running the entire month. It is best to delete the virtual machine and all resources after you are done for the day. Doing this method my usual expenses for the month is around $20-$30 depending on how long I work on my projects. This part is essential since if you are like myself, you do not want to be surprised with a huge bill at the end of the month.
</p>
<br />

<p>
<img src="https://i.imgur.com/aKGqK9g.png" height="80%" width="80%" />
</p>
<p>
Create a username, to make it easier I made it the same as my VM name. Follow the prompt and make a suitable password of your choosing.
</p>
<br />

<p>
<img src="https://i.imgur.com/fun1HSh.png" height="80%" width="80%" />
</p>
<p>
In this section you can go ahead and ignore both of the sections that say ports. Check the box that says I have eligible license. Afterwards click on review and create.
</p>
<br />

<p>
<img src="https://i.imgur.com/FSFe5U0.png" height="80%" width="80%" />
</p>
<p>
After clicking on review and create on the previous section it will take you to the networking tab. Here you will not change anything but click on review and create again.
</p>
<br />

<p>
<img src="https://i.imgur.com/ihpSNcX.png" height="80%" width="80%" />
</p>
<p>
This is the Review and Create tab, on here it will give you an estimate cost for the monthly use the virtual machine. Once again this only the cost if you leave the machine and all your resources running nonstop for the entire month. After reading this section click on the create button.
</p>
<br />

<p>
<img src="https://i.imgur.com/JSDD0Ox.png" height="80%" width="80%" />
</p>
<p>
This is the image you will see when your virtual machine is being created. Depending on the size of the machine it may take several minutes.
</p>
<br />

<p>
<img src="https://i.imgur.com/vwpzHka.png" height="80%" width="80%" />
</p>
<p>
Once completed this is the image you will see on your screen.
</p>
<br />

<p>
<img src="https://i.imgur.com/A3th5lN.png" height="80%" width="80%" />
</p>
<p>
Look up virtual machines in the search bar. Once on the virtual machine screen, click on the created vm. For my example it is Labuser.
</p>
<br />

<p>
<img src="https://i.imgur.com/KuQLoqm.png" height="80%" width="80%" />
</p>
<p>
When you open up the virtual machine, copy the public IP address. This can be done by hovering your mouse over it and clicking the copy icon that pops up.
</p>
<br />

<p>
<img src="https://i.imgur.com/dC8jQSj.png" height="80%" width="80%" />
</p>
<p>
On your personal computer open "remote desktop connection", in the empty space where it says computer paste the copied public address of the virtual machine you created. Press connect when ready.
</p>
<br />

<p>
<img src="https://i.imgur.com/fzch5Sw.png" height="80%" width="80%" />
</p>
<p>
After clicking connect on the previous screen it will show you the enter your credentials page. I block out my personal info but you can press more choices to fill out you information. For my vm its username Labuser and my password that I created. Press Ok when ready.
</p>
<br />

<p>
<img src="https://i.imgur.com/HXSPzn5.png" height="80%" width="80%" />
</p>
<p>
It will give you this warning message but go ahead and click Yes to continue.
</p>
<br />

<p>
<img src="https://i.imgur.com/FWd0IWO.png" height="80%" width="80%" />
</p>
<p>
Once you connect to the virtual machine, it will give you this page. Click on accept will allow you to continue on. Remember this settings don't matter since at the end of the day this vm will be deleted.
</p>
<br />

<p>
<img src="https://i.imgur.com/sYIfHp8.png" height="80%" width="80%" />
</p>
<p>
Congratulations on creating your first Windows Operating virtual machine. Go ahead and play around with it. Once you are ready to exit go ahead and turn off the virtual machine just like a regular computer. Click on the right bottom corner and choose shutdown. Another option is to click on the X button on the top middle of your screen. That will exit the Virtual Machine without shutting it down.
</p>
<br />

<p>
<img src="https://i.imgur.com/mLzmU5k.png" height="80%" width="80%" />
</p>
<p>
To delete the virtual machine open up the VM page on Azure. Click on the delete button as shown above.
</p>
<br />

<p>
<img src="https://i.imgur.com/ABVBy2b.png" height="80%" width="80%" />
</p>
<p>
Check the I understand box, afterwards click the delete button to finish erasing the virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/OtinwKt.png" height="80%" width="80%" />
</p>
<p>
<img src="https://i.imgur.com/GPIpt40.png" height="80%" width="80%" />
<p>
<p>
Next up to is to delete all the resource groups. Make sure to delete both NetworkWatcher and the main resource group that was created earlier. For my example it was Test1. Once deleted make sure to check the virtual machine section once more to be sure that everything was deleted. Now your Azure account is clean and ready for the next use.
</p>
<br />


