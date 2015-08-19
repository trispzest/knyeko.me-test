---
layout: post
title: "If everyone used adblock"
excerpt: >

    Using adblock is almost a no-brain decision these days.
    What would happen to the Internet if all web-surfers realized its greatness?
    How can the companies that depend on advertising respond?
---
Using adblock is almost a no-brain decision these days.
It does so much to improve the web-surfing experience of browsers:

*   First and foremost: adblock blocks ads and uncovers content.
    Many websites (almost all news sites) today are rendered unreadable due to ads.
    They interrupt your navigation telling you to "Click to continue", inflate across the whole browser when you accidentally hover over them, scream noise at you in a video player with a broken mute button, randomly collapse/expand, etc.
    Their goal is to steal your focus and put it on their product.
    Your goal is to read the headlines, so you install adblock.

*   Adblock gives you speed.
    Surprisingly making 50 less HTTP calls does allow a page to load faster.
    Not being forced to watch the same movie trailer for the 16th time means you don't have to wait for it to buffer for the 16th time too.
    There's not a single ad in the world that speeds up a webpage.
    Installing adblock is cheaper than getting more bandwidth from an ISP.

*   Security.
    Suppose you want to watch a sports game, but you can't find it in your cable subscription because none of the teams playing are local.
    There are some **very illegal sites** which allow you to **illegally** stream such games.
    These **deplorable** sites are supported by advertisers whose morals are often even lower.
    You might be smart enough to dodge their phishing attempts, but your browser will left all alone to fight off whatever malicious code is present.
    If you install adblock and navigate to one of these dirty corners of the web **for security research purposes**, you're likely to come out unscathed.
    Since middle school I've been using adblock on regularly updated Windows (without the Norton virus).
    During this time I've never gotten a virus from web-browsing.
    (Of course, this is more due to the fact that I've **never** done anything illegal on the Internet.)

Given how overwhelmingly beneficial adblock is to web-browser, I'm stunned at how often I find people who don't have it.
I guess it's not being advertised enough.
Possibly the same forces keeping IE7 at a significant market share are in play as well.
I don't believe we'll be in this situation for long, and adblock will someday be popular enough that websites won't be able to afford to ignore it.
One of the following things will happen:

1.  Adblock continues to naturally grow in popularity.
    Eventually it reaches some critical point where a media outlet decides to run the story: "Could this free program bring down Google?"
    Boom! CNN, ABC, NBC, and CCTV find their pundits and scream it in everyone's ears.
    Maybe this is a bit too dramatic, but this is the media.

2.  A major browser builds in adblock to an update.
    Could this really happen? Definitely.
    This is how we eradicated pop-ups.
    Mozilla and Microsoft are already pushing Do Not Track into their browsers (with Google reluctantly following).
    Going from DNT to a basic adblock is a tiny jump.
    Firefox already [did it accidentally][accident] in their beta.
    Additionally, almost all browsers now feature a Reading Mode which oblitherates all parts of a website except the exact content to be read.

After that lengthy introduction we can finally raise the question: So what would the Internet look like if everyone used adblock?
Ask this to someone, and their first thoughts will seem dismal:

*   *Google is doomed.*
*   *The Internet relies on ads.* *Half of it can't survive with adblock.*
*   *All content would cost money!*

I don't see the above scenarios as likely.
Given a second thought, adblock has weaknesses.
In the rest of this post we'll look at some ways for content providers to circumvent adblock without losing their funding or going to paid tiers.
Many of the methods may seem obvious and almost all are already in the wild today.

### Apps

This first method might be the most prevalent solution.
Simply stated: There are no extensions for mobile apps, and therefore there is no adblock to worry about.
Developers decide exactly what is displayed in their apps.
Need an ad for funding? Done. There's nothing in the way.

Desktops are on the decline.
People love their phones, tablets, and all the apps on them.
Given a choice between a mobile website and a native app, everyone goes to the app.
Any speed and security that can be gained by using adblock in a browser is just outclassed by switching to native.
(Most mobile browsers don't even support extensions yet.)
Advertising from within apps is often enough to completely fund a company.
Some companies completely forgo having a web-app at all:
The average startup website is just a useless cookie-cutter jumbotron that links to its iOS and Android apps.

In the case of Google, Android can be seen as one giant app.
The Google Play phones are a direct connection to Google without any filters or blockers.
They can serve ads in searches and suggest restaurants in Google Now with ease.
Additionally, they get a cut out of all the ads running through their services on apps in the phone.

The app solution is far from perfect.
It is much cheaper to make a single web-app than to build/publish separate native apps on iOS, Android, Windows, OS X, Linux, etc.
For some business, it fundamentally doesn't make sense to have only native apps.
News sites and blogs need URLs in order to be shared and spread.
There is no equivalent to a hyperlink for apps.
The web needs solutions too.



[accident]: http://www.geek.com/apps/mozilla-just-built-an-ad-blocker-into-firefox-1631245/
[simple-detect]: http://stackoverflow.com/questions/4869154/how-to-detect-adblock-on-my-website