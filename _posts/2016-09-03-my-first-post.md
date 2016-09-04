---
layout: post
title: The blog is online!
description: First post after blog setup
keywords: Blog setup, Jekyll, Font Awesome, CSS, Hello World.
---

### Jekyll is not bad at all

Okay so I had my reservations about setting up a blog like this and using a technology stack I knew nothing about.
I was wrong! It took me 1 day to set this up ('am a noob at this stuff') on a windows system, plus I am kinda enjoying the whole markdown experience. Now all that's left to set up (or learn, I haven't explored it enough to know), is MathJax and code highlighting and then I'll be on my way to serious blogging.  I'll update this post later to describe the process for any other noob out there who might want this. Am still setting things up so some links may not work, bear with me till then :)

I'm just experimenting stuffs, no big deal!

### Update 1
It wasn't that simple after all. Turns out all those memes on internet about ghostly behaviour of websites are true after all. This monstrosity works fine on my localhost but when I deploy it to Github pages, it goes out of whack at some places. Like the social media icons. They are suppposed to appear under neath the header (and are apearing just fine on  my localhost), but are invisible! A mozilla inspect element test shows some wierd duplicacy error with the font-awsome css thingy. I'm gonna have to look into it. (oh and I had some issues deploying it but after seperating the source and deployement direcotry the whole thing workded as charm, looks like this [Heisway](https://github.com/heiswayi) guy had it figured out all along!)

### Fix for font-awesome CSS issue
So it turned out, the CSS was being reffered to via http:// protocal in the site and site in itself was https:// protocol. A simple swap in the header solved the issue and voila the site header shows social media icons now! Thank you [Amit Phulera](https://github.com/AmitPhulera) for pointing the issue and helping me in debugging it. Check the [commit](https://github.com/Joshi-Harsh/Joshi-Harsh-Source/commit/1096c49788f3dacefb1f3bee1dfde238ffd014c1) to see the juicy stuff. For those of you reading the blog, Amit is an awesome programmer and a leader in making. We used to work together back in college in IEEE Student Chapter, Google Student Community and as of late, the Microsoft Student Community. Thanks champ ;)

It's alive, finally. I'll upload repository page and resume later. Time to get back to analysing the data obtained from one of them simulation of pHash(it's almost done, wait for it). I'll blog about it later, stay tuned!

### Update 2
Added the fa fa-inbox element, now there is a link to email me via the soicial media icon pannel(I'mma pee all over this site, LOL) . I think I'm getting a hang of it. 

