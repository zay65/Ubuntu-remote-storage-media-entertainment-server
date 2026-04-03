# Ubuntu-remote-storage-media-entertainment-server
<h3>My Ubuntu (24.04.4 LTS) home server where I can store and share files/pictures with Samba and watch movies/shows with Jellyfin from anywhere in the world using Tailscale.</h3>

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
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/eaed17513f30934b3cd701f09b45acf77a0856e0/Samba%20Install.png" alt="Sample Image" width="30%" height="30%">
  </p>

 <p align="center">
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/eaed17513f30934b3cd701f09b45acf77a0856e0/Samba%20Installed%20with%20directory%20config.png" alt="Sample Image" width="30%" height="30%">
  </p>

<div align="center"> Map network drive on windows computer to Linux Server for Network Attached Storage (NAS).</div>

<p align="center">
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/1c96b082cbd909a656e0515c4db41876f51ac6a2/Net%20Drive%20map%20to%20serv.png" alt="Sample Image" width="30%" height="30%">
  </p>

<div align="center"> Install Jellyfin .</div>

<p align="center">
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/a5f39abf85574507dbad9ed40c450a4f3d1bd0ff/Jellyfin%20Installing.png" alt="Sample Image" width="50%" height="50%">
  </p>

  <p align="center">
    <img src="https://github.com/zay65/Ubuntu-remote-storage-media-entertainment-server/blob/1c96b082cbd909a656e0515c4db41876f51ac6a2/JF%20installed.png" alt="Sample Image" >
  </p>
