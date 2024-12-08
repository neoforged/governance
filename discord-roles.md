### Discord Ownership
The ownership of the Discord is Transferred to a special account: `@neoforged.admin` its credentials can be found in the core Vault

### Roles
| Name                              | Members                 |      Hoisted       |        Color        |                Icon                |
|-----------------------------------|-------------------------|:------------------:|:-------------------:|:----------------------------------:|
| PIM Bot                           | PIM Bot                 |        :x:         |        None         |                None                |
| Server Manager (Manage server)    | PIM                     |        :x:         |        None         |                None                |
| Role Manager (Manages roles)      | PIM                     |        :x:         |        None         |                None                |
| Channel Manager (Manage channels) | PIM                     |        :x:         |        None         |                None                |
| Announcer                         | PIM                     |        :x:         |        None         |                None                |
| Steering Council                  | SC Members              | :white_check_mark: |        None         |                None                |
| Moderators                        | Moderators              | :white_check_mark: |        None         |                None                |
| Maintainers                       | Maintainers             | :white_check_mark: |        None         |                None                |
| Foundation Team                   | Foundation Members      | :white_check_mark: |        None         |                None                |
| Infrastructure Team               | Infrastructure Managers | :white_check_mark: |        None         |                None                |
| Docs Team                         | Documentation writers   | :white_check_mark: |        None         |                None                |
| Bot Team                          | Bot managers            | :white_check_mark: |        None         |                None                |
| NeoForged Team                    | All team members        |        :x:         |        None         |                None                |
| Mojang Team                       | Mojangsters             |        :x:         |        None         |                None                |
| ModLauncher Team                  | McModLauncher Team      |        :x:         |        None         |                None                |
| RetroGradle Team                  | RetroGradle Team        |        :x:         |        None         |                None                |
| Moderator                         | Moderators              |        :x:         |        None         |                None                |
| Snapshot Alarm                    | Added via Discord Join  |        :x:         |        None         |                None                |
| Announcement Pings                | Added via Discord Join  |        :x:         |        None         |                None                |
| Dev Announcement Pings            | Added via Discord Join  |        :x:         |        None         |                None                |
| Snapshot Guesser                  | ?                       |        :x:         |        None         |                None                |
| All Vanity Roles                  |                         |        :x:         | 1 for each MC Color | 1 for each hoisted role + combined |
| All Bot Roles                     |                         |        :x:         |        None         |                Gear                |

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

