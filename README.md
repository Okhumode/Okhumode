# General First Time Steps On how To Run Airdrop Scripts On A VPS
## !Take Note after pasting each code into the VPS, press the ENTER button on your Keyboard To Run It!!! 
### 1. Open Your VPS
```sh
   sudo su
   ```
  ### 2. Upgrade and Update The VPS
  ```sh
  apt-get update && apt-get upgrade -y && apt-get dist-upgrade -y && reboot
  ```
If you get a red/pink screen while this code above is running, press the ENTER button on your keyboard. immediately the code is run completely, you would see a notification that your VPS has been disconnected, press the CANCEL button at the top right of that notification.
#### Now RE-OPEN your VPS
### 3. Install python 3
```sh
sudo apt-get install python3-pip -y
```
### 4. Install python 3
```sh
 sudo apt-get install python-is-python3
```
### 5. Upload All/some of your Scripts using termius SFTP protocol.
