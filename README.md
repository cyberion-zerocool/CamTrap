# CamTrap
Grab cam shots from target's phone front camera or PC webcam just sending a link.

# What is CamTrap?
<p>CamTrap is techniques to take cam shots of target's phone front camera or PC webcam. CamTrap Hosts a fake website on in built PHP server and uses ngrok & serveo to generate a link which we will forward to the target, which can be used on over internet. website asks for camera permission and if the target allows it, this tool grab camshots of target's device</p>

## Features
<p>In this tool I added two automatic webpage templates for engaged target on webpage to get more picture of cam</p>
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
  <li>Windows (WSL)</li>
</ul>

# Installing and requirements
<p>This tool require PHP for webserver, and wget for downloading dependencies. First run following command on your terminal</p>

```
apt-get -y install php wget unzip
```

## Installing (Kali Linux/Termux):

```
git clone https://github.com/cyberion-zerocool/CamTrap.git
cd CamTrap
bash camtrap.sh
```

## Clean logs & unnecessary files :

```
bash cleanup.sh
```
<p>The cam files and saved location will also be removed.</p>

## Change Log:

<p><b>Version: 2.0:</b> Added GPS Location Tracking</p>
<ul>
  <li>Added: GPS location capturing functionality</li>
  <li>Added: Google Maps integration for captured locations</li>
  <li>Added: Location accuracy reporting</li>
  <li>Added: Improved loading screen with location request</li>
</ul>

<p><b>Version: 1.9:</b> Enhanced architecture detection</p>
<ul>
  <li>Added: Improved architecture detection for all CPU types</li>
  <li>Added: Better support for Apple Silicon (M1/M2/M3) Macs</li>
  <li>Added: Automatic detection of ARM, ARM64, x86, and x86_64 architectures</li>
  <li>Fixed: Windows compatibility improvements</li>
  <li>Fixed: CloudFlare Tunnel download issues</li>
</ul>

<p><b>Version: 1.8:</b> Added CloudFlare Tunnel and removed Serveo</p>
<ul>
  <li>Added: CloudFlare Tunnel support for more reliable connections</li>
  <li>Removed: Serveo tunnel (deprecated)</li>
  <li>Fixed: Various code improvements and bug fixes</li>
</ul>

<p><b>Version: 1.7:</b> Fix and add support</p>
<ul>
  <li>fixed: termux failed to get home directory</li>
  <li>Add support for Apple sillicon (M1/M2/M3 ARM64)</li>
  <li>Add support for arm64 like Raspberry Pi</li>
</ul>
<p><b>Version: 1.6:</b> Fix ngrok direct link generate</p>
<p><b>Version: 1.5:</b> Add new online meeting template</p>
<p><b>Version: 1.4:</b> Ngrok authtoken update</p>
<p><b>Version: 1.3:</b> Fix ngrok direct link</p>
#### For More Video subcribe <a href="http://youtube.com/Cyberion-ZeroCool">CYBERION YouTube Channel</a>
<p>CamTrap is created to help in penetration testing and it's not responsible for any misuse or illegal purposes.</p>
<p><b>Special thanks to Mian Izaz Ali Shah</b> — for being the guiding light on my coding journey. Your support, mentorship, and passion for web development have truly inspired me to push my limits and keep learning. This project wouldn’t be the same without your help!</p>
#### For More Video subcribe <a href="http://youtube.com/@Cyberion-ZeroCool">CYBERION YouTube Channel</a>
<p>CamTrap is created to help in penetration testing and it's not responsible for any misuse or illegal purposes.</p>
