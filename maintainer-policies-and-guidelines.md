# Maintainer Policies and Guidelines

This document aims to clarify hard policies that Maintainers have to follow as well as less-enforced guidelines that are recommended to be followed. The goal is to help Maintainers understand what is expected of them and what actions should be done to reduce the chances of conflict within the Maintainer team.

## Policies

- `c` tags in 1.21+ NeoForge should be kept in sync with Fabric's `c` tags as close as possible. New `c` tags or changes to existing `c` tag should by ran by Fabric to ensure they will agree to make the same changes. `c` tags are to be a standard between loaders with Fabric being our main partner in this effort.

  - Failure to meet this expectation will result in the change being undone so NeoForge matches Fabric again and the incident reviewed to understand how we failed to communicate with Fabric.

## Guidelines

- Breaking change window for the NeoForge project will generally aim to last only 1 month after a significant Minecraft version.

  - Hotfix Minecraft versions or very small Minecraft versions will not reset the breaking change window.

  - This window is flexible and may be longer if there is significant breaking change PRs that need to be released for that Minecraft version but not yet ready. The 1 month timeframe is just a goal we would like to achieve but we understand it is not always possible or optimal.

- When making a "big-deal" PR, please post a link to the PR in the NeoForge Discord's maintenance-talk channel, ping the maintainer role, and leave a short sentence on what the PR is about.

  - A "big-deal" PR is one that has a significant impact on many systems, changes the project ecosystem, or requires significant coordination with external projects.
  
    - An example of a significant impact on many systems, Transfer PR which involved creating a transaction system and refactoring the item/fluid/energy handlers. Many systems affected and massive amount of changes. This is a big deal.

    - An example of a project ecosystem change is the PR to merge ModLauncher code into FancyModLoader to remove the dependency to ModLauncher. We folded one deliberately-external project into our own project. This is a big deal as it changes what is in scope of the NeoForged organization and changed the relation between projects. If two of our own NeoForged projects were to merge or split up into more, this too would be a big deal as maintainers would definitely like to know as keeping track of what project relates to what is important. *(In addition, when cutting out reliance on an external project that we had close relations with, we should notify the owner of the external project before we cut the ties)*

    - Lastly, a solid example of a coordination work is the Unify Tag PR which created a new policy that new `c` tags have to be ran by Fabric first to see if they agree with adding them and requiring NeoForge to keep their `c` tags to be as similar to Fabric's as possible. The Unify Tag PR is also a significant many-system impact example too due to the wide-reaching nature of tags.

  - There is no hard enforcement of this guideline. Rather it aims to show that communication of a "big-deal" PR is important to helping to keep the team in the loop of what is going on and prevent conflicts between teammates. The examples given helps to give a sense to what kind of PR is considered a "big-deal" but it is left a bit open-ended as PRs can take many forms. We will defer to the PR creator's to use their best judgement on whether a PR is something to keep the team informed about or not. The rate of "big-deal" PRs should be uncommon so ideally, this should not lead to an excess of maintainer pings.