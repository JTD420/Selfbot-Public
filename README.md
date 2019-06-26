"**# Selfbot-Public**" 
![h4xr0x](https://img.shields.io/badge/dynamic/json.svg?color=Green&label=h4xr0x&prefix=v&query=$.message&url=http://35.211.65.163/test.json)

This page is a heavy W.I.P
Eventually this should be a well documented guide explaining how to use the different commands that the bot comes with.

   **Note:  It's recommended that you should end the program gracefully with the stop command wherever possible to ensure you are properly logged out.**

**[*****Cmnd Index*****]: - All commands here exclude their prefix which is set independently through the config.ini file!**   

`renick`: Animates the user that ran the commands Name   
    (if in a server & the user is included in either allowed_ids or owner_id)  
	
`bnick`: Animates the user that ran the commands Name Forwards then backwards   
    (if in a server & the user is included in either allowed_ids or owner_id)  
    
`stop`: This command can ONLY be ran by "owner_id" in the config file. Executing this command will gracefully exit the program logging out of any open sessions first.    
    
`refresh`: This can be ran by anyone in allowed_ids + owner_id can execute. This is a "soft-restart". It will stop any/all running commands and restart the bot. It will not re-read things like the config file.   
    (*changes to config file for example will not be detected by doing `refresh` you must do a hard-restart for that such as manually with the red X button and reopening or by doing the `stop` command and then re-opening the program.*)   
  
  
`embed`: Create a custom embed message.
`status`: Sets a custom status (e.g: `status h4xr0x selfbot is the best!`)
`cycle`: Cycles through playing and streaming (e.g: `cycle h4xr0x`)



---------------------------------------------
**[*****Operational Commands*****]: - All commands here exclude their prefix!**  

Note: `{category}` is a placeholder which should be replaced for the category you are trying to load/unload/reload.
`Load {category}
Unload {category}
Reload {category}`
Example: `load anywhere`
The above example would load the `anywhere` category.
