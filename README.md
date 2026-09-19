Note to developers:

This is for the game torn.com.  In game, I am known as Baldr [1847600].  You probably already know me and my guide, or you wouldn't be reading this.

I have a very well known guide for new players.  https://www.torn.com/forums.php#!p=threads&f=61&t=16034448&b=0&a=0

As part of that guide, I have a list of good targets to use for leveling up.

All of these targets are low stats (under 1,000 total) but relatively high level, because higher levels give better experience.  And they are all inactive targets, at least when I add them.

I have those targets here in .json format.  Anyone is welcome to use those in any way, but I strongly recommend you design your software to refresh your data from my github.

The targets change over time.

It doesn't happen often, but several times since I first created the target list, I have gone looking for new targets, expanding it and making it much bigger.   And sometimes, targets have to be removed because they are active again.  For one thing, it's not fair to make a target of someone trying to play.  For another, they will train, so their stats will go up, and they will no longer be the soft squishy target that the newbies are expecting.  So if you grab these targets from my github, with some system to update regularly, it gives me a way to make updates.  Otherwise, your tool will be out of date soon at some point.

I would like anyone using this list to watch the targets "last active" date and simply not display them if it is less than 150 days ago.  I do remove them when I know they have been active, but that takes some time, and a program can easily watch for that so they stop getting attacked soon after they log in again.

In addition, I will have a file named "info.html" in my github.  It is very short, in html format, and I would ask that anyone building a tool using these targets display it.  

Shoutout to oraN [1778676] for his tool, and help financing this last round of updates.

And a shoutout to Glasnost [1844049], who also helped with financing, as well as using his FFScouter tool to give me a list of high quality potential targets to have spied.  That save a lot of work, and a lot of money.
