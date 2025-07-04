# Maintainer Policies and Guidelines

This document aims to clarify policies by which the Maintainer team operates. The goal is to help Maintainers understand what is expected of them and what actions should be done to reduce the chances of conflict within the Maintainer team.

## Policies

- `c` tags in 1.21+ NeoForge should be kept in sync with Fabric's `c` tags as close as possible. New `c` tags or changes to existing `c` tag should by ran by Fabric to ensure they will agree to make the same changes. `c` tags are to be a standard between loaders with Fabric being our main partner in this effort.

## Guidelines

- PRs that had requested changes from a maintainer or has another maintainer assigned to the PR, these maintainer(s) should be contacted first before merging the PR to ensure they are ok with the final form of the PR and that their concerns were properly addressed. Along these lines, a maintainer's review should not be "dismissed" without checking with the maintainer.

- Breaking change window for the NeoForge project will generally aim to last about 1 month after a significant Minecraft version.

  - Hotfix Minecraft versions or very small Minecraft versions will not reset the breaking change window.

  - This window is flexible and may be longer if there is significant breaking change PRs that need to be released for that Minecraft version but not yet ready. The 1 month timeframe is just a goal we would like to achieve but we understand it is not always possible or optimal.

- Maintainers should ping @Maintainers on discord before merging important PRs. What is considered important enough to warrant a ping is left to maintainer discretion, but it is better to ping too often rather than not enough.

  - An important PR could be one that has a significant impact on many systems, changes the project ecosystem, or requires significant coordination with external projects. But ultimately, it is still left up to the maintainer discretion.
  
  - There is no hard enforcement of this guideline. Rather it aims to show that communication of a "big-deal" PR is important to helping to keep the team in the loop of what is going on and prevent conflicts between teammates. The examples given helps to give a sense to what kind of PR is considered a "big-deal" but it is left a bit open-ended as PRs can take many forms. We will defer to the PR creator's to use their best judgement on whether a PR is something to keep the team informed about or not. The rate of "big-deal" PRs should be uncommon so ideally, this should not lead to an excess of maintainer pings.