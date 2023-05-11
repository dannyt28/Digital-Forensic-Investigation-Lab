# Digital-Forensic-Investigation-Lab

<h2>Description</h2>
In this lab, I utilized various network forensic analysis techniques to identify the root cause of a network attack. The goal was to develop skills in forensic investigative techniques that can withstand legal scrutiny in any given situation. Moreover, the expectation was to demonstrate the ability to analyze and interpret network traffic, identify any malicious or anomalous activity, and provide recommendations for intrusion detection and prevention measures.
<br />


<h2>Scenario</h2>
An employee at Anarchy-R-Us, Inc. named Ann Dercover is suspected to be a secret agent for their competitor. Ann has access to the company’s secret recipe, and security staff are concerned about a possible leak. Recently, an unknown laptop briefly appeared on the company's wireless network and Ann's computer was found to have sent IMs to this laptop. The organization has obtained the network activity packets in the file evidence01.pcap.
<br/>
<h2>Environments Used </h2>

- <b>Windows 10 enterprise </b> 
- <b>Wireshark</b>
<h2>IMPORTANT NOTE!</h2>
For security reasons, IP addresses in screenshots were blurred out. 

<h2>Lab walk-through:</h2>

<h2>Screenshot 1:</h2>
<p align="center">
Step 1: <br/>
An IP filter was applied using Wireshark to isolate traffic from Ann's computer. The filter used was 'ip.addr==IP1 && tcp.flags.syn', where IP1 was the IP address associated with Ann's computer.
</p>
<img src="https://i.imgur.com/BpoKmnD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
- <b> This filter will display the TCP SYN packets that were transmitted from Ann's computer.</b>

<h2>Screenshot 2:<h/2>
<p align="center">
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Screenshot 3:<h/2>
<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  
<h2>Screenshot 4:<h/2>
<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 
<h2>Screenshot 5:<h/2>
<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
