# NLP Sandbox Discord Server

[![Discord](https://img.shields.io/discord/770484164393828373.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=Discord&logo=discord)](https://discord.gg/Zb4ymtF "realtime support / chat with the community and the team.")

How to configure and use the NLP Sandbox Discord server

## Server Template

You can use [NLP Sandbox Discord Server Template] to instantiate a Discord
server with the same configuration as this server. Discord shows a previous
of the server before you actually create the server. You can always edit the
channels, roles, and permissions after creation.

## Roles

### Group roles

| Name | Description |
|---|---|
| admin | Administrator of the server |
| team | Members of the NLP Sandbox Team |
| moderator | Moderator of the server |
| community-dev | Users who contribute to the development of the NLP Sandbox |
| bot | Bot |
| @everyone | Everyone |

### Support roles

| Name | Description |
|---|---|
| support-room-1 | Allows the user to join the voice channel Support Room 1 |
| support-room-2 | Allows the user to join the voice channel Support Room 2 |
| verified | User who has accepted the server rules |
| muted | Prevent the user from sending messages |

## Categories and Channels

### Information Channels

| Name | Description | |
|---|---|---|
| #welcome | Welcome channel | |
| #rules | Rules of this server |   |
| #announcements | NLP Sandbox announcements |  |
| #blog | News, articles, tutorials on topics related to the NLP Sandbox |  |
| #releases | Notifications on new releases |  |
| #suggestions | Feedback from the community |  |

### Moderation

| Name | Description | |
|---|---|---|
| #admins | Channel for admins | |
| #moderators | Channel for moderators | |
| #logs | Logs of the server | |
| Admins Hangout | Voice channel for admins | |
| Moderators Hangout | Voice channel for moderators | |

### Support

| Name | Description | |
|---|---|---|
| #general-support | Main channel for support | |
| #docker-support | Support channel for our fleet of containers | |
| Support Room 1 | Voice channel for providing support | |
| Support Room 2 | Voice channel for providing support | |

### Community

| Name | Description | |
|---|---|---|
| #team | Channel for the members of the NLP Sandbox Team | |
| #developers | Channel for developers | |
| #users | Channel for users of the NLP Sandbox | |
| #data-sites | Channel for discussing topics related to Data Sites | |
| Team Hangout | Voice channel for the members of the NLP Sandbox Team | |
| Community Hangout | Voice channel open to all users | |

### NLP Sandbox Projects

| Name | Description | |
|---|---|---|
| #schemas | Channel for discussing schemas (e.g. OpenAPI, JSON Schemas) | |
| #tools | Channel for topics the NLP Tools | |
| #data-nodes | Channel for discussing NLP Sandbox Data Nodes | |
| #client | Channel for discussing the NLP Sandbox Client | |
| #deidentifier | Channel for discussing the NLP Sandbox PHI Deidentifier | |

### Code & Technology

| Name | Description | |
|---|---|---|
| #docker | Channel for discussion on Docker | |
| #python | Channel for discussion on Python | |
| #java | Channel for discussion on Java | |
| #javascript | Channel for discussion on JavaScript | |
| #other | Channel for discussion on other languages and technologies | |

## Users

### New users

New users who arrive on the server can only see the channels #welcome and #rules.
In #welcome, the user is prompted to accept the rules of the server by clicking
on the reaction emoticon :thumbsup:. Upon accepting the rules, the user is given
the role `verified` that gives him/her the ability to send messages and connect
to voice channels. At this point, the user can see most of the channels of the
server.

### Team members

The NLP Sandbox Team is the group of users who lead the development of the NLP
Sandbox. Team members have priviledges like being able to post announcements,
manage suggestions, stream video to this server. By default, team members can
not moderate the server without the role `moderator`.

### Moderators

Users with this role can moderate the server. This includes muting and banning
users who do not comply with the rules of the server. The motivation for creating
this role is to enable non-team members to moderate the server while not allowing
them to make announcements or make decisions on suggestions submitted by the
community.

### Community-dev

This role is given to users who contriute to the development of the NLP Sandbox.
At this time, receiving this role does not give special priviledges to the user.

## Suggestions

### Making suggestions

Users can make suggestions on how to improve our Discord server. This command
can be typed from any channel.

    !suggest <message>

The suggestion will then appear in the channel #suggestions where users can
vote for it.

### Managing suggestions

Admins and team members can manage suggestions.

    !approve <suggestion_number> [reason=No reason given]
    !deny <suggestion_number> [reason=No reason given]
    !consider <suggestion_number> [reason=No reason given]
    !implemented <suggestion_number> [reason=No reason given]

### References

- [Carl-bot Documentation - Suggestions](https://docs.carl.gg/utilities/suggestions/)



## asd

    !automod
    !automod drama logs
    !automod log logs

    !censor list
    !censor add <words...>

    !capslimit 70



    !rr selfdestruct <msg_id> <time>    !rr selfdestruct 458641514017587210 7d

    !info <@member>    Shows some interesting information about a member
    !serverinfo Shows some neat information about the server and its members

    !avatar nlp     Gives you a member's avatar in different formats
    !permissions nlp    Shows a member's permissions in a given channel. You cannot use this in private messages. If no member is given then the info returned will be yours.

    !about  Shows some interesting stats about the bot
    !wiki   Shows a link to carlbot's documentation

    !setnote <@member> <note>
    !notes  <@member>  Displays all of a member's notes.

    https://docs.carl.gg/moderation/moderation/#user-notes

    !rolediagnose <role>



    https://docs.carl.gg/utilities/highlights-pager/

## Channel #rules

### NLP Sandbox Discord Rules

Embed color: #94398d

Welcome to our Discord server. We hope you enjoy your stay!
Please make sure you read through and understand the following rules.

1. Follow [Discord's terms of service](https://discord.com/terms) and the law of your local area.
2. Do not share or encourage others to share any personal or identifiable information.
3. Please keep discussions relevant to the correct channels.
4. No Advertisements
5. Do not discuss piracy. Members violating this rule risk a permanent ban.
6. Be helpful to others.
7. We are all volunteers and commit to running this community in our free time. Any negative behavior towards staff will not be tolerated and will result in a Warning/Ban.
8. Do not abuse/insult other users. Any reports of this will be dealt with accordingly.
9. We are not google. Please do not expect users to search for the answer to your question if you haven't tried looking yourself first.
10. Do not provide or paste direct download links to executable files in public channels. If supporting or assisting another user, provide them with a link to the relevant vendor downloads page. If no download page is available, you may provide the direct link privately via a direct message to the user.
11. Please use only standard alphanumeric characters in your handle. Exceptions may be made at the discretion of the server team. Those not meeting this requirement will be warned. An unheeded warning will result in a ban.
No unsolicited direct PMs to staff for support unless otherwise stated.
12. No unsolicited direct PMs to staff for support unless otherwise stated.
13. No Solicitation
14. NSFW content is strictly forbidden.

Anyone found not to be following the rules, will be dealt with accordingly.

If you have any issues with the server or anyone on it, please report it to a member of staff with as much detail as possible. If we are unaware of an issue, we are unable to fix it.

### Synapse and NLP Tool Evaluation Support

Embed color: #94398d

The NLP Sandbox enables developers to submit their NLP Tools for continuous benchmarking. Learn more on [how to submit an NLP Tool for evaluation](https://www.synapse.org/nlpsandbox).

We are currently using [Synapse](https://www.synapse.org/) to manage the evaluation submissions. If you have any issues with a submission, please open a ticket on the [NLP Sandbox Synapse discussion forum](https://www.synapse.org/#!Synapse:syn22277123/discussion/default).


<!-- Definitions -->

[NLP Sandbox Discord Server Template]: https://discord.new/KyH9ZBWeD4x8