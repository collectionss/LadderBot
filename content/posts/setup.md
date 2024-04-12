---
author: LadderBot
title: "Getting Started"
date: "2023-04-11"
weight: 1
ShowReadingTime: false
ShowBreadCrumbs: false
---

This article goes over setting up LadderBot and running your first tournament.

<!--more-->

---

### Permissions Needed to Work

![Description of Image](/static/botPerms.png)

If you're comfortable with the bot having these permissions, you can add it to your server!

---

### Add LadderBot to Your Server

[Click here to invite LadderBot to your server!](https://discord.com/api/oauth2/authorize?client_id=1166023850962718741&permissions=268528656&scope=bot+applications.commands)

---

### Roles

Upon joining, LadderBot will create two roles:

1. **`TournamentMod`**: This role can be given to members you trust to manage tournaments in your server. They will be able to remove teams and players, start and end tournaments, and decide match results if necessary.

2. **`TournamentBan`**: Assign this role to members you do not want participating. It prevents them from creating or joining teams. Server Role Managers can add or remove this role before signups open. If a player is banned during the tournament, this role can be added, and a mod can remove the player.

---

### Creating a New Tournament

Mods and admins can use `/new_ladder` to create a new tournament. This command requires the tournament name, the maximum number of players per team, and the total number of teams that can sign up.

Currently, there is a maximum of 10 players per team and 128 teams per tournament.

You can also add any additional information you want players to know.

Afterward, a category with the tournament's name will be created along with a list of channels. A message will be posted in the info channel, explaining general info and rules, as well as any additional information the creator added.

![Description of Image](/static/channels.png)

---

### Now What?

Congratulations on creating your first tournament!

Remember that commands will only work in the channels created by `/new_ladder`.

Now is the time for admins/server mods to distribute the roles created by LadderBot. Ban the players you don't want participating and assign the `TournamentMod` role to your trusted mods.

When you're ready for teams to sign up, use `/toggle_signup` to let registrations!
If you want teams to be able to do things like edit their name or change their roster, use `/toggle_team_edits`!

---

### Starting

To begin the matches, use `/start`. Team rankings will initially be random.

---

### Ending

Use `/end` to conclude the tournament, preventing any further matches.

When you're ready to completely remove the tournament from the server, use `/clean` to delete all the tournament-specific channels.

---
