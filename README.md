<h1 align="center">Home Lab</h1>
<h3 align="center">A home lab environment I created to explore diverse projects.</h3>
<br>

<p align="center">
  <img src="assets/ubuntu-bg.png" width="50%">
</p>

<p>&nbsp;</p>

<h2 align = "center">Home Lab Information</h2> 
<h3 align="left">Home Lab Configuration:</h3>
<ul>
    <li><p><span style="font-weight: bold;">Server:</span> HP EliteDesk 705 G4</p></li>
    <li><p><span style="font-weight: bold;">Specs:</span> AMD Ryzen 5 PRO 2400G • 8GB DDR4 • 1x 256GB SSD • 1x 75GB HDD </p></li>
    <li><p><span style="font-weight: bold;">Operating System:</span> Ubuntu LTS 22.04</p></li>
    <li><p><span style="font-weight: bold;">Server Roles:</span> Docker Host • Python Script Host • Backup Server • Network-Attached Storage (NAS) • Home Assistant Host</p></li>
</ul>

<p>&nbsp;</p>

<h2 align = "center">Docker</h2> 
<h3 align="left">Docker Information:</h3>
<ul>
    <li><p><span style="font-weight: bold;">Docker Containers:</span> Home Assistant • yt-dlp Web Server</p></li>
    <li><p><span style="font-weight: bold;">Home Assistant Role:</span> Control smart devices • Monitor home lab system information</p></li>
    <li><p><span style="font-weight: bold;">yt-dlp Web Server Role:</span> Download Youtube videos on any local device by accessing yt-dlp web server.</p></li>
    <li><p><span style="font-weight: bold;">Implementations:</span> Docker containers are scheduled to run on system startup to start Home Assistant and yt-dlp Web Server services.</p></li>
</ul>

<p>&nbsp;</p>

<h2 align = "center">Python Scripts</h2> 
<h3 align="left">Python Scripts Information:</h3>
<ul>
    <li><p><span style="font-weight: bold;">Python Scripts:</span> yt-dlp Youtube Video Auto-Downloader • Social Media Web Scraper</p></li>
    <li><p><span style="font-weight: bold;">yt-dlp Youtube Video Auto-Downloader Info:</span> A Python script designed to fetch the most recent videos from multiple YouTube channels and downloads them.</p></li>
    <li><p><span style="font-weight: bold;">Social Media Web Scraper:</span> A Python script using Selenium to download social media content with Requests then stores them in a database with unique IDs using Python's sqlite3.</p></li>
    <li><p><span style="font-weight: bold;">Implementations:</span> The Python scripts are scheduled to run at certain times with CRON jobs.</p></li>
</ul>

<p>&nbsp;</p>

<h2 align = "center">Backup Server</h2>
<h3 align="left">Backup Server Information:</h3>
<ul>
    <li><p><span style="font-weight: bold;">Backup Server:</span> The backup server serves as an additional storage solution for files, providing redundancy and complementing my use of Google Drive. </p></li>
    <li><p><span style="font-weight: bold;">Implementations:</span> The backup server utilizes storage from my NAS, facilitating file backups either over my home network or via data cables to a secondary drive.</p></li>
</ul>

<p>&nbsp;</p>

<h2 align = "center">NAS</h2> 
<h3 align="left">NAS Information:</h3>
<ul>
    <li><p><span style="font-weight: bold;">NAS:</span> The Network-Attached Storage (NAS) device functions as a centralized location for storing and accessing data over my local network, providing shared storage resources to multiple users and devices.</p></li>
    <li><p><span style="font-weight: bold;">Implementations:</span> I created a network drive by auto-mounting the secondary drive then creating an authorized Samba user in Ubuntu with access to the drive when accessed from other devices in the network.</p></li>
</ul>