---
title: "Future Posts"
draft: true
---

One of the things I realised working as a web developer is how the tools I use abstract significant aspects of the software and the foundation they are built on to the point where it is magical they are able to accomplish what they do. Don't get my wrong, I'm happy that these things are abstracted away from me. but I do feel as a software developer, I have a responsibility to my craft to have a slightly deeper understanding of the foundation my tools are built on.

<!--more-->

## Why not use a CMS provider?

When I first started learning web development in 2017, it was with the hope to transition careers from teaching into programming. I probably googled software jobs and looked at the listed tools or languages that were being asked for. I eventually ended up at Ruby on Rails, followed a tutorial on setting up Rails and eventually got the text I wrote in a template file (.erb?) to show up in the browser at localhost:3000. When I wanted to show that off to a friend, localhost:3000 was only working from the context of my laptop. It was not accessible from the web and learned that my application needed to be hosted. I continued to Google, followed another tutorial which led me to use Heroku to host my application. I was able to get my Rails application to run using Heroku, and my web application could be accessed like such: http://pet1ov3.herokuapp.com/#/home. Then I wanted a more friendly url and learned about domains and that I needed to purchase a domain name if the desired name was available. I then learned when a url is typed into the browser, my request is passed into the INTERnet, where essentially it is passed from server to server until a server that has access and knowledge of my application and heroku's server could satisfy my initial request and that request could be handled accordingly and a response could be sent back downstream.

Long story short here as the rabbit hole keeps on going is that the building blocks of the tools we use in programming are abstracted away from us. I often only worry about inputs and outputs with the libraries and tools I use. There is nothing wrong with not knowing the nitty gritty. Most users of software are not programmers and don't need to know the tools they use in great detail. But..... (almost always a but) as someone who prides themselves in craftmanship and producing quality work, I have a responsibility at the very lease to loosely know of the foundation of the tools are built upon. Why do I think this?

1. Creates a better mental model of the system you are working within
2. Builds clarity of an appropiate solution (solution more likely to be scoped accordingly)
3. Enables independence should anything go wrong with your system
4. Makes you a better programmer/developer/engineer

As an example, I'll try and use my previous example of what happens when a web request is made starting off with a problem. So that text that I was so happy my application could serve when accessing in the browser, I was no seeing a 500 error in the browser. Oh no! Now what? Where do I start? This is just a hypothetical but for some reason,  

In my day job as a web developer, a lot of the problems I solve are built upon frameworks that simplify building of the desired end product. In web development, you'll almost certainly hear of a frontend framework called React. A lot of web pages are built using React and it does simplify aspects to producing a web page once you understand React's API. Something I've noticed though that feels off when working with other "engineers", is how they only know how to do things under the context of React. It is embaressing to admit but for a long time I did not know how to run JavaScript outside of a browser terminal. I did not understand what Node was. I thought all JavaScript had to be run through a transpiler (webpack)I guess what I'm trying to get to is that I want to understand more deeply the building blocks of the tools that I use.

So with that all said, that's why I wanted to try to see what it takes the host my blog without a traditional blog provider. There is a lot more I want to experience, and I have a general understanding of how I think things should work. To keep it simple, I feel I should be confident in hosting my own personal website, especially working in the web development space for 6 years now at the time of this post. And after doing this, I'm definitely more confident in getting my website hosted but I understand that I do have a reliance on the service that is hosting it for me. But should anything go wrong with that service, I could switch that to another provider. And should all the providers for some reason stop working, I could try hosting the web server to my home router (if it gets to that point, what catastrophic event has happened!)

as we grow as individuals to be aware of the things that we have been on and understanding the function they play. Not everyone needs to know the ins and outs to that degree but there is so much value in understanding I want to be able to understand these things more deeply when necessary so I can better understand if the solutions I face are handled in the appropiate context. I want to understand some of the tradeoffs I make 
 am fortunate to be living in a time where others have done a lot of the heavy liftingas I program, to understand that  on the web anthere is so much that can be taken for granite (granted), the work I do for the company I work for profesionally is highly focused into a much narrower scope.

 generated a new url, particular URL, it would serve the html for that request and I followed the bare minimum to host writing React to generate some markup. I just needed to use the frontend framework to render some html it was Working within software, That way I have no reliance on a cms provider, and allow anyone visiting my website to just read the content I create. No paywalls, no registration, no ads. And for me, I get the chance to experience more of how to host a website on the web.

And here we are! The site you are seeing right now is being hosted on github pages. We are using Hugo as the CMS application which also handles the web requests. The theme is using Bootstrap 5 and is a fork of .

There are a lot of concepts and tools I've heard about but never took the time to look into understand. For starters, I mentioned the abbrevation CMS as in Content Management System. I've always heard profesionally that "oh some of the work you do is just a content management system". I've always wondered what was meant by that. One thing I've learned working profesionally in software is that terms we use when we communicate with others is often not standardized. What do I mean by that? In chemistry , What is a Content Management System, WordPress, Hugo, Markdown to name a few). But finally glad to have something to show for!

If anyone is interested in creating a custom hugo theme, this is the tutorial I followed

https://www.youtube.com/watch?v=wcMqrb3v2SM

https://github.com/ericmurphyxyz/hugo-starter-theme

I learn so that it can better benefit I can share my experience capture always enjoyed learning and building things, but I realise I never had a documented outlet that would capture, I wanted a way to capture I want to stand up a personal site where I can document my thoughts. The goal is to have a website where I can write blog posts about what is on my mind. I'd like to just write my thoughts into a file, if this was being published on the internet to be viewed in a browser, I would use something like Google Docs or Microsoft Word.

 What is a static site generator? In my own words (but did reference google to see my accuracy), is just a way of generating static html based of simple files. In my case I'd like to write blog post on my machine as files (in this case in a markdown (.md) file we would normally do 

https://gohugobrasil.netlify.app/variables/page/


When I started learning programming in 2017, I followed an intro to computer science course. It introduced a lot of basic computer science concepts and essentially we would write code into a file and executed that file to perform the desired task at hand. Coming from a PC gaming background, it was underwhelming the end output of the code we wrote, a lot of the time it seemed to be just text manipulation. Not to undersell how impressive actually the feat of modern computers are, the code we wrote was really simple.