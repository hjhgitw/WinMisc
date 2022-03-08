
Damit man das System herunterladen und installieren kann, muss man sich allerdings mit einem Microsoft Online-Konto anmelden.


https://docs.microsoft.com/it-it/windows/wsl/install-manual#step-4---download-the-linux-kernel-update-package

Power Shell Reboot

https://github.com/PowerShell/PowerShell

Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux

or
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart

https://it-learner.de/so-installiert-man-linux-direkt-unter-windows-11/



wsl -l -o

wsl --instaall -d "Ubuntu 20.04 LTS"


https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi
