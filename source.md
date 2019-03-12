# Liquid.qihl Staff README

Welcome to Liquid.qihl staff! This document contains information to help you as a staff member. Please read it!

## Contents

1. [Get Started/MISC](#get-startedmisc)  
2. [Channel Descriptions](#channel-descriptions)  
	2.1 [Info](#info)  
	2.2 [Staff](#staff)  
	2.3 [Development](#development)  
	2.4 [Chessbot](#chessbot)  
3. [Player Reports](#player-reports)  
	3.1 [Under Ranked](#under-ranked)  
	3.2 [Password Sharing](#password-sharing)  
	3.3 [Cheating](#cheating)  
	3.4 [Spam](#spam)  
	3.5 [Racism, Hate Speech, and Personal Attacks](#racism-hate-speech-and-personal-attacks)  
4. [Helping in `#help-desk`](#helping-in-help-desk)  

## Get Started/MISC

- Please read this and `#readme`
- Tag yourself with relevant roles if someone else hasn't already (e.g. `readme-dev`, `Caster`, `Rustaff`, etc). 
- Join the staff backup server. Link is in `#staff-readme` .
- The qihl Backend Sheet shows Staff Teams and leads, the complete Staff List, Staff Applications, Server Growth, tournament info, and other useful stuff. The link can be found from pinned posts of `#staff-serious`. Do not share the link!
- If you're doing something other than moderating, you can get on the qihl Trello board so you know what your team is working on. If you're a dev, everything should be in the gitlab repo. You can find Trello and Gitlab by asking i
- Do not `@staff`, `@moderators`, or similar unless there is a serious reason to do so (staff lobbies, minor player reports, memes, etc are NOT sufficient). 
- Gold count at the end of a game is basically meaningless to humans as it adds from selling units but does not subtract from buying them. 
- Enable developer mode in Discord settings under Appearence to right-click people and get their Discord ID. Then you can create `@`'s yourself (e.g. `<@93049613392568320>`). 

## Channel Descriptions

### Info

- `#readme`: Basic info in various languages. Read it!
- `#announcements` Server wide announcements. 
- `#help-desk` People as for help with stuff; please help them when you have time. 
- `#player-reports` Reports. React with a ✓ when you resolve one.
- `#stream-spam` qihl DAC streams.

### Staff

- `#staff-readme` This, which you should read.
- `#readme-changes` Discuss/request changes to a readme. 
- `#staff-heads` Team heads and Organizational Development team.  
- `#staff-serious` Serious server discussion. 
- `#staff-general` Non-serious staff discussion. 
- `#staff-bot` Admin commands. 
- `#staff-lobbies` Staff DAC games. 
- `#stats-graphics` Stats & Graphics team.
- `#outreach` Outreach team. 
- `#casters` Caster team. 
- `#tournament-org` Tournament Organization team. 
- `#bans` Post bans, warns, and blacklistings. 
- `#deduction` Track down cheaters and the like. 
- `#secret-vip-room` Some streamers and high-level players. 

### Development

- `#development` Software devs do magic. 
- `#gitlab` Bot posts updates for the repos. 

### Chessbot

- `#chessbot-commands` Users interact with Chessbot.
- `#chessbot-feedback-and-issues` Users reports problems with Chessbot. 
- `#suggestion-panel` High level users and staff discuss changes to the server. 

## Player Reports

Only those with Staff 2 role have banning rights. If you are Staff, ask a Staff 2 to ban a user for you. Ask Staff 2 if you are sure that they are in need of a ban, you can do a temporary ban with -mute and by removing all of their other roles by hand. Permaban is on the table for multiple offenses, but is evaluated case-by-case.

### Mutes
Use -mute command for temporary bans. It will message them the reason and they won't be able to post in any channel during the duration.  All moderators/staff can mute. The format is:

`-mute <@discord> "<reason>" <time>`
Example: `-mute @Deathkillsme "Because I can" 30m`

With time parameter you can do 1h for one hour, 1m for one minute, 1s for one second. You should also be able to combine them like 4h30m15s for four hours thrity minutes and fifteen seconds Minumum duration is 2 minutes (2m) and maximum duration is is 168 hours (1 week) (186h)

### Under Ranked

- 1 rank under: Light Warning
- 2 rank under: Light Warning
- 3 rank under: Use best judgment. Strong Warning or ban based on the circumstances. If ban, unban if they apologize.
- 4 rank under: Use best judgment. Strong Warning or ban based on the circumstances. If ban, unban if they apologize.
- 5+ ranks under: 7 day ban minimum.

### Password Sharing

Password sharing or inviting friends is often just ignorance to the rules. Most of these are a case-by-case basis.
- If you've decided they were just ignorant: Give a strong warning and a threat of ban if it happens in the future.
- If you've decided they were actively trying to get around the rules of the server: 7 day ban minimum.
- Ignore if the bot is down.

If you're unsure, judge based on the rank of the invited player relative to the rest of the lobby. (See Under Ranked rules)

### Cheating

Make sure, beyond reasonable doubt, they were cheating. Consult with other staff if needed. `!blacklist [steamid] [reason]` if they are found guilty. Never unban (`!unblacklist [steamid]`) unless they can PROVE their innocence.

### Spam

If someone is spamming, you can use the -mute command to mute them.

- Posting lobby passwords in non lobby channels 2 minute minimum
  - If they post several times increase by a few minutes
  - If they're just spamming every channel do few hours

### Racism, Hate Speech, and Personal Attacks

Mute by default (up to a week (168h)) but if it was beyond regular flaming and insults, permanent ban.

## Helping in `#help-desk`

- Telling them to read `#readme` is often the best solution. Maybe mention the specific part. 

- If someone is having trouble linking, ask them to make sure they are using the correct Discord/Steam in browser.
  - Ask them to open their browser in incognito mode and use that tab to log in to discord's web app and retry linking

- If bot says a new persons rank is `error`, check if they have a rank in game. If not, tell them to play enough games to have rank and then try again (5 games needed for a rank)

- If bot says someone someones Steam is already linked to another Discord account
	- Ask them to get on that Discord account and post in `#help-desk`. It's not a huge deal if they can't, but it's preferable.
	- Check if they've been banned.
		- You can get the Discord account currently linked to that Steam with `!getd [steamid]`. If this returns <@id number> instead of Discord username it is likely that they are trying to avoid bans.
			- Ask them for their steam64ID, they can use https://steamid.io to find it
		- Search #bans, #deduction and #staff-bot channels in discord search with the Discord ID and with the steam64ID
		- If `!getd` returned a valid discord account check that they don't have the `mute` role
	- If everything seems to be in order, use `!adminunlinksteam [steamid]` to unlink from the other Discord account.
	- If they are clearly avoiding bans, ban the new account as well. (For Staff 1 please mute them and ask Staff 2 to ban)
	- If in doubt ask help in `#staff-serious`

- If they ask about accessing higher lobbies tell them to use `!updateroles` in `#chessbot-commands3`
	- Don't use `!adminupdateroles` for them, because otherwise they don't learn
	- `!rank` command does not update roles anymore

- Lobbies auto-close after 15 minutes of no activity, 5 minutes of no activity when full, 60 minutes no matter what, or 10 join/leaves. 
