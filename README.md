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

| Name | Description | |
|---|---|---|
| team | Members of the NLP Sandbox Team |   |
| community-dev | Users who contribute to the development of the NLP Sandbox |   |
| bots | Bots |   |
| @everyone | Everyone | |

### Support and moderation roles

| Name | Description | |
|---|---|---|
| admin | Administrator of the server |   |
| moderator | Moderator of the server |   |
| support-room-1 | Allows the user to join the voice channel Support Room 1 |   |
| support-room-2 | Allows the user to join the voice channel Support Room 2 |   |
| verified | User who has accepted the server rules |   |
| muted | Prevent the user from sending messages |   |

## Categories and Channels

### Information Channels

| Name | Description | |
|---|---|---|
| #welcome | Welcome channel | |
| #rules | Rules of this server |   |
| #announcements | NLP Sandbox announcements |  |
| #blog | News, articles, tutorials on topics related to this project |  |
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
Sandbox. Team members have priviledges like being able to moderate the server,
post announcements, manage suggestions, stream video to this server.

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

<!-- Definitions -->

[NLP Sandbox Discord Server Template]: https://discord.new/KyH9ZBWeD4x8