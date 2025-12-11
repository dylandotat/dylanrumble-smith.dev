+++
date = '2025-12-10T14:38:12Z'
draft = false
title = 'Pre B1 Resubmission Dev Diary'
+++

# Introduction
Before the B1 submission started, I barely had any Dev Diary work in my original submission. The only dev diary I had was the commits I had in my repository, which as I found out when I got my B1 grades back, is not sufficient for any decent or good grades. This is a **major** problem, as I am trying to aim for good grades so I can get into university. This document is a recollection of what happened during this time from a mixture of:
- File Metadata
- GitHub Commits
- My *poor* memory

This will not be 100% accurate, but since I didn’t have a dev diary for this period of time, *something is better than nothing right?*

## Part I: The Original Research.

One of the reasons why the research uploaded to my B1 was so bare was because the original document that I had was deleted accidentally. To be honest, I don’t think this version of my research would of got me that much higher of a grade than the one that I had uploaded, but still, it was much more thorough than the one I uploaded in the end. If you were wondering how it got deleted, it was because I formatted my MacBook without having an extra copy in the cloud. And if you were wondering why I formatted my MacBook it is because it is a habit for me to reinstall the operating systems on my device to have a fresh slate to start from. Doing this, at least I found, makes me device perform like new, and it means that I can try new package management solutions such as [Brew](https://brew.sh) or [Nix](https://nixos.org).

As soon as I reformatted my MacBook I went to bed, as the Macintosh reinstallation takes a while and as soon as I got to college the next day, I realized the errors of my ways. Oops.

I think I should have backups in the future.

Anyways, from my memory, this old document had the following sections:
- Where I wanted to work in the future (job prospects)
- Universities that I looked at (in more detail than the Dev Diary I uploaded)
- A conclusion

Still not a lot by any means of the word, but a bit better than the one that I uploaded.

## Part II: GitHub Git Commits

In the [NHS Escape Room GitHub organization](https://github.com/NHSEscapeRoom) there are four repositories:

- NHSEscapeRoom
- NHSEscapeRoom-old
- Documentation
- Unity-CI-Templates (Which I’ll avoid talking about for the rest of this document as it is simply a fork of another repository which has the CI/CD scripts this repository was using.)

### NHSEscapeRoom-old

This is the most simple one to explain: it contained all the work that the old group (Matthew Jennings & Darkknight4303) did.  The only commit that I added was to make the repository use [Git LFS](https://git-lfs.com). With Git LFS it would make it easier (and quicker) for large files to be uploaded. This is due to Git LFS storing these “large files” in a separate location and instead of storing the files directly in the Git project’s work tree, it stores pointers to where the file exists on the separate location. This means that we can have gzip compression on these files and that we can push files larger than 100MiB to GitHub. This massively improves DX (Developer Experience) as it means that `git pull` times will be way less and it will ensure that `git clone` times will be **way** less.

### NHSEscapeRoom

This is where most of my time went into. This project is no where near complete, but I have setup most of the groundwork to build the project. I have some CI/CD pipelines to automatically build the project for Windows and MacOS. The CI/CD pipeline for testing the project is yet to be done and, if ran, will idle out.

This repository also has some stuff in the wiki for it. One of the two posts in the wiki is an explanation of the CI/CD system and the other post in the wiki is an explanation of how you setup Unity on a new system.

### Documentation

This is an empty repository which I am going to use to document the game and all its features. I am planning on either using something like [LaTeX](https://en.wikipedia.org/wiki/LaTeX) or [Hugo](https://en.wikipedia.org/wiki/Hugo_(software)) to create documentation.

## Part III: The Personal Statement

Before the project started, I started a personal statement using [examples of past student’s personal examples](https://universitycompare.com/personal-statement-examples/computer-science). My goal with these personal statements was not to match them one-to-one but instead to use them as a base and use them as something to write about.

In the end, I only managed to complete one of the three parts of the personal statement, that being the “Why do you want to study this course or subject” one.

## Part IV: The CV

Near the end of the time we had for B1, I created a CV. This CV was hastily made with the time I had left to make it and it used one of Microsoft Word’s built in templates. I was very unsure what to put on the CV and I made some spelling mistakes that the spell checker likely misconstrued as other words (e.g. immediate instead of intermediate). I also did not write enough for this, because, as I mentioned before, I was in a rush.

## Part V: LinkedIn

During Shonie’s lesson, the entire class made their own LinkedIn profiles. In that lesson we:

- Set a profile picture
- Set “skills” -- Which are the things we learnt from school and  work.
- Set where we work
- Connected with (friended) some lecturers.

## Conclusion

B1 did not go well. For the resubmission I have a lot of work to do and I can expect to, for that, work through Christmas and New Year’s Day.

I think the poor grades for B1 were a mix of:
-  Procrastination
-  Not having a proper task management system setup (because that generally does help me)

And, this is connected to the last point:
- Not knowing what to work on.