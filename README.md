# Ubuntu-remote-storage-media-entertainment-server
<h3>My Ubuntu (24.04.4 LTS) home server where I can store and share files/pictures with Samba and watch movies/shows with Jellyfin from anywhere in the world using Tailscale.</h3>

<div align="center"> After headless Ubuntu server is installed, I reserve the IP address in my router's DHCP settings so that it remains static.</div>

 <p align="center">
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/4afe3d57fd40c085006832cc4e312b1add7d8b24/Reserved%20IP%20address%20in%20AT%26T%20router%20DHCP%20set.png" alt="Sample Image"/>
  </p>

<div align="center"> I then SSH into my server via my windows laptop.</div>

 <p align="center">
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/4afe3d57fd40c085006832cc4e312b1add7d8b24/SSH%20into%20Linux%20server.png" alt="Sample Image"/>
  </p>
 <p align="center">
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/4afe3d57fd40c085006832cc4e312b1add7d8b24/Linux%20Server%20login%20success.png" alt="Sample Image"/>
  </p>

  <div align="center"> Install Samba, create and assign directory for files, and name it something easy to remember like "myfiles".</div>

 <p align="center">
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/eaed17513f30934b3cd701f09b45acf77a0856e0/Samba%20Install.png" alt="Sample Image" width="30%" height="30%">
  </p>

 <p align="center">
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/eaed17513f30934b3cd701f09b45acf77a0856e0/Samba%20Installed%20with%20directory%20config.png" alt="Sample Image" width="30%" height="30%">
  </p>

<div align="center"> Map network drive to Linux Server for Network Attached Storage (NAS).</div>

<p align="center">
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/e0e06599affa9e12e669122b21f45f0d58e62695/Network%20Drive%20mapped%20to%20server.png" alt="Sample Image" width="30%" height="30%">
  </p>
