# Ubuntu-remote-storage-media-entertainment-server
<h3>My Ubuntu (24.04.4 LTS) home server where I can store and share files/pictures with Samba and watch movies/shows I own with Jellyfin from anywhere in the world using Tailscale.</h3>

<div align="center"> After headless Ubuntu server is installed, I reserve the IP address in my router's DHCP settings so that it remains static.</div>

 <p align="center">
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/1c96b082cbd909a656e0515c4db41876f51ac6a2/Reserved%20IP%20address%20in%20AT%26T%20router%20DHCP%20settings.png" alt="Sample Image"/>
  </p>

<div align="center"> I then SSH into my server via my windows laptop.</div>

 <p align="center">
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/1c96b082cbd909a656e0515c4db41876f51ac6a2/SSH'd%20into%20linux%20server.png" alt="Sample Image"/>
  </p>
  
 <p align="center">
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/1c96b082cbd909a656e0515c4db41876f51ac6a2/Lin%20Serv%20Login%20Succ.png" alt="Sample Image"/>
  </p>

  <div align="center"> Install Samba, create and assign directory for files, and name it something easy to remember like "myfiles".</div>

 <p align="center">
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/eaed17513f30934b3cd701f09b45acf77a0856e0/Samba%20Install.png" alt="Sample Image" width="50%" height="50%">
  </p>

 <p align="center">
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/eaed17513f30934b3cd701f09b45acf77a0856e0/Samba%20Installed%20with%20directory%20config.png" alt="Sample Image" width="50%" height="50%">
  </p>

<div align="center"> Map network drive on windows computer to Linux Server for Network Attached Storage (NAS).</div>

<p align="center">
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/1c96b082cbd909a656e0515c4db41876f51ac6a2/Net%20Drive%20map%20to%20serv.png" alt="Sample Image" width="30%" height="30%">
  </p>

<div align="center"> Install Jellyfin .</div>

<p align="center">
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/a5f39abf85574507dbad9ed40c450a4f3d1bd0ff/Jellyfin%20Installing.png" alt="Sample Image" width="70%" height="70%">
  </p>

  <p align="center">
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/1c96b082cbd909a656e0515c4db41876f51ac6a2/JF%20installed.png" alt="Sample Image" >
  </p>

<div align="center"> Upload movies and shows in MP4 format to the mapped network drive from any of my devices (windows, mac, etc), configure & map my jellyfin media access directory to "myfiles" and create user account(s). .</div>


 <p align="center">
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/3ab67961ee5eb134dfa3b6ea298969bf5db1bed9/Jellyfin%20home%20UI.png" alt="Sample Image" >
  </p>

  <div align="center"> Jellyfin only allows devies on the local network to access the server, meaning I'd have to be at home to watch my movies which defeats the purpose of this being a fully fledged remote server. So I configure Tailscale to recognize my IT server as the main host and Tailscale creates a secure tunnel for me to watch my media from anywhere in the world via VPN   .</div>


 <p align="center">
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/a0fd2aa4187a1fd0cdcb08f09c98b7c9c87169ef/Jellyfin%20Home%20UI%20with%20Tailscale%20connected.png" alt="Sample Image" >
  </p>
