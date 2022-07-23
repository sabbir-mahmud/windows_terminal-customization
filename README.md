# windows_terminal-customization
cmd 1: Set-ExecutionPolicy Unrestricted
cmd 2: Set-ExecutionPolicy Bypass -Scope Process -Force; Invoke-Expression ((New-Object System.Net.WebClient).DownloadString('https://ohmyposh.dev/install.ps1'))

cmd 3: PowerShellGet\Install-Module posh-git -Scope CurrentUser -Force
cmd 4: Install-Module -Name Terminal-Icons -Repository PSGallery

# install Fira Code NF font

# settings.json
"defaults": 
        {
            "font": 
            {
                "face": "FiraCode NF",
                "size": 10
            }
        },
