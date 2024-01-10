# Simple-Home-Network
Here I will be going to Show you how to build a virtual home network.



<h1>Packet Tracer Simple Network</h1>





<h2>Description</h2>
<b>
You will be able to build a simple home virtual network using Cisco Packet Tracer. Start by going to this link and creating an acccount. https://skillsforall.com/course/getting-started-cisco-packet-tracer?utm_source=netacad.com&utm_medium=referral&utm_campaign=packet-tracer&courseLang=en-US&userlogin=0
<br />
<br />
Program walk through
<br />
<br />




<p align="center">
<img src="https://imgur.com/mTn9jVl.jpeg" height="85%" width="85%"
</p>


- <b>After downloading Packet tracer, you can follow along with the course or we can build our own network as shown here. Start with clicking on end devices and grab a pc, labtop, smart phone, printer, and a server. Now we need to click on Network Devices, then wireless devices. We'll use the WRT300N Router. Lastly click on the cloud icon, then grab the PT Cloud.</b> 

<img src="https://imgur.com/jWX5PKM.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>

<h2>Connecting Everything Together</h2>

<img src="https://imgur.com/GSpfo15.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>

- <b>Let's start with the laptop, double click on the the laptop and click on the power button which is next to the power cord. Now Click on the removable ethernet part and return that to the list of computer parts to the left and replace that with the WPC300N. Then cut the laptop back on and it should auto connect. Close that window and go back to the packet tracer page.<b>

<h2></h2>

<img src="https://imgur.com/3lVtoJr.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>

- <b>Now, we'll do the same with the printer. except the part to install is called WMP300N. Same process turn the printer off swap out the old and in with the new part (WMP300N). Cut the priter back on and close out the window, back to the packet tracer page.</b> 

<h2></h2>

<p align="center">
<img src="https://imgur.com/2HoIY6D.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2></h2>
- <b>Last end device to connect for the home network is the pc. Click the Lightning icon, and we'll use the copper straight through. Click the copper straight through from the pc to the router to have all home devices connected.</b>
<p align="center">
<img src="https://imgur.com/tW88XaH.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>


<h2>Connecting to the Internet</h2>

<p align="center">
<img src="https://imgur.com/KBtuXn0.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

- <b>Click back on the lightning icon, select the same copper straight through wire to the router selecting the internet port. Next connect that cord to the cable modem box and select port 1.

<h2>Back to Metasploitable 2</h2>

<img src="https://imgur.com/nfopoen.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>  

- <b>We need to go back to Metasploitable 2 to grab the IP address using the command 'ifconfig.<b>

<h2>Back to Nessus</h2>

<img src="https://imgur.com/3OGiVHc.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>

- <b>Input your info here.<b>
- <b>We will do a 'credential scan,' so you'll need your login and password info for Metasploitable to make this work. Now, click on 'Credentials.<b>

<h2></h2>

<img src="https://imgur.com/T5z8VoM.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>

- <b>Here, you can choose based on your operating system, whether it's Linux or Windows. I'll show an example of both.<b>

<h2>Linux</h2>
<p align="center">
<img src="https://imgur.com/cdT73tY.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>

- <b>If you're using Linux, click on 'SSH,' then add your username and password for the machine you are scanning. Then, click save to keep things simple.<b>

<h2>windows</h2>


<img src="https://imgur.com/UXkVcAe.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>

- <b>"If you're using Windows, click on 'Windows,' and type in your username and password for the machine you are scanning. Then, click save.<b>

<h2>Scannning</h2>

<p align="center">
<img src="https://imgur.com/J6JX3Gf.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>

- <b>Now, we see our scanner is ready to scan. Let's click the play button to start scanning.<b>

<h2></h2>

<img src="https://imgur.com/fXhDg83.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>

- <b>This is what you'll see when your scanner is running the scan.<b>

<h2></h2>

<p align="center">
<img src="https://imgur.com/WtIho5T.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>

- <b>Once your scanner is finished, look over by the 'Last Scanned' column; there will be a check next to the date and time. Now, click on your scanner's name to see the results.<b>

<h2>Results</h2>

<img src="https://imgur.com/iRb9Vdu.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>

- <b>"Now, these are the vulnerability results. Many of these results are just informational, but there is one with medium severity according to the CVSS score. You can find this information on the right side of the screen. So, click on the blue bar across the screen under 'Vulnerabilities.<b>

<h2>Vulnerabilities</h2>

<p align="center">
<img src="https://imgur.com/Xd2Z6h0.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>

- <b>Here is a list of the vulnerabilities found. You can take a look at each one. Click on a vulnerability to see what kind it is and read on how to remediate it. We're going to focus on the mixed severity; SSL (Multiple Issues). Click on that.<b>

<h2></h2>

<img src="https://imgur.com/44QkyZX.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>

- <b>Now, notice the medium severity SSL certificate cannot be trusted. This has a CVSS severity score of 6.5. Click on this severity.

