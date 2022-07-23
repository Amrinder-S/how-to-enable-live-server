# How to view Live Changes to your webpages on local network

## Install and configure VSCode Live Server
- Press Ctrl + Shift + X inside VSCode
- Search Live Server in the search menu and install the extension
![installit](https://i.imgur.com/4jh0VDj.png)

- Go to the extension settings
![blabla](https://i.imgur.com/Lrte88Q.png)

- Scroll all the way down and enable this option.

![imsleepy](https://i.imgur.com/yyPD9Bo.png)

## Start the Live Server and host it locally

- click Go Live and note down the port number for later (if it is not 5500).

![sas](https://i.imgur.com/yy5I0AU.png)

![sas](https://i.imgur.com/ukvV8g1.png)

- Note the link that opens in the browser automatically.

![ok](https://i.imgur.com/KhiGMBZ.png)

- open command prompt as an administrator and type this command:
```cmd
netsh advfirewall firewall add rule name="VSCode Live Server" dir=in action=allow protocol=TCP localport=5500
```
- Replace the localport=5500 to localport=(YOUR LITERAL PORT NUMBER).
As in: If your port number was 57682 then you put localport=57682
- Press Enter

![1](https://i.imgur.com/geEcXTm.png)

## Accessing it locally

Enter the link you noted down before, put the same link on any device on same Wi-Fi/Hotspot etc
![ok](https://i.imgur.com/KhiGMBZ.png)
- Enjoy
