---- / ----
name: Git, GitHub, GitHub Pages

---- cover ----

## Git, GitHub, GitHub Pages
Jürgen Leschner @jldec
![](/images/imalive.png)

---- ----
background-image: /images/stallman2.png

## Back in the 80's

> Free software is software that respects your freedom and the social solidarity of your community.  
So it's free as in freedom.

#### Richard Stallman
- GNU 1983
- GPL 1989

---- ----
background-image: /images/linus1.png

# Then came Linus

> I'm doing a (free) operating system  
just a hobby  
won't be big and professional

#### Linux Kernel 1991


---- ----

> Good programmers worry about data structures  
 and their relationships.

![](/images/gitlogo.svg "width=400")
![](/images/linus2.jpeg "align=right width=297")
- Distributed Version Control
- Linus Torvalds
- April-December 2005

---- ----
background-image: /images/crew.jpg

# git demo
```diff
- git init
write some code
- git add
- git commit
write some more code
- git status
- git add
- git commit
- git log
```

---- ----
background-image: /images/github-website-2.png

# GitHub


---- ----
background-image: /images/octocat.png

# GitHub Demo

```diff
First create a new repo at github.com
- git remote add origin <github-repo-url>
- git push origin <branch>
Someone else on a different machine
- git clone <github-repo-url>
- git push
Hack on the code together
Use branches and pull requests to coordinate
```


---- ----
background-image: /images/cover.jpg

# GitHub Pages

Publish a website from your GitHub repo

---- ----
background-image: /images/icy.jpg


# GitHub Pages Demo

```diff
- git init
write code, git add, git commit
- git branch -m gh-pages
Push to new GitHub repo

Or...
Name your repo 'username.github.io'
```

---- ----
background-image: /images/jekyll.png

#### Jekyll is a blog-aware, static site generator written in Ruby

---- ----
background-image: /images/river.jpg

# Jekyll demo
```diff
- gem install jekyll
- jekyll new .
- jekyll serve
in _config.yml
  baseurl: /hamphack
  kramdown:
    input: GFM
- git add -A
git commit, push etc.
```

---- ----
background-image: /images/plane.jpg

# pub-server demo

```diff
- npm install -g pub-server
- git clone <github>/jldec/pub-sample-deck.git pub;
- cd pub; pub
edit markdown, watch http://localhost:3001/
- pub -O
- cd out
- git init
- git add, git commit, git branch -m gh-pages
push to a new repo on GitHub
```

---- ----
background-image: /images/sky.png

# Other Static Site Generators

https://www.staticgen.com/

e.g. Hugo, Hexo, Pelican, Brunch, Middleman, Docpad, Harp

---- ----

# Time for

![](/images/question.jpeg "width=800")

---- ----

# Thank You!

---- ----

# GitHub
- https://github.com/
- https://git-scm.com/
- https://help.github.com/

---- ----

# Command Line installers
- git command line utilities included with OSX since v10.9 (Mavericks)
- https://github.com/git-for-windows/git

---- ----

# GUI (OSX and Windows)
- https://desktop.github.com/

---- ----

# Online Git Tutorials and more

https://try.github.io

https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf

https://github.com/blog/2019-how-to-undo-almost-anything-with-git

https://ja.atlassian.com/dms/wac/images/landing/git/atlassian_git_cheatsheet.pdf

---- ----

# Read about GitHub Pages
- https://medium.com/@dfosco/git-for-designers-856c434716e#.9rnz1ulu7
- http://readwrite.com/2013/11/27/github-pages-explained

---- ----

# GitHub Pages links
- https://pages.github.com/
- https://help.github.com/categories/github-pages-basics/
- https://help.github.com/categories/github-pages-features/
- https://help.github.com/categories/github-pages-troubleshooting/
- https://guides.github.com/features/mastering-markdown/

---- ----

# Jekyll
- Static Site Generator written in Ruby
- Integrated into GitHub Pages
- http://jekyllrb.com
- https://github.com/jekyll/jekyll
- https://help.github.com/articles/configuring-jekyll/

---- ----

# Pub server
- Static Site Generator written in JavaScript
- Personal project - not GitHub sponsored or integrated
- https://github.com/jldec/pub-server
- https://jldec.github.io/pub-doc/

---- ----

# YouTube

- [2001 The Code: Story of Linux documentary](https://www.youtube.com/watch?v=XMm0HsmOTFI)
- [2012 Aalto Talk with Linus Torvalds](https://www.youtube.com/watch?v=MShbP3OpASA)
- [2007 Tech Talk: Linus Torvalds on git](https://www.youtube.com/watch?v=4XpnKHJAok8)
- [2008 Chris Wanstrath Interview at RailsConf](https://www.youtube.com/watch?v=-Reg0yhJw4s)
