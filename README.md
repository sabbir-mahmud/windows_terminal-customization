# windows_terminal-customization
cmd: Set-ExecutionPolicy Bypass -Scope Process -Force; Invoke-Expression ((New-Object System.Net.WebClient).DownloadString('https://ohmyposh.dev/install.ps1'))

cmd: Install-Module -Name Terminal-Icons -Repository PSGallery

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
