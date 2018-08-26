---
layout: post
title: how to make the offline set-up work
---

Okay this is al little hard to explain but whatever.

1. Get the repository files from github by cloning it to the github software.
2. Next save it somehwere where you can easily find it.
3. Open the terminal and type 'cd ' and drag the folder behind it. hit enter and now you'll be in that directory. (aka nothing really happens)
4. 'bundle exec jekyll serve --livereload' hit enter
5. open browser and go to '[http://localhost:4000'](http://localhost:4000')

Now you can edit the website offline before pushing it.
6. Launch Atom.
- Open the cloned file (yes the whole file)
- maybe you have to 'built' the website first with a command. see [jekyll](https://jekyllrb.com/docs/usage/)
- now you can edit anything.
- Be sure to have an index page, otherwise the theme will be fucked up in the browser
7. Create a new article or post in the designated folder (the 'posts' folder with an underscore in front of it).
8. save it as YYYY-MM-DD-Blog-title-here.md
9. hit cmd-s everytime you want to see how the layout looks. (jekyll isn't on livereload for nothing).


# test2

ps.

To set up a repository at github:
1. Make new, come up with a name, can be changed later.
2. check the Read-me box thing.
3. Go to settings (you can change the name of the thing here)
4. Go to github pages and select the main branch and hit save
5. refresh page and the URL of your published site is there!
