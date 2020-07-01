## Set up SSH Authentication between your computer and Raspberry Pi

![ssh login](resources/ssh-login.jpg)

Setting up a public/private key pair for [SSH](https://en.wikipedia.org/wiki/Secure_Shell) authentication is a secure and fast way to authenticate from your computer to the Raspberry Pi. This is recommended for this hands-on lab.

### Set up SSH for Windows Users

The SSH utility guides you through the process of setting up a secure SSH channel for Visual Studio Code and the Raspberry Pi.

1. **Download** the [Raspberry Pi SSH Authentication Utility](https://github.com/gloveboxes/Setting-up-Raspberry-Pi-SSH-Authentication/archive/master.zip) from GitHub
2. **Open** Windows File Explorer and navigate to the your *Download* directory. 
3. **Double click** on the **Setting-up-Raspberry-Pi-SSH-Authentication-master.zip* file.
4. **Navigate** to the *Setting-up-Raspberry-Pi-SSH-Authentication-master* directory
5. **Drag and drop** the **windows-ssh-setup.cmd** to your Desktop
6. **Start** the Raspberry Pi SSH Authentication Utility

    From your Desktop, double click on the **windows-setup-ssh.cmd** file. You will be prompted for:

    - The Raspberry Pi Network IP Address,
    - The Raspberry Pi login name and password. The Raspberry Pi **default** login name is **pi**, and the default password is **raspberry**.

### Set up SSH for Linux and macOS Users

The SSH utility guides you through the process of setting up a secure SSH channel for Visual Studio Code and the Raspberry Pi.

You will be prompted for:

- The Raspberry Pi Network IP Address,
- The Raspberry Pi login name and password

1. Open a Terminal window
2. Copy and paste the following command, and press **ENTER**

    ```bash
    curl https://raw.githubusercontent.com/gloveboxes/Setting-up-Raspberry-Pi-SSH-Authentication/master/ssh-setup.sh | bash
    ```
