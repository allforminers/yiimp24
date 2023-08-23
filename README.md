cd /home/crypto-data/yiimp/site/stratum

screen bash run.sh sha

nicehash = 750000

PANELADMIN

/home/crypto-data/yiimp/site/web/yaamp/modules/site SiteController.php

```
curl https://raw.githubusercontent.com/afiniel/yiimp_install_script/master/install.sh | bash

```
 

<h3>Finish! Remember to</h3>
<h4>A server reboot is REQUIRED after the installation is fully completed to finalize the installation process</h4>
<p>
  After rebooting the server, log back in to your user account you have created. When the rebooting process is complete, log in again with your user account and you have successfully installed YiiMP on your server.
</p>
<h4>On first reboot it may take up to 1-2 minutes before the cron screens auto-start. After waiting 1-2 minutes type:</h4>
<pre>
motd
</pre>
<p>
  To help make your server more secure, the install locations and directory structure of YiiMP have been changed as follows:
</p>
<table>
  <thead>
    <tr>
      <th>Directory</th>
      <th>Files</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><pre>/home/crypto-data/yiimp</pre></td>
      <td>General install location for YiiMP</td>
    </tr>
    <tr>
      <td><pre>/home/crypto-data/yiimp/starts</pre></td>
      <td>screens and stratum sh files - you do not need to run these</td>
    </tr>
    <tr>
      <td><pre>/home/crypto-data/yiimp/site</pre></td>
      <td>-</td>
    </tr>
    <tr>
      <td><pre>/home/crypto-data/yiimp/site/web</pre></td>
      <td>New location for YiiMP web files</td>
    </tr>
    <tr>
      <td><pre>/home/crypto-data/yiimp/site/backup</pre></td>
      <td>backup location for MySQL DB</td>
    </tr>
    <tr>
      <td><pre>/home/crypto-data/yiimp/site/configuration</pre></td>
      <td>New location of your serverconfig.php</td>
    </tr>
    <tr>
      <td><pre>/home/crypto-data/yiimp/site/crons</pre></td>
      <td>New location of the "main:blocks:loop2" sh files</td>
    </tr>
    <tr>
      <td><pre>/home/crypto-data/yiimp/site/log</pre></td>
      <td>New location for debug.log and your nginx server log</td>
    </tr>
    <tr>
      <td><pre>/home/crypto-data/yiimp/site/stratum</pre></td>
      <td>New location for your stratum files</td>
    </tr>

Permissions have been setup correctly allowing your main user write acess to the /home/crypto-data directories! Changing file or directory permissions after install will cause your YiiMP to not function correctly you have been warned!!

