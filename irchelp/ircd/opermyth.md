# **Dispelling the myths of opers....**

* * *

**Ed. note:** This is a must-read for anybody who wants to know what an IRC operator ("oper") really can or will do, at least on networks like EFnet which have no services. As of 2001, there is now a pseudo-service on EFnet called ["CHANFIX"](chanfix.html) which contradicts some of the things said below in that it supports _de facto_ ownership of channels and limited oper intervention in takeovers, but the following document still represents the mainstream spirit of EFnet's philosophy. In addition, there is also another semi-official updated version at [EFnet.info](http://www.efnet.info/?module=docs&doc=6&type=html) which contains a lot more technical details. After reading this, you may also be interested in reading our other [ircd-related helpfiles](index.html). -Jolo 6/28/04 

**Date: **Thu, 30 Jul 1998 16:21:40-0700 (MST)  
**To:** operlist@the-project.org  
**From:** rayp@primenet.com (Ray Powers)  
**Subject:** The myths of opers....  

I've always wanted to write something like this.. Its half rant, half fact, so
bear with it. Hopefully it will be worth reading.

There's a lot of hate for opers for a lot of reasons. Some are directly oper
related (i.e. 99% of us are collossal assholes), some are directly user
related (i.e. 99% of you are raving lunatics), and some is just plain
misconceptions. I'd like to take a minute to talk about part three in hopes of
clearing a few things up. This will kind of be in a FAQ form, maybe you'll
like it, maybe not, but its worth a shot.

**Q: What can an oper on efnet do.**     

**A:** This is an **EXACT** list of what we can do: 

  1. /squit a server, separating it from the rest of the net 
  2. /die our server 
  3. /kill a user, this disconnects them from the server they are on 
  4. /kline a hostmask, this bans them from our server 
  5. /dline an ip, this bans them from our server, regardless of hostmask 
  6. See all invisible users on our server 
  7. Mass Msg/CTCP/notice a hostmask 
  8. Mass Msg/CTCP/notice a server 
  9. See and send Operwall/wallops notices 

That's it. We can see more server messages than you, but that's not the
point.. The point to be shown here is very simple, **none** of these things
have anything to do with channels. Which leads us to our next question.

**Q: What can opers **NOT** do, but keep being asked to anyways?**     

**A:** We can **NOT**: 

  1. Enter a channel that is +i or +k without being invited or having the key 
  2. See who is inside a +s channel 
  3. Op ourselves or op you on a channel (unless of course we are a channel op for that channel) 
  4. Tell you what XXXX's new nick is since they changed it to hide from you.  
[Ed. note: Actually an oper can follow nick changes but only on his own
server, but he won't invade that privacy for you because nobody likes a
stalker. :-]

  5. Deop someone for you on a channel (unless of course we are a channel op for that channel) 

Notice a trend, with the exception of 4, all of these are 100% channel
related. Efnet is made so that opers have **NO** power over channels, for
better or worse. If we don't help you with these requests, its not because we
won't, its because we are completely incapable doing so. On the other hand....

**Q: What can opers do, but won't?**     

**A:** This will be a bit differently done, because I figure I should explain why opers don't do these things, when they may normally make sense. 

  1. Why won't they kill somebody who has stolen your nick. 

Efnet has gone on the basis of nicks not being owned, which is why there is no
nickserv on Efnet. Of course we see opers kill all the time for nicks, though,
so it seems rather hypocrital, doesn't it?

An oper who kills for his nick will tell you its because the other person was
a bot, was juping his nick, or was imitating an oper. It may be true, but it
really comes down to the same feeling you get when your nick is taken "Hey!
that's my name! I don't want that person using my name!"

I personally do not kill for nicks. If someone takes my nick, they can have
it. Let them get my several hundred messages a day. :P But the problem with
the oper is this: How does an oper know that you are really the person that
uses that nick, or are you the guy that wants to nick jupe that nick out from
the real guy? Unless the oper knows you well, they don't.. And saying that
people generally tell the truth means you haven't been on efnet very long.

I would prefer to think I am one of the more well respected people on the net
and people still lie to me on a regular basis. So, the oper is stuck refusing
to help because he can't tell who is who. Remember this line of reasoning, its
going to be coming up a lot. :P

  2. Why won't they kill that guy nuking/smurfing/ping -f'ing me? 

This one is simple. There is no way to prove that somebody is doing any of
these things to you from an opers point of view. All logs are fakable, and the
oper has no way to firsthand prove it's happening. Your best bet in this
situation is to [log](/irchelp/misc/irclog.html) what you can and complain
loud and long to their ISPs.

  3. Why won't they help me take my channel back? 

[Ed. note: see note at the very top regarding [CHANFIX](chanfix.html) and how
it affects this question.]

There's a bunch of answers to this. First, it is popular opinion at efnet that
channels are not owned, and therefore, if you lose a channel, you should go
make another one. Notice I say popular instead of official, because efnet has
never had an "official" policy on much of anything.

But more and more you see opers killing for takeovers, so why are they helping
their channels and not yours.

Well, first, let's say your channel was taken over, and is now +smtinlk. How
exactly is the oper supposed to find out who is opd in the channel right now
to mass kill them? Even if they do get all the nicks, they have to somehow
manage to kill them all in one hit, or they'll all just op each other again
and it will be fruitless. Or worse, they could have it all set up, and some
other oper could kill them halfway through because they don't like masskills
and it would be all ruined.

Or, let's say the masskill goes off, then the channel is opless and generally
speaking, chaos begins. People start massnuking or flooding the channel to
clear it out, or just to be annoying. And there's still a 50/50 chance that
takeover people will get the channel back on a split and we'll have to try to
do it all over again.

If you're about to ask why they don't split their server, the answer is very
simple: We are not about to screw up roughly 30,000 peoples chatting for your
channel. Its rude. This of course is all based on the fact that we can prove
its taken over, as per the conversation about nicks, we often can't.

[Ed. note: make that >100,000 people as of mid-2002 and growing fast.]

  4. But.. its obvious they took it from me! The topic says "Ha ha, we took your channel Rick!" for Pete's sake! And there's only One op, so you can kill him and get the channel back immediately! 

This one is a bit more complex, but its really a personal call. That one op
could be a rampant smurfpup with a penis so tiny he has no choice but to
rampantly smurf and synflood anyone that gets in his way. This is popularly
known on irc as SPS, or Small Penis Syndrome. In this case, if the oper does
help you out, they could end up with their server being downed for a day or
two, and it really isn't worth it for your channel, no offense.

Keep in mind that this is all spoken from the perspective of someone who
**DOES** help with channels when possible, but understands greatly the reasons
not to, and judges each situation very carefully.

That's the gist of the information I was trying to get across. If you were
cluefull enough to get on operlist, a lot of this may be common knowledge to
you, but sometimes its good to step back and see why opers do what they do a
lot of the time.

Hoping this is of value to SOMEONE....

Ray Powers

Monkster/MimePunk/PrimeMonk/PacMonk/MtgMonk/Ihavefartoomanynickstonickjupe

* * *



[ [go back](/irchelp/) | [search](/irchelp/search_engine.cgi) |
[help](/irchelp/help.html) | [send email](/irchelp/mail.cgi) ]

[all pages (C) IRCHELP.ORG or original authors](/irchelp/credit.html)

