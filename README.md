# docker-core-steamcmd
This project is to build a Docker Image for steamcmd to run on Windows Server 2019 core.

This dockerfile will build a Windows Server 2019 core Image, and download and install steamcmd.exe to c:\steamcmd\

Download and extract steamcmd.exe to the DockerFile location. (TODO: Automate this in the DockerFile)
https://steamcdn-a.akamaihd.net/client/installer/steamcmd.zip

Other Projects based off this Image:
https://github.com/madmunki/docker-core-7daystodie

This project is a port of zobees/docker-steamcmd to run on Windows Server 2019 Nano, and Docker for Windows.
https://github.com/zobees/docker-steamcmd
