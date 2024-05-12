# This script can setup discord from scratch on linux

- Requirements: wget command, tar command.

This script is capable of downloading whole discord from scratch using wget command.
usage:
```bash
git clone https://github.com/5onGoku/discordautoupdate.git
chmod +x discordautoupdate
./discordupdate or bash discordautoupdate
```
clone and run this script anywhere you like and it will install latest discord image from discord website in '/tmp' directory and extract its contents. Once the contents are extracted it will be copied to '/opt/Discord/' directory and then you can close the terminal and run discord so that it can update itself.

Make Sure: File permissions are set correctly for all users to execute the script use `chmod +x discordupdate`

Any Issue/Suggestions are highly appreciated!
