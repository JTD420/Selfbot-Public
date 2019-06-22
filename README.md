"**# Selfbot-Public**" 

This page is a heavy W.I.P
Eventually this should be a well documented guide explaining the how to use the different commands that the bot comes with.

   **Note:  It's recommended that if you are able to do so you should always end the program gracefully with the stop command wherever possible.**

**[*****Cmnd Index*****]: - All commands here exclude their prefix which is set independently through the config.ini file!**   
    `renick`: Animates the user that ran the commands Name   
    (if in a server & the user is included in either allowed_ids or owner_id)  
    
`stop`: This command can ONLY be ran by "owner_id" in the config file. Executing this command will gracefully exit the program logging out of any open sessions first.    
    
`refresh`: This can be ran by anyone in allowed_ids + owner_id can execute. This is a "soft-restart". It will stop any/all running commands and restart the bot. It will not re-read things like the config file.   
    (*changes to config file for example will not be detected by doing `refresh` you must do a hard-restart for that such as manually with the red X button and reopening or by doing the `stop` command and then re-opening the program.*)   
  
  
`test`: Command was left in for debug purposes. Simply shows a message with 3 stats;   
```
1, The owner_id as set in the config.ini file.   
2, The allowed_ids as set in the config.ini file.   
3, A combination of both used to say when anyone in either owner or allowed_ids should be able to execute command.   ```
