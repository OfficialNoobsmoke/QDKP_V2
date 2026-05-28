<h1>Quick DKP</h1>

<b>Quick DKP V2</b> is an addon for World of Warcraft that aims to handle <b>every aspect</b> of the DKP management of a guild. Its goal is to stay <b>completely in-game</b>, storing points and time amounts in the <b>officer or public notes</b> fields of the guild's chart, in a clear format readable by everyone <b>without using the mod</b>.
<h1>Features List:</h1>

<b>Completely Ingame:</b> Designed to fully work on his own while playing, Quick DKP can also export dkp and log data with various formats for forums, web pages or guild DKP sites like Guildzilla.

<b>Very easy to use and maintain: </b>You can learn to use it in few minutes.

<b>Flexible: </b>you can adjust many parameters of the mod to best suit your guild's needs, adapting it to every points or roll based loot system known. ALL options are kept in a single file (Options.ini) easy to share with your guildmembers or repack in a custom package.

<b>Automated Awarding and Charging systems:</b> ** Boss Bonus DKP table, to award the raid when the given boss is killed ** Give DKP on a hourly base (Hourly bonus) ** Award the most hard-core gamers with the IronMan bonus, which gives DKP to the players who stayed for the whole raid. ** For guilds with fixed item prices, compile a table of item prices based on the instance and the difficulty level. ** Give custom raid awards as a bonus, just with a click. ** Redistribute DKP from a member to other Raid members with the ZeroSum function.

<b>Fully configurable Bid Manager:</b> The integrated bid manager support every dkp or roll bidding system known, like open/silent bid, pure or modified roll, random influenced bid, ni karma or shroud loot systems, "spend one more" policy and so on.

<b>Dynamic and Interactive Log System:</b> Keep a unique and complete history of your raids! The log will store every modification, and you'll be able to view and edit those modifications at any time. QDKP will update the data as requested, in real time. It will also monitor and log the killing of bosses, bids, loots, raid members who joins, leaves and goes on or offline.

<b>Info Center:</b> Guildmembers who don't have the addon installed can whisper you to know their DKP amounts, the dkp they earned and spent in the current session or get a DKP top ten of their rank or class, or an overview of their personal log. You can output detailed reports of any log view to any channel. You can even set QDKP to actively announce DKP modifications and events to the raid chat, or to push notifications via whispers.

<b>DKP values exporter</b>: You can export a table with the DKP table for the whole guild, in both plain text or HTML format, or in a convenient XML format useful to be imported in a database. You can copy the table and paste it in your guild site, or in a forum, or wherever you like.

<b>Alternatives Support:</b> You can easily define alts, to implement a Player-based DKP pool. Each alt is related to a Main Character, and will share his DKP amounts and his Log.

<b>External Support:</b> Add players that aren't in your guild to QDKP's local Guild Roster, and add players that aren't in the current raid as standby players, enabling them to get DKP awards.

....And more....

<h1>FAQ</h1>

<i>I am an officer, but QDKP won't let me edit DKP, it only show a list of players.</i> To enable the officer mode, your guild rank must have the rights to edit Officer notes AND guild notes. If you don't, Quick DKP assumes you are not allowed to edit DKP and put itself in read only mode. The only way to change this is to ask your guild master to edit the guild permissions of your rank, or to be promoted to a higher rank that has the needed rights.
If you hover the cursor over QDKP's minimap icon, you'll see the status of your guild rights. The command "/dkp permissions" will do the same.

<b>Please Note</b>:If your guild stores DKP values in the public notes rather than officer notes, then you need the rights to edit public notes.

<i>How do I configure the mod?</i> Quick DKP configuration is in a .ini file, that you can find in the QDKP_V2 addon directory (usually under c:/Program Files/World of Warcraft/Interface/Addons). There you'll find a file named "Options.ini": open it with notepad or any other text editor. There you'll see a huge amount of configuration options. There are a lot of comments, so it should be easy to set it up. Once done, you can mail the file to your officers, or put it on your guild site (if any). That way, all your DKP officers will work with the same configuration.
<b>REMEMBER: To apply the changes you make to the options file, you have to relog WoW.</B> While you are in the process of setting things up, I suggest you to disable all mods except for Quick DKP, and use the WoW command "/reload" to import the changes you do to the options file without relogging each time.

Should you make an error setting up the options.ini file, QDKP won't be able to read it and will fall back to the default values. If your settings don't appear to be used, then probably this is what is happening. Enabling the display of LUA errors (under WoW interface options->help) can help you spot bugs in the options file.

A GUI configuration tool is in the ToDo list.

<i>Do I need to edit the options file each time I update the addon?</i> No you don't, unless the update has some new setting you need to modify from the default value. QDKP has default values for every setting, so you can just save the options file somewere on your computer (or in your guild site), update the addon, and copy back the options file over the default in the QDKP_V2 directory, overwriting it.

<i>Regular players can't view the DKP amounts</i> Have you enabled all ranks to view officer notes? If you don't want to do it, you can set QDKP to use the public notes instead. Remember to back up DKP amounts before switching storing system!

<i>How do I reset dkp/log/hours/everything?</i> The command to reset stuff is "/qdkp reset x", where x is one of these keywords: log to clear the log, dkp to reset all guild's DKP to 0, hours to do the same for the raiding hours, local to clear the data stored locally (the log, the guild externals and some settings), and all combines the previous to completely reset all QDKP related data. The reset command has only effect with the data related to the guild you currently are in.

<i>Where did the "Notify all" button go?</i> Since the roster now supports multiple selection, it became obsolete. To achieve the same function, select all the player in the raid roster (by shift+click or by right clicking the roster background->"Select all"), then right click on any player->"Notify DKP".

<i>Where did the "+1 Hours" button go?</i> You can find it under the "Quick modify" voice of player's menu in the roster. Please mind that it works with multiple selections: all of the selected members will get 1 extra raiding hour.

<i>I get the chat frame spammed with "xyz is not in the guild", and I have set the hide ranks OR min level filters in the options.ini.</i> That is a known bug that has been fixed in version 2.6.0. Update now to fix it.

<i>I have problems setting up the bid manager to suit my guild needs</i> I know, setting up the bid manager can be tricky, especially if you have no programming experience. I had to make it that way to be as flexible as possible. If you're having problems, you can mail me or post a request here on Curse with your needs.
