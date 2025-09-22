# PuTTY – SSH Connection  
**Reading time: 2 minutes**  
**Documentation – PuTTY**  

## Description  
PuTTY is a free and open-source terminal emulator that allows secure remote connections using the SSH (Secure Shell) protocol. It is widely used in Windows environments to securely access Linux servers and other devices.  

PuTTY was originally written for Microsoft Windows but has been ported to several other operating systems. Official ports are only available for certain Unix platforms, with ongoing development for classic Mac OS and Mac OS X. Unofficial versions have also been created for platforms such as Symbian OS and Windows Mobile. PuTTY was written and is primarily maintained by Simon Tatham.  

With PuTTY, users can:  
- Connect to servers via SSH with secure authentication.  
- Save sessions for future reuse.  
- Use different protocols (SSH, Telnet, Rlogin, Raw, Serial).  

This tool ensures efficiency and security in remote server management.  

## Features  
- **Secure SSH connection:** enables remote server access with encryption.  
- **Saved sessions:** allows storing connection parameters for reuse.  
- **Multi-protocol support:** SSH, Telnet, Rlogin, Raw, and Serial.  
- **Intuitive interface:** makes configuration and usage easier, even for beginners.  

## Benefits  
- **Security:** encrypted connections with support for password or SSH key authentication.  
- **Productivity:** saved sessions save time and reduce configuration errors.  
- **Flexibility:** supports multiple protocols and custom configurations.  

## Tutorial – How to Establish an SSH Connection  

### Prerequisites:  
- PuTTY installed on the computer.  
- Accessible SSH server (IP or hostname).  
- Valid user credentials.  

### Step by step:  
1. Open PuTTY.  
2. In the **Host Name (or IP address)** field, enter the server’s address.  
3. Ensure the **Port** is set to 22.  
4. Select **SSH** under *Connection type*.  
5. Click **Open** to start the session.  
6. Enter your username and password when prompted.  

**Expected result:** access to the remote terminal, ready to execute commands.  

### Important notes:  
- Use strong passwords or SSH keys for better security.  
- Avoid using the root account directly; prefer users with appropriate permissions.  
- Save sessions in **Saved Sessions** to make reconnections easier.  
- When connecting for the first time, PuTTY will ask you to accept the server’s key.  

## Reference – SSH Connection Parameters  

### Administrator/User requirements:  
- PuTTY installed.  
- Server IP or hostname.  
- Valid credentials.  

### Access path:  
Open **PuTTY** > **Session category** > Configure fields > Select **SSH**.  

### Input fields:  

| Item | Type | Description |  
|------|------|-------------|  
| Host Name (or IP address) | Text field | Address of the remote server (IP or DNS). |  
| Port | Numeric field | Connection port. Default: 22. |  
| Connection type | Radio button | Protocol type (SSH, Telnet, Rlogin, Raw, Serial). |  
| Saved Sessions | Text field | Stores configurations for reuse. |  

### Available actions:  
- **Open:** starts the connection.  
- **Save:** saves the current session.  
- **Load:** loads a previously saved session.  
- **Cancel:** closes the configuration window.  

### Additional information:  
- By default, PuTTY uses port 22 for SSH.  
- Saved sessions can be reused for future connections.  
- Authentication failures require re-entering credentials or ending the session.  

