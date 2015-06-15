---
title: Fork adamcroom.com
author: Adam
layout: post
date:   2015-06-02 14:40:25
permalink: /2015/05/fork-adamcroom-com/
image: /uploads/2015/06/hitch.jpg
categories: Github, Indie Edtech
---

> It is one thing to mortify curiosity, another to conquer it.
>
> — Robert Louis Stevenson, *The Strange Case of Dr. Jekyll and Mr. Hyde*

Recently, I stumbled across [Kris Shaffer's][kris] project, [Open Music Theory][openmusictheory], which is a textbook hosted entirely on Github utilizing [Jekyll][jekyll], a "blog-aware, static site generator."" This means if someone else who teaches music theory wants in on the textbook, they can not only quickly create a website for it through Github (which is called "forking" a repository), but they can delete the chapters they don't want and modify the text of others to their taste. In fact, if they think they have found an error they want to suggest back to the original work, they can submit what is called a [pull request][pullrequest] which alerts the author and they can decide to accept the request. If they do, this will change the version.

This has really intruiging implications for open textbook adoption. Further, I've always thought there's something deeply romantic about the discourse that takes place around how a text is formed. It wasn't until recently that I learned, thanks to my good friend and Open Education Resource wizard, [Stacy Zemke][stacyzemke], that there's a little "Talk" tab where you can see conversations about Wikipedia articles.

![Kiss Wikipedia Article][kiss]

This really caught me off guard when I thought about how much I have interacted with Wikipedia's content over time but had never bothered to peel back the Wikipedia onion. How did I miss this? As an example, on the band's Kiss's page (see above), I can now read arguments about their genre. The official page says Hard Rock while others call it "Glam Rock" and "Glam Metal." Real serious stuff. Or how Anton Fick, whoever that is, was never in the band in May 1980 despite the Wiki page saying he was.

> Anton Fick was not an official member of Kiss in May 1980. That is a lie, a big lie. And it is an evil lie! --

Sorry Anton Fick. But, anyways, what was I talking about?

My point is that the presentation of information is one *layer* of the web. Discourse and social interaction is another layer. And before *any* of this can take place, there is the construction of the information, which is in turn disseminated; allowing for the opportunity for interaction to take place.

![Web Cycle][cycle]

I see a lot of folks looking at the presentation and the social aspects that come thereof, but (for whatever reason) I don't see a lot of people looking at how we structure the architecture that allows this to happen. What are the principles in which we can harness to build education technologies? To what standards do we hold companies (and even ourselves)? How can we begin to define **indie edtech**?

Continuing on the Wikipedia analogy, it's been interesting to look at the Federated Wiki project from the creator of the Wiki, Ward Cunningham, quoted from [Wired][wired]:

> I always felt bad that I owned all those pages,” he says. The central idea of a wiki — whether it’s driving Wikipedia or C2 — is that anyone can add or edit a page, but those pages all live on servers that someone else owns and controls.

[Mike Caulfield][holden] explained this really well at his [NWACC keynote][holdenkeynote]:

> In a traditional wiki, you have multiple people sharing a single server, and the server is the ultimate arbiter of what’s on the wiki. In a federated wiki, everyone has their own server which stores the records associated with them. But the meaning is made in your browser. Your browser pulls wiki records from all over the internet, and makes them look like they exist on a single server.

And while Mike is brilliantly thinking on this application to wikis, I'm thinking about everything as simple as my own personal website. How can I be the original owner, and thus the authority, on myself, but still lend the site's infrastructure and content?

I started poking around an article Kris wrote on [Hybrid Pedagogy][hybridpedagogy] called ["Push, Pull Fork: Github for Academics"][hybridpedgithub] and made an unexpected move this weekend. I exported my entire personal web site and blog, which runs on the Wordpress platform, and moved it to Jekyll (hosted on Github). This means, for the first time in five years, I'm working on a site that is 100% Wordpress free. The two different versions are below:

![adamcroom.com][newsite]

See the difference? :wink:

### Forkable

Honestly, this is the major reason I moved over to Github pages. If you want to take pieces of my site, or the *entire* site, you now can download this with the click of a button. On Github, you can *fork*, meaning you can make a copy of my repository and experiment with the site without actually affecting my site. Go ahead and [check out the repository][repo]!

This is something I wanted to explore mainly for my course site, [prpubs.us][prpubs], but tested out with my main domain for the first go around. And I'm pleasantly surprised with how much I've enjoyed the experience so far. It's one thing to put a Creative Commons license on a website (really, I think that's fantastic!), but that doesn't make the webpage any easier to recreate. In fact, if you decided to pull anything out of my currently CC-licensed course site, you'd be met with the resistance of broken code that doesn't work outside the ecosystem that I've created. Most people would spend more time than its worth.

