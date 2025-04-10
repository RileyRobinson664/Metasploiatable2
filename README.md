<h1>Metasploitable 2</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
This project shows how to set up the Metasploitable 2 box for a simulated engment as well was providing a walkthrough for the box.
<br />


<h2>Resources</h2>

- <b>[Kali Linux](https://www.kali.org/get-kali/#kali-virtual-machines)</b> 
- <b>[Metasploatable 2](https://sourceforge.net/projects/metasploitable/)</b>

<h2>Configuration:</h2>

<p align="center">
After importing the files into your hypervisor of choice, remove the Network Adapter 2 from the Metasploatable 2 box. Having this box on a public facing network could present a security issue.: <br/>
<img src="https://imgur.com/mjnUW0K.png" height="80%" width="80%" alt="Removing the network adapter"/>
<br />
<br />
Now we switch the remaning network adapter to a LAN segment where the Metasploatable 2 box will be isolated from the internet:  <br/>
<img src="https://imgur.com/NZzaZZQ.png" height="80%" width="80%" alt="Putting the box on a LAN"/>
<img src="https://imgur.com/iPJs95e.png" height="80%" width="80%" alt="Putting the box on a LAN"/>
<br />
<br />
Now we can launch the box: <br/>
<img src="https://imgur.com/9L3zySf.png" height="80%" width="80%" alt="Launching Metasploitable 2 box."/>
<br />
<br />
We now want to add out Kali instance to the LAN so that our boxes can talk to eachother:  <br/>
<img src="https://imgur.com/ZOyfmQ5.png" height="80%" width="80%" alt="Add a network adapter"/> 
<img src="https://imgur.com/n4vcazI.png" height="80%" width="80%" alt="Add a network adapter"/>
<img src="https://imgur.com/upcRWdl.png" height="80%" width="80%" alt="Add a network adapter"/>
<br />
<br />
Now that both boxes are on the same network, we can boot up out Kali box as well:  <br/>
</p>

<h2>Installing OpenVAS:</h2>

<p align="center">
Now we can begin to install Open VAS on out Kali Linux box. First we need to update all of our packages: <br/>
<img src="https://imgur.com/pgrkdzx.png" height="80%" width="80%" alt="Updating our packages"/>
<br />
<br />
Now we can install OpenVAS like this:  <br/>
<img src="https://imgur.com/EZ04hoD.png" height="80%" width="80%" alt="Installing Open VAS"/>
<br />
<br />
</p>

<h2>Engagment:</h2>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
