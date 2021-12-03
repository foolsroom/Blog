---
title: "Devlog"
date: 2021-08-16T15:31:12-04:00
slug: ""
description: ""
keywords: []
draft: false
tags: ["game-dev", "devlog"]
math: false
toc: true
---
## Aug 16, 2021
So I've been working on a game for the past few weeks. I wanted a place where I could put my thoughts and other things regarding it, so I've created this simple website. Well, I say simple, but I actually spent so long messing around with it and configuring random stuff. Anyways, it's very likely that there will only ever be a few people who ever see this. So if you're reading this, hello and welcome. This is just going to be a very informal place where I share my thoughts and progress on this game's development. I made this because I personally really like reading other game developers' thoughts and posts like these. So maybe someone out there might get something out of this.

So today is Monday, August 16, 2021. I began working on this game on July 8, 2021, so it's been a little over a month since I began. The game idea is pretty lame. It's just a twin stick shooter roguelite game. There's no special mechanics or interesting gimmicks or anything that would make a player want to play my game over any of the other high quality twin stick shooters out there. I gave some thought into what sort of mechanics might be interesting and unique for this game, but couldn't really come up with anything decent. Maybe I'll keep trying to come up with something, but there's a high chance I won't change anything.

The main goal for this game is primarily to just finish and release a project. That seems to be something indie developers say a lot. For me, I've worked on various smaller projects in the past. The maximum time I spent on a single game was probably a little over one month. None of them were really intended to be played by anyone other than my friends. But around a year ago, I decided I wanted to try and make a "real" commerical game. Since then, I've hopped from project to project, always overscoping, and never ending up actually making anything. My previous project before this one was going to be a tower defense kind of game which was going to be really small. But scope creep and overestimating my abilities came into play again, and I ended up scrapping it as well. As a result, I really don't want to throw away yet another project. I will do my best to see this project through to the finish, regardless of what I must do to achieve it. 

I made a bet with a friend that I would release this game before October 30th. At this point in development, I am not sure whether or not that goal is totally feasible, but I will still try my best to finish by then. I don't have a ton of time to devote to development, but hopefully an hour or two a day will be enough over time. Anyways, let's talk about the game now.

So far, I have most of the basic stuff implemented already: health, ammo, exp, some upgrades, and some enemies. I'm currently working on the first boss, which is literally just a giant circle. As a part of limiting the scope, I was going to make all of the enemies and the player just shapes. Then, I wouldn't have to spend a lot of time drawing or animating them. It turned out that the shapes were really boring, so I just gave them all faces, hoping that it would spice it up at least a little bit. I think it's a good addition that also doesn't take a bunch of effort.

Anyways, I really have to think about the direction I want to take this game towards. Currently, it's pretty boring, and my defeatist mentality is telling me that nothing I will add will make it any better. Maybe it'll end up just being a boring mess. I guess we'll see in a couple months.

I'll update this post every once in a while with progress updates and stuff like that. But I guess that's it for today.

## Aug 23, 2021
It's been about a week since the previous update, so I guess I'll write another one. I haven't had as much time recently to work on the game, so progress isn't going too quickly. Anyways, I've been primarily working on the upgrades system and implementing individual uppgrades. The hope with the upgrade system is that it will provide interesting builds that people can try out in different runs that play differently. Whether or not that will actually happen is another story. At the very least, maybe they'll provide a little bit of thought and variation to runs.

Sorry I don't have something more substantial, but that's pretty much all I have for this update. I guess I'll see you guys in another week or so. With hopefully some more progress and stuff to report on.

## Sep 18, 2021
Oh no. It's been very long since the previous update. The reason for this is because I really haven't been working on the game too much for the past while. I squeeze in a little progress here and there, but I have other responsibilities at the moment which is taking up a significant amount of time. Anyways, I have made a design decision that might hopefully alleviate some of the negative feelings I've had towards the game, which was to drastically zoom out the camera. It might not seem like that big of a deal, but I feel like it was a great change. Previously, the game felt rather cramped, and I think that limited the potential enemy designs that were possible. After widening the playing field, I believe I will have much more freedom in creating enemies.

Other than that, I've been working on some special activated ability for the player, and brainstorming content that could be added. I'm considering adding multiple unlockable characters, as that might add some much needed variety. But at the same time, I've been programming this game with the mindset that there would only be one playable character, so adding other ones might prove to be a significant challenge. I'll have to investigate to see if that sort of thing would be feasible.

Regarding the October 31st deadline that I mentioned earlier, I think that the worst possible case has happened, which is the case where I completely disregard the deadline. There really is no consequence for missing it, and I have no reason to meet it, except to prove to myself that I could do it (I can't). At this point, there is practically no chance that I finish the game by October 31st unless I drastically cut pretty much everything from the game, but then I would have a barebones shell of a game that I wouldn't even be happy with. I guess I'll set a new personal deadline of December 31st, since I think it might be feasible to finish the game before then. Of course, I might just completely disregard this new deadline as well in the future, but having some arbitrary personal deadline is probably better than having nothing at all.

Anyways, it is extremely late and I am extremely tired, so I guess that's all for this update. Hopefully I'll bring some good news in my next one, but I'm not crossing any fingers.

## October 31, 2021
So I have been working on more upgrade designs and implementations. Since the previous update, I have decided to completely ditch my old upgrade system in favor of a new one that I think would make the game more enjoyable. Previously, the idea was that each upgrade was significant and unique. In other words, you could only obtain any given upgrade once, and that upgrade would theoretically have a decently significant impact on your stats or abilities or the game. However, this made me feel very limited in my options for potential upgrade designs.

The resolution was to rework it into an upgrade system in which you can obtain multiple of the same upgrade, with stacking benefits. I feel this allowed me to create better and more balanced upgrade effects, and enabled a wider variety of upgrade types.

Anyways, with this change came along a significant amount of work reworking and creating code for these systems. What is left now is just implementation of a bunch of different upgrade effects. That's probably what I'll be working on for a while. After that, it's probably time to add more content like enemy types.

## December 3, 2021
Progress has been going slower than expected as a result of various things happening in life. Over the past month or so, I've just been working on implementing some more upgrades. Here is a little video of what some of the upgrades looks like at the moment:

{{<video src="https://i.imgur.com/Hzw3gbq.mp4">}}

I'm going to keep working on this stuff for a while. This is taking a bit longer than expected.