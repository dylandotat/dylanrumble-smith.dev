+++
date = '2025-12-11T12:20:33Z'
draft = false
title = 'Planning and the First Two Days of B1 Resubmission'
+++

# Introduction

On the first day of my resubmission I opened up the Word file that had all my grades within it and I found out that I had poor grades. As I said in the [previous blog post](/b1/pre-resubmission-dev-diary/), I will need good grades to get into University.


# Day One

Most of this first day was spent ruminating of what to do to improve my work and, as a knock on effect, my grades. I needed to come up with an action plan to figure out what to do next based on the comments from the Word document and the comments from the Miro board.

By the end of the first lesson, I started setting up my Monday.com account.

During Lunch I was back to ruminating.

For the second lesson of the day, I added the first five tasks to my Monday.com board, and I also set up this website and started writing the first blog post.

# Day Two

In the first lesson of the day I spent my time writing out all the other tasks into Monday.com. Which I finished off by the end of the lesson.

For my second lesson I finished the rest of the two tasks I had remaining which was: write this blog post and clean up the Miro board.

## Website Technical Details

My website is using the [Hugo](https://gohugo.io) [Bear](https://themes.gohugo.io/themes/hugo-bearblog/) [theme](https://gohugo.io/about/features/#themes), it is being hosted in [Cloudflare’s](https://www.cloudflare.com) [static website](https://en.wikipedia.org/wiki/Static_web_page) hosting system called [Cloudflare Pages](https://pages.cloudflare.com).

On every [Git](https://git-scm.com) [push](https://git-scm.com/docs/git-push) to [GitHub](https://github.com), Cloudflare checks if there is any new changes in the [working directory](https://stackoverflow.com/questions/36201342/git-where-exactly-is-the-working-directory) and if so it rebuilds with website using the [hugo build](https://gohugo.io/commands/hugo_build/) terminal command and updates [Cloudflare’s](https://www.cloudflare.com/application-services/products/cdn/) [CDN](https://en.wikipedia.org/wiki/Content_delivery_network) using the [npx](https://docs.npmjs.com/cli/v8/commands/npx) [wrangler](https://www.npmjs.com/package/wrangler) [deploy](https://developers.cloudflare.com/workers/wrangler/commands/#deploy) command.

# Reflection

This is a good start to the B1 resubmission. I am feeling good about the resubmission so far and despite the grades that I got for B1, I am still confident for the resubmission. I think the bit I need to focus on is doing *at least* seven hours per day of College Work. I think the thing that is stopping me the most so far, and this is a challenge I need to overcome, is my schedule; as on Mondays I have work where I cannot do demanding college work such as writing a blog post, porting a UE5 project to Unity or researching.

# Screenshots

![Week one and two of my Monday.com board](/assets/11-1.png)

![Week two and three of my Monday.com board](/assets/11-2.png)

![Week three and four of my Monday.com board](/assets/11-3.png)

![Cloudflare Pages build settings for dylanrumble-smith.dev](/assets/11-4.png)

![This blog post opened in iA Writer](/assets/11-5.png)