<center>![Resist!][resist]</center>

<center>*Source: [API Evangelist][api]*</center>


### Backup and Security

The second big win for Github and Jekyll is that my entire site is cloned to my Dropbox account. I've got a certain level of peace of mind in knowing that should anything happen to my site, I can always quickly reupload the entire thing. I've ran across more instances recently where I'm frantically trying to update all my different Wordpress instances because of a large and necessary update and it feels good to veer a little further away from that. This is solved because while Wordpress utilizes dynamic code and relies on database calls, Jekyll is purely static on the server side. Additionally, there's no need to worry about someones Wordpress plugin code.

So am I now anti-Wordpress? Absolutely not. In fact, I still would argue its the easiest entry point into publishing on the open web. It's relatively user-friendly and gives you a lot of features that are great for a classroom, such as an intuitive admin panel and extreme flexibility. I'm just more interested moving beyond the presentation of information and coalescing around the idea of technology that has the necessary infrastructure for shareability and discussion.

### Some "how" info

I tried to keep as much tech out of this post as possible (I probably failed, sorry...). So rather than posting a tutorial for how to make this happen, I'll post some the links that helped me make the transition:

- [Push, Pull Fork: Github for Academics (Kris Shaffer, Hybrid Pedagogy)][hybridpedgithub]
- [How-to: Migrating Blog from WordPress to Jekyll, and Host on Github (Tomomi Imura)][migrate]
- [From Wordpress to Jekyll (Martin Van Aken)][fromwordpress]
- [Setting up a custom domain with GitHub Pages (Github)][customdomain]
- [Pointing My Domain at Hover to Github Pages (Steven D'Anna)][hover]
- [Using GitHub to Power A Web Project: How and Why (Audrey Watters)][audrey]
- [Jekyll (YouTube Playlist)][youtube]

<small>Cover Photo Credit: [Atlas Green][atlasgreen]</small>

[jekyll]: http://jekyllrb.com
[newsite]: /uploads/2015/06/newsite.gif
[prpubs]:http://prpubs.us
[kris]:https://twitter.com/krisshaffer
[openmusictheory]:http://openmusictheory.com/
[pullrequest]: http://oss-watch.ac.uk/resources/pullrequest
[stacyzemke]:https://twitter.com/slzemke
[kiss]: /uploads/2015/06/Kiss.jpg
[hybridpedagogy]:http://www.hybridpedagogy.com/
[hybridpedgithub]: http://www.hybridpedagogy.com/journal/push-pull-fork-github-for-academics/
[wired]: http://www.wired.com/2012/07/wiki-inventor/
[holden]: https://twitter.com/holden
[holdenkeynote]: http://hapgood.us/2014/11/06/federated-education-new-directions-in-digital-collaboration/
[resist]: /uploads/2015/06/developers-will-resist.gif
[api]: http://apievangelist.com/2012/10/08/developers-resist-api-evangelism/
[atlasgreen]: https://stocksnap.io/author/675
[migrate]: http://www.girliemac.com/blog/2013/12/27/wordpress-to-jekyll/
[fromwordpress]:http://blog.8thcolor.com/en/2014/05/migrate-from-wordpress/
[customdomain]:https://help.github.com/articles/setting-up-a-custom-domain-with-github-pages/
[hover]:http://stevendanna.com/2014/09/10/Hover-Domain-Pointing-To-Github-Pages/
[audrey]: [http://audreywatters.com/2013/07/07/how-to-run-your-site-on-github/]
[youtube]: https://www.youtube.com/playlist?list=PLWjCJDeWfDdfVEcLGAfdJn_HXyM4Y7_k-
[cycle]: /uploads/2015/06/cycle.jpg
[repo]: https://github.com/adamcroom/mediator
