# Freeze Command Docs
How to set up the Freeze command:

First, add the 3 Freeze commands: [freeze](https://github.com/DynoCC/Dyno-Custom-Commands/blob/master/Freeze.txt) [unfreeze](https://github.com/DynoCC/Dyno-Custom-Commands/blob/master/unfreeze.txt) [setupfreeze](https://github.com/DynoCC/Dyno-Custom-Commands/blob/master/setupfreeze.txt0

Then, run `?setupfreeze` in your server. This will do some of the setup work for you.

Next, go to the settings for each channel, and set `freeze` to `can't send messages`, as shown:
![Freeze Perms](https://cdn.discordapp.com/attachments/252296452708106240/337698978621685761/unknown.png)

Once you complete setting that for each channel, the freeze command should be ready. Simply use `?freeze` to freeze the server, and `?unfreeze` to revert to normal.
Note that on large servers it may take a while to freeze everyone, up to a minute.
Administrators are not affected by freezes.

If you want to customize the freeze command (maybe excludes certain roles), please contact us on Discord [here](https://discord.gg/8xBag8Q).

Note: If your server has a different prefix than `?`, you will need to use that prefix in place of `?` in this documentation.

Documentation written by advaith#9121.
