# CyberEye
Grab cam shots from target's phone front camera or PC webcam just sending a link.
![CyberEye](https://cweducation.in/img/cy.png)

# What is CyberEye?
<p>CyberEye is techniques to take cam shots of target's phone front camera or PC webcam. its Hosts a fake website on in built PHP server and uses serveo to generate a link which we will forward to the target, which can be used on over internet. website asks for camera permission and if the target allows it, this tool grab camshots of target's device</p>

<p>CyberEye is created to help in Social engineering & penetration testing  and it's not responsible for any misuse or illegal purposes.</p>
<p>CyberEye is inspired by https://github.com/thelinuxchoice/ Big thanks to @thelinuxchoice</p>


## Features
<p>In this tool I added 3 automatic webpage templates for engaged target on webpage to get more picture of cam</p>
<ul>
  <li>Festival Wishing</li>
  <li>Live YouTube TV</li>
   <li>Online Meeting [Beta]</li>
</ul>
<p>simply enter festival name or youtube's video ID</p>

## This Tool Tested On :
<ul>
  <li>Kali Linux</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Parrot Sec OS</li>
</ul>

# Installing and requirements
<p>This tool require PHP for webserver, SSH or serveo link. First run following command on your terminal</p>

```
apt-get -y install php openssh git wget
```

## Installing (Kali Linux/Termux):

```
git clone https://github.com/techchipnet/CyberEye
cd CyberEye
bash cybereye.sh
```
