---
layout: post.njk
title: Welcome to Faeriemachine 3.0!
description: An introduction to my 3.0 site, and talking about what I learned along the way!
date: 2025-07-11
author: Kian Quinn
tags:
  - 2025
  - Webdev
  - Technology
---

So, normally updates to my website don't usually come with blog posts talking about the updates themselves, but I figure that this is a big enough update to warrant such a post to be written. After having this website for over 3 years, I'm happy to say that I'm at a point where I actually feel satisfied with it, so naturally I want an excuse to talk about the site itself and all the things I learned while putting it together!

The project started on June 28th, just after publishing my last blog post to my old 2.0 layout. In that post, I mentioned feeling a sense of fear with learning Eleventy, something that I needed in order to create the website I envisioned truly having. I stated that, while I understood what was being taught in the online crash courses I was following along with, I felt a bit frustrated with understanding how to apply what I've learned to create the website I envisioned in my head.

Luckily, my issue was just with choosing the right tutorial for what I wanted to achieve, and I have to give my many thanks to FlamedFury for [their tutorial on creating static websites using 11ty and deploy to Neocities](https://flamedfury.com/guides/11ty-homepage-neocities/) for finally making things click in my head and helping me to understand what I was doing! I'm completely new to static site generators, using the terminal for coding, and doing anything with nunjucks, so before 3.0 I was coding all of my sites by hand. While I do greatly admire those who *do* completely handcode their sites, it was very tedious trying to make what I wanted work without the power of site generation, so I was very excited when I finally figured out how 11ty worked!

The site itself is mainly made up with several partials inside of a base nunjucks file that make up the website's layout, which includes the header, sidebars, and footer. I'm sure there's more efficient ways of doing this, and I may cringe at how I set up my layouts later on as I continue to learn how to use 11ty to it's fullest, but I think it works for what I want it to do. In the main section of this layout is all of the content that is surrounded in the middle by these partials, which I'm able to pass the content of my pages through! I'm also to use this same technique with my *Currently* section on my homepage, where it's an entirely separate file that I can edit myself. 

I've also learned how to build a fully-functioning blog with tags and dates, and my God, it's everything I could've dreamed of and so much more. I always kinda hated having articles and journal posts separated, but I felt like it wasn't a good look to have (often heavy-handed) seriously-written essays mixed in with my more personal and less proofread writings. But now, thanks to the magic of 11ty and nunjucks, I'm able to properly categorize and, by extension, filter everything using the tags in my blog post's front matter! 

But you know what's the most exciting part of all of this? I'm able to write my blog posts using just markdown and nothing else. I always hated, *hated* having to write down my blog posts in markdown in my Obsidian, and convert them to HTML afterwards, because I didn't have a way of being able to keep everything in markdown. But now, all I have to do is refer my layout to my base nunjucks file, and 11ty does the rest for me. This thing really does work like magic.

For optimal accessibility, I've also included a light/dark mode CSS toggle, as well as a play/stop gifs toggle! These were things I neglected to add to the site's past iterations, fearing that setting it up would've been too complicated. Luckily for me, they were actually pretty simple, and I have to give my thanks to [SwiftyHQ's CSS toggle guide](https://swiftyshq.neocities.org/blog/2025-06-29-Style-Switching-Creating-Themes/) and [Solaria's freezing gif tutorial](https://solaria.neocities.org/guides/gifpausetut) for helping me make sense of going about these things.

And hey, I finally finished my [links page](/links) after all these years! It's literally been in the works since 2023, but I could never figure out a good way of presenting it. This time though, I decided to just say 'fuck it' and use my base nunjucks file for it. Maybe I'll find another, better way of presenting my favourite links, but for now I'm okay with the way it looks and operates.
 
I also have a new little page dedicated to [my pets](/pets)! It's not anything too fancy by any means, but it's something I've been wanting to make since I started expanding my website back in 2023, so I figured that now would be a good time to put one together. 

The [about](/about) page also got a new look, and what was once the 'otherkin' page is now titled as the more general '[alterhuman](/alterhuman)' page! Not much to say about these two, they're relatively simple in terms of their designs, but are still worth a mention. 

<figure>
<img src="../../../img/blog/posts/ver3layoutsketch.jpg" width="70%" alt="Sketch of FaerieMachine's 3.0 layout">
<figcaption>The initial sketch I drew of what I wanted for FaerieMachine's 3.0 layout.</figcaption>
</figure>

I think my favourite little detail on the entire site is my Last.FM scrobbles tracker. [This is not my own code](https://prashant.me/development/2018/03/04/creating-a-web-widget-to-get-currently-playing-song-tracks-using-lastfm.html), but I did edit the CSS to look more like how I wanted it to, and part of this was the little spinning CD gif peaking out from behind the album cover. I had this idea planned back when I drew up my first initial sketches of 3.0's layout, and it was something I really wanted to try out. Admittedly, it took me a good bit of finagling to get it to look right on all screen sizes, but it works great and looks awesome! 

While this blog post is meant to celebrate the release of layout 3.0, I have to admit that it's not entirely done, and there's still a lot that I need to do before it's entirely finished. For starters, I'm wanting to recode my entire music shrine from the ground up, since I didn't originally build it with semantic HTML. My ~~super secret~~ James character shrine page is also due for some fixing up, and part of me just wants to start from scratch, or at least pick apart what I can keep and toss what I can't. I know that redoing these pages isn't going to be *that* difficult, and might even make things much easier in the longrun, but as it stands I'm starting to run a little bit thin on my energy for coding after everything I've worked on in the past few weeks. I'm also thinking of redoing my pages dedicated to my partner Ghost, and my friend Hyde, since both of them were built early into my coding journey and never really got any proper updates beyond some aesthetic changes. 

And yes, the thrift log is still down because I'm still very unhappy with my past iteration of it. I have it saved, so I won't delete any of the past entries I had on it. But I want it to look a hell of a lot better than it used to, because it looked painfully amateur compared to my current coding work.

The picture log page is also still something I'm trying to figure out, specifically with how I want everything presented. I don't even know if I want it to use my base layout and go for something entirely unique or not! I haven't forgotten about it, I just truly don't know what to do with it yet... 

I also have a bunch of future editions to the website to look out for, including (but not limited to); archive pages, a wishlist page, a recipes page, more shrines, and so, so much more. Even as I finish parts of the site, it will always be a work-in-progress, and I'm coming to terms with the fact that something as big as a personal website with all kinds of content on it is a huge task that doesn't need to be finished and polished right away. I'm learning the art of taking things one day, one step at a time. 

With all that said, I hope you all will enjoy what 3.0 has to offer! Next on my to-do list is to revamp my [art site](tri4ge.icu) to fit my current coding skills, as I've learned a ton from rebuilding this site, and want it to be the best it possibly can be.