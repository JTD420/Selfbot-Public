"**# H4xr0x Bot/Selfbot-Public-Version**"    
![h4xr0x](https://img.shields.io/badge/dynamic/json.svg?color=Green&label=h4xr0x&prefix=v&query=$.message&url=http://35.211.65.163/test.json)
[![h4xr0x](https://img.shields.io/keybase/pgp/h4xr0x.svg)](https://keybase.io/h4xr0x/pgp_keys.asc)
[![keybase](https://img.shields.io/static/v1.svg?label=Add%20me%20on&message=Keybase&color=Blue&logo=keybase?style=for-the-badge)](https://keybase.io/h4xr0x/)
[![Donate-to-h4xr0x-with-BITCOIN](https://img.shields.io/keybase/btc/h4xr0x.svg)](https://keybase.io/h4xr0x/sigchain#4200bc86dc03131241bd4957d1a2ec1f469c203b17f0d9d1d052e1379190334d0f)
[![Donate-to-h4xr0x-with-XLM](https://img.shields.io/keybase/xlm/h4xr0x.svg)](https://keybase.io/h4xr0x/sigchain#c99a05b36bb2357a138eb8751374200270047a9c581b656eb371aeb5986d416d22)

**Support Server**:   
[h4xr0x v2 (Permenant Link)](http://h4xr0x.com) | [h4xr0x v2 (Discordapp Link)](https://discordapp.com/invite/bBa3jUB)


![h4x0rx bot](https://h4xr0x.keybase.pub/H4xr0x%20Selfbot.png "h4xr0x bot/selfbot")


This page is a heavy W.I.P
Eventually this should be a well documented guide explaining how to use the different commands that the bot comes with.

   **Note:  It's recommended that you end the program gracefully with the stop command whenever possible to ensure you are properly logged out.**

**[*****Cmnd Index*****]: - All commands here exclude their prefix which is set independently through the config.ini file!**   

`help`: Provides an always-up-to-date index of **all** commands!
`help <category>`: Provides an up-to-date description of commands and its usage. (Note:<category> is a placeholder)


`renick`: Animates the user that ran the commands Name   
    (if in a server & the user is included in either allowed_ids or owner_id)  
	
`bnick`: Animates the user that ran the commands Name Forwards then backwards   
    (if in a server & the user is included in either allowed_ids or owner_id)  
    
`stop`: This command can ONLY be ran by "owner_id" in the config file. Executing this command will gracefully exit the program logging out of any open sessions first.    
    
`refresh`: This can be ran by anyone in allowed_ids + owner_id can execute. This is a "soft-restart". It will stop any/all running commands and restart the bot. It will not re-read things like the config file.   
    (*changes to config file for example will not be detected by doing `refresh` you must do a hard-restart for that such as manually with the red X button and reopening or by doing the `stop` command and then re-opening the program.*)   
  
  
`embed`: Create a custom embed message.   
`altem`: Creates an alternative style embed message.   
`status`: Sets a custom status (e.g: `status h4xr0x selfbot is the best!`)   
`stream`   
`cycle`: Cycles through playing and streaming (e.g: `cycle h4xr0x`)   
`scycle`: Stop the cycle loop.   
`sbnick`   
`srenick`   
`lmgtfy`   
`ping`   
`say`   



---------------------------------------------
**[*****Operational Commands*****]: - All commands here exclude their prefix!**    
   
Note: `{category}` is a placeholder which should be replaced for the category you are trying to load/unload/reload.   
`Load {category}    
Unload {category}   
Reload {category}`   
Example: `load anywhere`   
The above example would load the `anywhere` category.
