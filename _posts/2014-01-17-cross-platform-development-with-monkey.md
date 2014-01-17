---
layout: post
title:  "Cross platform development with Monkey-X"
date: 2014-01-17 21:00:00 +0000
tags: development
author: Richard

---

We are currently at the end of our first week of development on the mobile
version of Card Pirates. I thought it would be a good opportunity to quickly
introduce you to the platform we are using to develop the game and the reasons
why we chose it.

It was only a couple of weeks ago that I sat down with Chris and played Card
Pirates for the first time. If you haven't already played it, do it! It takes a very short amount of time to pick up the rules and the game is seriously fun! My first thought was "Why have you not developed this into a computer game yet!?" Chris is an extremely talented software developer, a mentor to myself and is understandably in high demand, so I offered to help out.
We discussed platform choices and decided the game would work best on mobile
devices. We wanted to target both iOS and Android, so the development platform
had to be cross-platform and allow us to develop the game in relatively short
amount of time (we set ourselves an ambitious deadline).

Introducing [Monkey-X](http://www.monkeycoder.co.nz)! Monkey is primarily a games
programming language (often extended further) which when compiled can be
translated into a number of platforms, including C++, C#, Java, Javascript and
ActionScript. More specifically the games can be run on iOS, XBox, Android,
HTML5 and Flash platforms with little to no code changes. For us this is a huge
win. There are number of technical challenges that we need to overcome in terms
of device resolutions and networking, but for the huge wins in
cross-platformability these are relatively minor.

We have ended the week with basic movement and a very crude title screen
(apologise for the programmer art). This may seem fairly insubstantial, but we
have a lot of base code for loading resources, managing screens, shuffling and
dealing cards, drawing the map, calculating valid moves and actually making
those moves on the game board. Phew.

We are certainly aiming for a more playable demo for next Friday, so watch out
for that! In the meantime you can log in to [our new twitter account](http://twitter.com/cardpirates) to get updates, or our [facebook page](https://www.facebook.com/cardpirates) - or you can keep coming back to this blog for more. Sign up to receive updates on the upcoming mobile/tablet app:

<form class='form-inline' role='form' action="http://thinkcodelearn.createsend.com/t/r/s/ttlylhk/" method="post">
  <div class='form-group'>
    <label class='sr-only' for="fieldName">Name</label>
    <input id="fieldName" name="cm-name" type="text" class='form-control' placeholder='Enter name'/>
  </div>
  <div class='form-group'>
    <label class='sr-only' for="fieldEmail">Email</label>
    <input id="fieldEmail" name="cm-ttlylhk-ttlylhk" class='form-control' type="email" required placeholder='Enter email'/>
  </div>
  <button type="submit" class='btn btn-success'>Get updates</button>
</form>

<p>
<br/>
Don't worry, we won't give your email address to anyone else. Looking forward to posting more information soon!
</p>
