<h1>Automation of Port Scanning Pentesting Project</h1>

<img src="https://imgur.com/DH5jorA.png" height="80%" width="80%" alt="diagram"/>

<h2>Description</h2>
In this project, I create an automation of a Python Script that performs port scanning to automate pentesting for any IP address and desired port to check if its open or closed. We code using Virtual Studio Code (any python environment can be used) and the socket library. Lets get right into this step by step guide!
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>JSON</b>

<h2>Environments Used </h2>

- <b>Virtual Studio Code</b>

<h2>Program walk-through:</h2>

<p align="center">
Here is the completed code, we import the socket library which is used to specify we are using IPv4 via the "AF_INET" method and "SOCK_STREAM" which specifies it being TCP and that there will be a TCP Handshake: <br/>
<img src="https://imgur.com/zaS28Ce.png" height="80%" width="80%" alt="set up"/>
<br />
We create a function which scans the port using the socket variable we created and it checks to see if the socket does not connect using "connect_ex" print that its closed. Else print that its open if it connects: <br/>
<img src="https://imgur.com/hjxyEFJ.png" height="80%" width="80%" alt="set up"/>
<br />
<br />
We will be scanning the ports of this site "www.hackthissite.org" as an example, to get the ip we ping the site in our command prompt: <br/>
<img src="https://imgur.com/65a6E8Q.png" height="80%" width="80%" alt="set up"/>
<br />
<br />
Now we run the code and follow the input instructions we made, we add the IP which we got from the cmd:  <br/>
<img src="https://imgur.com/qYRc4Om.png" height="80%" width="80%" alt="set up"/>
<br />
<br />
And  then we input the port we want to scan to see if its open or closed, in this case we will check port 21 and it appears to be open:  <br/>
<img src="https://imgur.com/n3l02vI.png" height="80%" width="80%" alt="set up"/>
<img src="https://imgur.com/J5OztNJ.png" height="80%" width="80%" alt="set up"/>
<br />


<br />
This Concludes This Automation Python Script Project!
NOTE: You can add onto this and make it more complex, or use these methonds to automate other tasks!  <br/>
<br />
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
