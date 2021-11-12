# WSL In Another Drive
> Install wsl in another drive.

> First you need to use Windows PowerShell as admin.

> Now in file manager go to drive you want to setup wsl I'll use my `E:` drive.

> Make folder with any name in my case I'll go with `zero`.

> In windows powershell use command `cd E:\` use appropirate drive name in your case.

> `cd zero`

> `Invoke-WebRequest -Uri https://aka.ms/wsl-ubuntu-1804 -OutFile Ubuntu.appx -UseBasicParsing`

### Note : for diffrent distro

```javascript
System	            URL
Ubuntu 18.04	    https://aka.ms/wsl-ubuntu-1804
Ubuntu 18.04 ARM	https://aka.ms/wsl-ubuntu-1804-arm
Ubuntu 16.04	    https://aka.ms/wsl-ubuntu-1604
Debian GNU/Linux	https://aka.ms/wsl-debian-gnulinux
Kali Linux	        https://aka.ms/wsl-kali-linux
OpenSUSE	        https://aka.ms/wsl-opensuse-42
SLES	            https://aka.ms/wsl-sles-12
```

> `move .\Ubuntu.appx .\Ubuntu.zip`

> `Expand-Archive .\Ubuntu.zip`

> `cd .\Ubuntu\`

> `ls`

> `.\ubuntu1804.exe`