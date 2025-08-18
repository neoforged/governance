# The process for organising NeoForged Steering Council Elections

As stated in the [Governance document](core.md), the Steering Council is to be elected annually from among the team members. This document lays out how this process is intended to work. The process is largely inspired by [the process implemented in the Python ecosystem](https://peps.python.org/pep-0013/).

## Who Is Eligible to Participate?

All team members of the NeoForged Project are eligible to both run and vote. This most importantly includes the two main teams, Moderators and Maintainers, but it also extends to other subteams of the Project.

At least one new member should be elected to the Steering Council in each year, to get fresh views and opinions into the council.

### Election Officers

Before the election, one election officer is determined from among the team and internally announced as such. They are assigned by the Steering Council, ideally after volunteering. If no one volunteers, a NeoForged team poll is done where everyone can submit a name to be the election officer and whoever gets the most nomination, is the officer. In the case of a tie, a candidate will randomly be chosen using a random number generator. then The election officer should not be a member of the Steering Council prior to the election.

The election officer's job is to organize and supervise the election process. Additionally, they must also announce a timeframe for the election process beforehand. Suggestions for the duration of the individual phases of the election are stated below.

## The Election Process

The election process has three phases. For the sake of organization, all information related to the election should be kept in a separate internal text channel (or thread), and all announcements by election officers should be pinned to that channel (or thread) for easy reference.

### Phase One: Nominations

To begin, candidates can be nominated. Any team member may nominate any amount of candidates, including themselves, by sending a message to an election officer. There explicitly is no limit as to the amount of possible nominations, it is appealed to the team members' discretion to only nominate candidates they actually see fit.

The nomination message may optionally contain a reason for the nomination, i.e., why the nominator thinks the nominee would be a good fit for the position. This is optional as to avoid "flavor text" that might result from making this mandatory.

This phase should run for approximately one week, with the timeframe announced beforehand. After nominations have ended, the election officers will announce a list of nominations and - if applicable - nomination messages to the channel. The nominators will not be announced by the election officers, however, nominators may choose to announce their support for certain candidate(s) themselves.

Sitting members of the Steering Council are expected to announce their intent to re-run, or the lack thereof, prior to the nomination phase.

After a nomination has been received, the corresponding election officer should send a message to the nominee, confirming that they accept the nomination. If a nominee does not respond within the set timeframe, it will be assumed that they accepted the nomination.

### Phase Two: Voting

After the candidates have been announced, the voting phase will commence. Like the nominating phase, this phase should run for approximately one week, with the timeframe announced beforehand.

It is suggested that the [Helios voting service](https://vote.heliosvoting.org), or a similar service, be used for conducting the election. This choice is to be made by the election officers. The election officers are then also responsible for setting up the service for use before the voting phase begins.

It should be possible to vote at least three members (as the Steering Council has three seats). It is suggested that voting more than three members is possible, so that people who cannot or do not want to decide between two candidates they perceive as equal have the option to vote both.

### Phase Three: Results

After voting has finished, the election officers announce the results internally as soon as possible for them. A transition of power is to be prepared, including reassignment of roles and permissions. In parallel, a public statement in the form of a Discord announcement and a blog post is to be prepared and released.

In the event of a tie that would cause one or more members to win a seat on the council while one or more members with the same amount of votes would not win a seat, i.e. if a tie occurs for places 3 and 4 (and beyond), or for places 2, 3 and 4 (and beyond), or for places 1, 2, 3 and 4 (and beyond), the result is to be determined from among the candidates randomly by an election officer.

## Communication to the Outside

It should be announced to the public that an election process has been initiated. Other than that, in order to not compromise the integrity of the vote, public statements about the election should be kept to a minimum until the election is over.

## Replacements and Emergency Elections

A Steering Council member may choose to become inactive and appoint another Project team member in their place until they return or their term expires.

If a Steering Council member cannot be reached and there is an important time-sensitive Steering Council vote, an emergency Steering Council election will be held in accordance with [The Election Process](#the-election-process) section with the only differences being, nomination is now 24 hours, a Steering Council member cannot nominate themselves as they are already on Steering Council, and the voting process is also 24 hours. The newly elected member(s) will now act as the Steering Council member in question until the original Steering Council member(s) return or their term expires.

## Considerations

Before the election is started, ensure that the Grace Period role is taken care of. See more [info about that here.](./inactivity-policy#grace-period-at-steering-council-voting)
