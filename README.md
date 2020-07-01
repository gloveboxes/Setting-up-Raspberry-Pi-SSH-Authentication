## Set up SSH Authentication between your computer and Raspberry Pi

![ssh login](resources/ssh-login.jpg)

Setting up a public/private key pair for [SSH](https://en.wikipedia.org/wiki/Secure_Shell) authentication is a secure and fast way to authenticate from your computer to the Raspberry Pi and will be used by Visual Studio Code Remote SSH Development.

The Raspberry Pi SSH Authentication utility will prompt you for:

- The Raspberry Pi Network IP Address,
- The Raspberry Pi login name and password. The Raspberry Pi **default** login name is **pi**, and the default password is **raspberry**.

### Set up SSH for Windows Users

The SSH utility guides you through the process of setting up a secure SSH channel for Visual Studio Code and the Raspberry Pi.

1. Start Powershell
    From the Start Menu. Click Start, type PowerShell, and then click Windows PowerShell.
2. Download the Raspberry Pi SSH Authentication Utility. 

    Run the following PowerShell command.

    ```powershell
    Invoke-WebRequest -Uri "https://raw.githubusercontent.com/gloveboxes/Setting-up-Raspberry-Pi-SSH-Authentication/master/windows-ssh-setup.cmd" -OutFile "windows-ssh-setup.cmd"
    ```

3. Start the Raspberry Pi SSH Authentication Utility.

    Run the following PowerShell command.

    ```powershell
    .\windows-ssh-setup.cmd
    ```



### Set up SSH for Linux and macOS Users

The SSH utility guides you through the process of setting up a secure SSH channel for Visual Studio Code and the Raspberry Pi.

1. Open a Terminal window
2. Copy and paste the following command, and press **ENTER**

    ```bash
    curl https://raw.githubusercontent.com/gloveboxes/Setting-up-Raspberry-Pi-SSH-Authentication/master/ssh-setup.sh | bash
    ```
