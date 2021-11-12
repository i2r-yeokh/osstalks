---
marp: true
theme: gaia
paginate: true
---

# Introducing GitHub
**Open Source Things #OST**
Kheng Hui <yeokh@i2r.a-star.edu.sg>


---
# Overview

 - Introducing Git
   - Git vs GitHub
   - Browsing
   - Downloading
   - Using Git
 - Common Open-Source Projects
   - Firefox
   - Android
 - Community? What Community?
   - User Support
   - Improvements
   - Fixes (not just code!)
 - Getting Started

---

# Git vs GitHub

## Big difference!

**[Git][gitscm]** is a distributed version control system you can use to track your work and share it with others.

**[GitHub][github]** is a central location for hosting projects managed by Git. Other solutions exist, e.g. **[GitLab][gitlab]**, **[Gitea][gitea]**, **[Bonobo][bonobo]** etc.

[gitscm]: https://git-scm.com/
[github]: https://github.com/
[gitlab]: https://gitlab.com/
[gitea]: https://gitea.io/
[bonobo]: https://bonobogitserver.com/

---
# Browsing

 - Just visit the site... 

    ![main github page][pic1]

 - Or search for any open-source project online:

    ![another picture][pic2]

[pic1]: img/01-github.png
[pic2]: img/02-foxmob.png

You don't have to create an account if you don't want to :)

---
# Downloading

 - From any project page, you can download the archive of the project.

   ![download archive][pic3]

 - If you already use [git][gitscm], you can clone the project *repository*:

        git clone https://.... # requires no account
        git clone git@github.com:... # account with SSH key needed

Let me know if you need help with keys :)

[pic3]: img/03-dlcode.png
---
# Using Git

 - [Basic Intro][gitintro]
 - [Cheat Sheet][gitcheat]
 - Deep Dive (thanks, [GeekCampSG][geeksg]!)
 - *tl;dr*

        git clone $URL $TARGET
        cd $TARGET
        # ... make changes ...
        git add changes
        git commit -m "what i did"
        git push

[gitintro]: https://.../
[gitcheat]: https://.../
[geeksg]: https://geekcamp.sg/

---
# Common OSS projects

 - Firefox
 - Android
 - etc...
---
# What Community?

 - GitHub
   - Stars
   - Watches
   - Issues
 - Not GitHub
   - Socials
     - IRC (yes, that IRC)
     - Reddit
     - Discord 
   - StackOverflow
 - **Singapore**
   - HackerspaceSG ([web][hsgweb])([telegram][hsgtele])
   - FOSSASIA ([summit][faconf])([telegram][fatele])
   - Engineers.SG ([web][esgweb])([youtube][esgvid])
   - NUSHackers ([web][nhweb])([youtube][nhvid])([telegram][nhtele])


[hsgweb]: https://hackerspace.sg/
[hsgtele]: https://t.me/.../
[faconf]: https://.../
[fatele]: https://t.me/.../
[esgweb]: https://engineers.sg/
[esgvid]: https://youtube.com/.../
[nhweb]: https://.../
[nhvid]: https://youtube.com/.../
[nhtele]: https://t.me/.../

---
# User Support / Improvements / Fixes

- GitHub Issues
  - check the labels
- GitHub Watchlists
  - members get notified

---
# Acknowledgments

- HackerspaceSG
- FOSSASIA
- VSCode
- [marp][marp] for easy markdown to slides conversion ([intro][marpintro])
- and all of you :)

Slides available at my [github repo][mygh]

[marp]: https://marp.app/
[marpintro]: https://levelup.gitconnected.com/creating-professional-presentation-from-markdown-975c65211359
[mygh]: https://github.com/i2r-yeokh/osstalks/
