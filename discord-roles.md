# Discord Roles
With Discord being one of the main community spaces of the NeoForged project, a proper structure for Discord is needed. This document lays out the roles and administration concepts for the NeoForged Discord server.

## Ownership
The ownership of the Discord is held by a special account: `@neoforged.admin`. Its credentials can be found in the Vault, accessible by Steering Council members.

## Roles
| Name                   | Members                           | Description                                                                                         |      Hoisted       |        Color        |                Icon                |
|------------------------|-----------------------------------|:----------------------------------------------------------------------------------------------------|:------------------:|:-------------------:|:----------------------------------:|
| Server Owners          | Admin account                     | Server owner, hoisted for visibility                                                                 | :white_check_mark: |     Bright Red      |                Hammer              |
| PIM Granters           | PIM Bot                           | PIM granters. Can grant privileged roles to team members                                             |        :x:         |        None         |                None                |
| Server Manager         | PIM                               | Has Manage Server/Admin permission                                                                   |        :x:         |        None         |                None                |
| Role Manager           | PIM                               | Has Manage Roles permission                                                                          |        :x:         |        None         |                None                |
| Channel Manager        | PIM                               | Has Manage Channels permission                                                                       |        :x:         |        None         |                None                |
| Announcer              | PIM                               | Has Write Message permission in #announcements/#dev-announcements                                    |        :x:         |        None         |                None                |
| Steering Council       | SC Members                        | Steering Council role, as we currently have it.                                                      | :white_check_mark: |        None         |                Steering wheel      |
| NeoForged Team         | All team members                  | Catch-all for all the hoisted roles.                                                                 |        :x:         |        None         |                Fox                 |
| Moderaintainer         | Moderator && Maintainer           | Any team member that is moderator and maintainer.                                                    |        :x:         |        None         |                Tagged Shield       |
| Moderators             | Moderators                        | Has moderation permissions, i.e. mute, kick, ban, etc.                                               | :white_check_mark: |        None         |                Shield              |
| Maintainers            | Maintainers                       | Has GitHub permissions.                                                                              | :white_check_mark: |        None         |                Tag                 |
| Foundation Team        | Foundation Members                | Involved in the NeoForged legal entity.                                                              | :white_check_mark: |        None         |                None                |
| Infrastructure Team    | Infrastructure Managers           | Involved in the project infrastructure in some way.                                                  | :white_check_mark: |        None         |                Server              |
| Docs Team              | Documentation writers             | People with permissions on the docs repo.                                                            | :white_check_mark: |        None         |                Clipboard           |
| Bot Team               | Bot managers                      | People who can manage the bot.                                                                       | :white_check_mark: |        None         |                None                |
| Automation             | Camelot                           | Contains camelot so that it can moderate the public.                                                 |        :x:         |        Gray         |                Gear                |
| Mojangstas             | Mojangsters                       | Mojang people.                                                                                       |        :x:         |     Mojang Red      |                None                |
| ModLauncher            | McModLauncher Org                 | Members of the ModLauncher side organization                                                         |        :x:         |        None         |                None                |
| Moderator              | Moderators                        | The pingable moderator role.                                                                         |        :x:         |        None         |                None                |
| Probation              | New team members                  | Given to new team members.                                                                           |        :x:         |        None         |                None                |
| Collaborator           | Recognized non-NeoForged people   | Has libraries or other works that NeoForged is reliant upon. Grants access to public "talk" channels |        :x:         |        None         |                None                |
| Community Volunteers   | Community volunteer Helpers       | Given to community experts to help others.                                                           |        :x:         |        None         |                None                |
| Former Member          | Old team members                  | Given to old team members to honor their contributions.                                              |        :x:         |        None         |                None                |
| Snapshot Alarm         | Added via Discord Join            | Available for anyone to add in Channels & Roles.                                                     |        :x:         |        None         |                None                |
| Announcement Pings     | Added via Discord Join            | Available for anyone to add in Channels & Roles.                                                     |        :x:         |        None         |                None                |
| Dev Announcement Pings | Added via Discord Join            | Available for anyone to add in Channels & Roles.                                                     |        :x:         |        None         |                None                |
| Snapshot Guesser       | Whoever guessed the snapshot time | Assigned by a team member.                                                                           |        :x:         |        None         |                None                |
| All Vanity Roles       | All team members (optionally)     | The only roles with colors.                                                                          |        :x:         | 1 for each MC Color | 1 for each hoisted role + combined |
| Nitro Booster          | Nitro boosters                    | Handled by the Discord integration.                                                                  |        :x:         |        None         |         Nitro Booster Icon         |
| All Bot Roles          | All bots                          | Discord-demanded integrations.                                                                       |        :x:         |        None         |                Gear                |
                                    
### PIM
PIM stands for Privileged Identity Management. Its main goal is to provide a just-in-time way of giving users permissions when they need it, in a controlled and operational fashion, with or without approval of a second person.

This ensures that roles with extreme rights, which when misused (either through hacking or for personal gain) would harm the server and the community, are not directly accessible via Discord alone.

If an approval is needed for the role, it can only be granted by somebody other than the requester, even if the requester would normally be eligible to approve the role request.

All team members will be eligible for any and all roles exposed via the bot.

#### The PIM Bot
The pim bot is a special sole purpose bot that can be used by team members to request certain roles. Its command structure is: `/pim <rolename> <reason>`.

Depending on the configuration within the bot, the bot will then either directly assign the requested role to the team member, or ask a specific team for approval.

When the allotted time for the role assignment has passed, the bot will automatically remove the role from the team member. This way there is no way of forgetting to unassign the role, and the risk to the community is minimal.

#### High privilege roles
There are two high privilege roles:
- Server manager
- Role manager

These roles will be assigned for 6 hours maximum and require approval of a Steering Council member.

#### Medium privilege roles
There is one medium privilege role:
- Channel Manager

These roles will be assigned for 12 hours maximum and require approval of a moderator.

#### Low privilege roles
There is one low privilege role:
- Announcer

This role is assigned for 16 hours maximum and does not require an approval.

#### Collaborator role

This is a unique role to generalize granting access to public-viewable "talk" channels and for identifying people who have libraries, tooling, or other works that NeoForged's projects are reliant upon or uses. Any NeoForged member can grant this role to other.

ModLauncher and Mojangstas roles are not impacted as those two are special cases to be handled separately.

### Vanity roles.
The vanity roles exist so that team members can assign themselves the color they want.

The available colors are the 16 colors from Minecraft, else we will again have a wild mixture of roles.

One last special vanity role is Automation, which marks all bots, and gives them the ability to actually operate on the general public.

