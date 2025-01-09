# Onefootball Auto Reff  

**[Onefootball AutoReff](https://ofc.onefootball.com/s2)** is a tool designed for automatic operations on Onefootball airdrop  

---

## Features  
- **Auto Sign**: Automatically signs transactions.  
- **Auto Login**: Facilitates quick and secure login.  
- **Auto Register**: Automatically Register accounts
- **Multi-Account Support**: Handle multiple accounts with ease.  
- **Proxy Support**: Supports Proxy  

![Screenshot](https://i.ibb.co.com/7VkQQ6M/Cuplikan-layar-2024-12-23-192359.png)  

---

## Installation

1. **Clone Repository:**
   ```bash
   git clone https://github.com/Idevxd/onefootball.git
   ```
   First Create Virtual Environment
   ```bash
   python3 -m venv onefootball
   ```
   Now Activate Virtual Environment
   ```bash
   source onefootball/bin/activate
   ```
   Now Go to Directory
   ```bash
   cd onefootball
   ```

2. **Instal Requirements:**


   ```bash
   pip install -r requirements.txt #or pip3 install -r requirements.txt
   ```
3. **Setup Proxy**

- manual_proxy.txt: You will find the file manual_proxy.txt in the project directory. Make sure manual_proxy.txt contains data that matches the format expected by the script. Here is an example of a file format::


  ```bash
    #ip:port #http or socks5 - change schemes in line 101
    http://ip:port
    socks4://ip:port
    socks5://ip:port
    http://ip:port@user:pass #idk its work or not, cuase i don't have authentic proxy
    socks4://ip:port@user:pass #idk its work or not, cuase i don't have authentic proxy
    socks5://ip:port@user:pass #idk its work or not, cuase i don't have authentic proxy#
  ```
