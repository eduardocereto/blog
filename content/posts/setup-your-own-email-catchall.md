---
title: "Setup Your Own Email Catch-all"
date: 2020-05-20T12:17:40-07:00
draft: false
slug: "Create email aliases on the fly and for free with you custom domain" 
---

## The Problem

I've been using the same email for years, in fact I signed up in the first weeks after Gmail was launched and use the same email untill this day. During this period my email has been leaked 22 times (according to [HaveIBeenPwned](https://haveibeenpwned.com/)) and I have certainly earned a well estabilished spot on spammers hearts.

I wanted to get a clean slate but I can't simply stop using my email cold. I needed a transition plan. 

## The Gmail + Suffix Solution

Gmail has this cool feature that lets you add a `+` next to your username and that gives you a new email address still redirected to your inbox. It's nothing new, in fact it has [been available since 2008](https://gmail.googleblog.com/2008/03/2-hidden-ways-to-get-more-from-your.html). 

If you have myname@gmail.com when you register for a new site you can simply use myname+siteA@gmail.com and you'll receive the email in your inbox anyway. If you are forced to register on a website you know you wont ever come back you can use myname+trash@gmail.com and setup a filter to trash messages to this address forever. 

That is great and all but it has a few problems.

1. Some people get confused if I give them an address with a plus sign in the middle.
2. Some websites won't like that your email has a + and will complain it's invalid
3. Your email is still visible, and people can just remove the + suffix and get your real email. And in fact some people often do that, specially spammers.

## Temporary Email Solution

You'll find on the web some services that offer a temporary email. It works as a throw-away account that you can use once and forget forever. Some examples are [TemMail](https://temp-mail.org/en/), [EmailOnDeck](https://www.emailondeck.com/), [GuerillaMail](https://www.guerrillamail.com/), [FakeMail](https://www.fakemail.net/), there's many around.

Don't take me wrong these are great for sites you really don't trust. But I've had problems before with sites refusing these emails, because they know the domain is for a throwaway account. And companies want to build an email base, they want you to signup with your real email. 

Another problem is that these are generally designed to be ephemeral, so if you decide to login on that website again you might have a problem, and end up needing to signup again. 

## The personal catchall email

I already had my own domain. I wanted to use that to create as many aliases as I wanted on the fly without any configuration. 

Enter [Google Domains](https://domains.google.com/). If you transfer your hostname to Google they will allow you to setup Email Forwarding rules. And you can even forward `*@mydomain.com` to your Gmail address. 

That will act as a catchall for all emails. Now looking for jobs, don't just send your email everywhere, instead use a nice alias such as jobs@mydomain.com. Just met someone in an online forum that wants to challenge you for a game of Mario Kart? Ask them to contact you at MarioKartKing@mydomain.com.

There will be some extra configuration required if you want to be able to send emails through these addresses as well, and you will need to configure it one by one, or you can just answer using your normal email.