# mini-rag

This is a minimal implementation of the RAG model for question answering.

## Requirements 

- python 3.8 or later

#### Install Python using Miniconda 

1. Windows InstallationDownload Installer:
 Visit the Anaconda Documentation and download the Miniconda3 Windows 64-bit .exe file.Run Installer: Double-click the downloaded .exe file to start the setup wizard.Navigate Prompts: Click Next, accept the license terms, and choose your installation folder (default is recommended).Advanced Options: Check the box for "Clear package cache upon completion" if you want to save space. Leave the default option checked to use Miniconda as your system's default Python.Finish: Click Install, then click Finish once complete.
 2. macOS InstallationDownload Installer: Choose either the .pkg Graphical Installer or the .sh Command Line Installer from the Anaconda page. Choose the file matching your chip type (Intel or Apple Silicon M1/M2/M3).Graphical Installation (.pkg):Double-click the downloaded .pkg file.Click Continue through the ReadMe and License sections.Click Install and enter your macOS user password to authorize.Terminal Installation (.sh):Open your Terminal app.Run the installer script by typing: bash Miniconda3-latest-MacOSX-x86_64.sh (replace with your exact filename).Review and approve the license agreement, then type yes to initialize Miniconda.
 3. Linux InstallationDownload Installer: Copy the download link for the Linux .sh installer from the website.Run via Terminal: Open your terminal and fetch the installer using wget or curl. For example:bashwget https://anaconda.com
يُرجى استخدام الرمز البرمجي بحذر.Execute Script: Run the script with the following command:bashbash Miniconda3-latest-Linux-x86_64.sh
يُرجى استخدام الرمز البرمجي بحذر.Follow Prompts: Press Enter to read the license agreement, type yes to accept, and press Enter again to accept the default install location.Initialize: When asked if you want to initialize Miniconda3 by running conda init, type yes.Verifying Your InstallationOnce the installation finishes, close your current terminal window and open a new one (or open the Anaconda Prompt from your Start Menu if you are on Windows).Run the following command to verify everything is working perfectly:bashconda list
يُرجى استخدام الرمز البرمجي بحذر.If the installation was successful, this command will print out a list of the core Python packages currently installed on your machine

