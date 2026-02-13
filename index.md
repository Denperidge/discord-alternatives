# Discord Alternatives

## Why move from Discord?
- In October 2025, [Discord leaked 70,000 user government ID's](https://arstechnica.com/security/2025/10/discord-says-hackers-stole-government-ids-of-70000-users/)
    - In January 2026, they announced base functionality would be lost [unless you give them your government ID](https://discord.com/press-releases/discord-launches-teen-by-default-settings-globally)
    - In February 2026, Discord quietly revealed that [certain customers' face pictures would be processed by Persona](https://piunikaweb.com/2026/02/12/discord-uk-age-verification-persona-vendor-shift/); owned by Palantir's own Peter Thiel & [in the middle of a lawsuit for misusing the pictures they processed](https://www.isba.org/cases/illinois/appellate/2024/08/13/washingtonvpersonaidentitiesinc)
- It is a walking security violation; with [Spyware Watchdog](https://spyware.neocities.org/articles/discord) at the time reporting it logs which processes are running on your computer
- Discord [does not allow you to choose your own client](https://nitter.net/discord/status/1006178587731550208#m), even though [many great clients exist](https://github.com/Discord-Client-Encyclopedia-Management/Discord3rdparties) compared to their [heavy](https://www.geeksforgeeks.org/websites-apps/how-to-make-discord-use-less-cpu/) [official](https://www.reddit.com/r/discordapp/comments/1pej7l7/restart_on_excessive_memory_usage_experiment/) [app](https://www.maketecheasier.com/reduce-discords-high-ram-usage-windows/)
- Discord [will provide law enforcement with information](https://discord.com/safety/360044157931-working-with-law-enforcement) when asked; this combined with their US location and that country's [14-country wide spy treaty](https://tuta.com/blog/fourteen-eyes-countries), makes it a leaky wall of private information for some of the most corrupt governments in history.

## Alternatives
All of the options below (except for Discord itself) are *open-source*

| Platform | Discord-like | Who can see your message contents* | Self-hostable | Federated/connects to other servers | Choose your client | Other concerns |
| ----- | ----- | ----- | ---- | ----- | ----- | ----- |
| Discord | ✅ ...Yeah | ❌ Discord staff, USA government [and co](https://tuta.com/blog/fourteen-eyes-countries), your government, whoever hacks Discord | ❌ No | ❌ No |  ❌ Bannable offense | ❌ [See above](#why-move-from-discord) |
| [Stoat](https://stoat.chat/) | ✅ Yes | ❌ Instance owner, [your government](https://stoat.chat/legal/privacy) and whoever hacks the instance server, but [end-to-end encryption is planned](https://github.com/orgs/stoatchat/discussions/951) | ✅ Yes, has public instance | ❌ No | ⚠️ Theoretically | ✅ There are outdated reports of Stoat.chat being vibe coded. Tl;dr it's not. Not tl;dr: [GitHub discussion](https://github.com/orgs/stoatchat/discussions/1022#discussioncomment-15442591) |
| [Spacebar](https://spacebar.chat/) | ✅ Yes | ❌ Instance owner, your government(?) and whoever hacks the instance server, but [end-to-end encryption is planned](https://discord.com/channels/806142446094385153/1063046569244508190/1470874560512655493) | ✅ Yes, has public instance | ❌ No | ✅ By design: [any 3rd-party Discord client](https://github.com/Discord-Client-Encyclopedia-Management/Discord3rdparties) & most Discord bots | ✅ Really [tight privacy policy](https://discord.com/channels/806142446094385153/1063046569244508190/1470878658460778537) |
| [Signal](https://signal.org/) | ❌ No | ✅ Nobody | ⚠️ Theoretically yes, practically no | ❌ No | ⚠️ Yes, but options are limited | ⚠️ Requires phone number to create an account; but any phone-number related functionality can be turned off in settings easily
| [Matrix](https://matrix.org/) | ❌ No | ⚠️ If End-to-End Encryption is enabled, nobody. Otherwise, whoever hosts or hacks the homeserver(s) | ✅ Yes, but [public homeservers](https://servers.joinmatrix.org/) exist | ✅ Yes | ✅ Yes, by design | ⚠️ While really popular among developers, Matrix is still in its relative infancy. Expect a weird getting started experience |
| [Jami](https://jami.net/) | ❌ No | ✅ Nobody, messages aren't even stored on their servers | ✅ Mainly peer-to-peer. Extra features like username resolution can be self-hosted | Not applicable | ⚠️ Theoretically | |
[Quiet](https://tryquiet.org/) | ⚠️ Yes, but without voicecalls | ✅ Nobody, encrypted through tor | ✅ [Peer-to-peer](https://github.com/TryQuiet/quiet/wiki/Quiet-FAQ#does-quiet-use-servers-at-all) | Not applicable | ⚠️ Theoretically | ⚠️ Still in its infancy (doesn't support a lot of things like multiple communities, calling, deleting messages...) and hasn't been security audited yet |

***:** This does *not* include the people who you send messages to; this refers to who could see your messages **without your consent/intent on the server-side**. As such, it also does not include situations where your computer is compromised.

### Not considered
- Nostr/Flotilla - complicated usage, a bit too crypto heavy
- Mattermost, Rocket.chat, Zulip - aggressive pricing
- Kahla - website down, no downloadable release
- Adapt chat, common ground, 0xchat, dirc, Valour, Neremity & Strafe - Too little traction
- Retroshare - Only releases a new version every few years
- Mezon - AI
- Vocechat - freemium instead of free
- Peersuite - web browser only

## Contributing
Have any additional info or suggestions? Open an issue or pull request on [GitHub](https://github.com/Denperidge/discord-alternatives.git)
