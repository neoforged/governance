### Discord Ownership
The ownership of the Discord is Transferred to a special account: `@neoforged.admin` its credentials can be found in the core Vault

### Roles
| Name                   | Members                           | Description                                                       |      Hoisted       |        Color        |                Icon                |
|------------------------|-----------------------------------|:------------------------------------------------------------------|:------------------:|:-------------------:|:----------------------------------:|
| PIM Bot                | PIM Bot                           | PIM bot - see below                                               |        :x:         |        None         |                None                |
| Server Manager         | PIM                               | Has Manage Server/Admin permission                                |        :x:         |        None         |                None                |
| Role Manager           | PIM                               | Has Manage Roles permission                                       |        :x:         |        None         |                None                |
| Channel Manager        | PIM                               | Has Manage Channels permission                                    |        :x:         |        None         |                None                |
| Announcer              | PIM                               | Has Write Message permission in #announcements/#dev-announcements |        :x:         |        None         |                None                |
| Steering Council       | SC Members                        | Steering Council role, as we currently have it.                   | :white_check_mark: |        None         |                None                |
| Moderators             | Moderators                        | Has moderation permissions, i.e. mute, kick, ban, etc.            | :white_check_mark: |        None         |                None                |
| Maintainers            | Maintainers                       | Has GitHub permissions.                                           | :white_check_mark: |        None         |                None                |
| Foundation Team        | Foundation Members                | Involved in the NeoForged legal entity.                           | :white_check_mark: |        None         |                None                |
| Infrastructure Team    | Infrastructure Managers           | Involved in the project infrastructure in some way.               | :white_check_mark: |        None         |                None                |
| Docs Team              | Documentation writers             | People with permissions on the docs repo.                         | :white_check_mark: |        None         |                None                |
| Bot Team               | Bot managers                      | People who can manage the bot.                                    | :white_check_mark: |        None         |                None                |
| NeoForged Team         | All team members                  | Catch-all for all the hoisted roles above.                        |        :x:         |        None         |                None                |
| Mojang Team            | Mojangsters                       | Mojang people.                                                    |        :x:         |     Mojang Red      |                None                |
| ModLauncher Team       | McModLauncher Team                | Members of the ModLauncher side project.                          |        :x:         |        None         |                None                |
| RetroGradle Team       | RetroGradle Team                  | Members of the RetroGradle side project.                          |        :x:         |        None         |                None                |
| Moderator              | Moderators                        | The pingable moderator role.                                      |        :x:         |        None         |                None                |
| Probation              | New team members                  | Given to new team members.                                        |        :x:         |        None         |                None                |
| Snapshot Alarm         | Added via Discord Join            | Available for anyone to add in Channels & Roles.                  |        :x:         |        None         |                None                |
| Announcement Pings     | Added via Discord Join            | Available for anyone to add in Channels & Roles.                  |        :x:         |        None         |                None                |
| Dev Announcement Pings | Added via Discord Join            | Available for anyone to add in Channels & Roles.                  |        :x:         |        None         |                None                |
| Snapshot Guesser       | Whoever guessed the snapshot time | Assigned by a team member.                                        |        :x:         |        None         |                None                |
| All Vanity Roles       | All team members (optionally)     | The only roles with colors.                                       |        :x:         | 1 for each MC Color | 1 for each hoisted role + combined |
| Nitro Booster          | Nitro boosters                    | Handled by the Discord integration.                               |        :x:         |        None         |         Nitro Booster Icon         |
| All Bot Roles          | All bots                          | Discord-demanded integrations.                                    |        :x:         |        None         |                Gear                |

### PIM
PIM stands for Privileged Identity Management, its main goal is to provide a Just-In-Time way of giving users permissions when they need it.
In a controlled and operational fashion. With or without approval of a second person.
This ensures that roles with extreme rights, which when misused (either through hacking or for personal gain) would harm the server and the community.
If an approval is needed for the role, it can only be granted by somebody other than the requester, even if the requester would normally be eligible to approve the role request.
All team members will be eligible for any and all roles exposed via the bot.

#### The PIM Bot
The pim bot is a special sole purpose bot that can be used by team members to request certain roles.
Its command structure is: `/pim <rolename> <reason>` depending on the roles configuration within the bot, the bot will them either directly assign your requested role to you, or ask a specific team for approval.
When the allotted time for your assignment has passed, the bot will automatically remove the role from you. This way you do not forget, and the risk to the community is minimal.

#### High privilege roles
There are two high privilege roles:
- Server manager
- Role manager

These roles will be assigned for 6 hours maximum and require an approval of a Steering Council member

#### Medium privilege roles
There is currently one medium privilege role:
- Channel Manager

These roles will be assigned for 12 hours maximum and require an approval of a moderator

#### Low privilege roles
There is currently one low privilege role:
- Announcer

This role is assigned for 16 hours maximum and does not require an approval.

### Vanity roles.
There are two kinds of vanity roles: Color and Icon
Depending on the team, each team will get its own icon, and as such each team member will get an Icon role assigned, potentially multiple.
The color is freely pick-able by any team member (however each team will get a default color role as well)
The available colors are the 16 colors from Minecraft, else we will again have a wild mixture of roles.
One last special vanity role is Automation, which marks all bots.

