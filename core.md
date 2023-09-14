# Governance of the NeoForged project

The NeoForged project is split between [GitHub](https://github.com/NeoForged) and [Discord](https://discord.neoforged.net). It is a community of volunteers, maintaining a free and open source ecosystem of modifications to the Minecraft game.

### What this document is

This document is:
 * A non-exhaustive list of the working principles of the project.
 * Intended to help direct the project in times of uncertainty.

This document is built on the fundamental principle of "people generally want to help, so we should not get in the way of it".

The core ethic is "people over processes", so this document is intentionally light on processes - situations that come up are rarely one-size-fits-all, and should be treated on a case by case basis, with the best process to fit the person.

### What this document is not

This document is not:
 * Intended to enforce rules on all members.
 * Intended to catch all possibilities.
 * Intended to prevent "rules lawyering".

The code of conduct of the project is taken to be the content of [the Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/), so this document is not the code of conduct.

Conflict resolution is the responsibility of the Moderation and Steering Council teams. They may wish to append a section to this document, but currently, this document is not conflict resolution.

## Definitions

Following are some core definitions that will be referred to in the later sections of the document.

### The Project

"The Project" refers to The NeoForged project, with a presence on both GitHub and Discord, as noted at the start of this document. It does not refer to any specific Repository or subproject.

### Subprojects

Subprojects are large tasks that the Project itself is undergoing.

These may be:

* Repositories under the Project's GitHub
* Large, multi-repository tasks that are being undertaken (ie. updating the Modloader to a new version of the Game)
* Smaller, more targetted tasks that are being undertaken (ie. refactoring the Modloader to remove or replace or rework a feature)

### Teams

The Project is split into four teams.

A team is a group of people with similar goals, and equal weighting in most decision making - with some exceptions, which will be explored later.

You may [apply to join some teams](https://tinyurl.com/ForgeApplications), but some require appointment from within an existing team, or further voting after application.

#### Steering Council

The Steering Council are the management of the Project. 

They "steer" the project to keep it aligned with the long-term vision, hence its secondary name of Vision Team.

The Council has at all times an odd number of active members, such that stalemates are not possible.

A member may choose to become inactive and appoint another in their place until they return.

At least one member of the Council is promoted from other teams via an annual internal vote, to ensure that the Council always has a fresh opinion and does not stagnate over time.

Once a year, [an internal voting process](https://peps.python.org/pep-8104/) will determine the members that will be promoted to the Steering Council, via the ranked voting system. It is intended that at least one, and at most three members will be promoted at a time.

The Council also serves double duty as a mediator for disagreements between other teams. These shall be resolved by discussion, rather than by unanimous applications of the rules, so this is not in the purview of this document.

#### Maintainers

The Maintainers team consists of all project developers who have push access or technical rights to the project's repositories or infrastructure.

They are the ones keeping the Project's repositories up to date, and ensuring the quality and standards of the Project are upheld, as well as adding new features as the community comes to require them.

Though maintainers may individually or collectively have different access rights across the project's many repositories or infrastructure services, all maintainers within the team are considered equal to each other with respect to their rights within the team's governance.

Maintainers may be appointed by other maintainers, or by application from the person who wishes to join the team.


#### Moderators

The Moderation team is composed of all moderators of all community spaces (GitHub, Discord) under the purview of the project.

They have the responsibility of enforcing the policies and rules of each space, as well as the Code of Conduct, and applying disciplinary sanctions to people who violate said rules.

#### Subproject Leads

A special group exists for those designated as "subproject leaders".

The members of this group were assigned from the Maintainers team, and is indeed a strict subset of the Maintainers team.

The role of this team is to take lead of a subproject, as defined above.

The subproject leader has total purview of their given subproject (repository or task) up to and including their primary goal.

They may:
* Decide the structure of their team, in whatever capacity is neccessary
* Decide who may or may not be on their team
* Delegate the power of subproject leader to another person
* Make final decisions on the implementation and structure of their subproject
* Overrule another Maintainer on the strict matter of their subproject, and no other.

They are not:
* A project dictator
* Unaccountable
* Free from scrutiny

They may not:
* Make decisions not related to their subproject
* Make major architectural decisions without the assent of the Steering Council

Finally, the decisions made by the subproject leader and their team are, under all circumstances, subject to regular scrutiny and final review by the Maintainers and the Steering Council, to ensure the subproject still holds to the Project's values and quality standards.
