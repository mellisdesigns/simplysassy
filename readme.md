# Simply Sassy - A Basic Guide to Understanding SASS, SCSS and CSS

This quick talk is intended to get you up and running a sass compiler so you can get down and dirty with sass.

### Getting Started

##### But Mitch, do I have everything I need?
* iTerm2 - A terminal replacement for OSX. After installing you can open iTerm from your applications directory.

  https://www.iterm2.com/downloads.html

* Install GIT - You all should have this installed already, but if you don't you can download from http://git-scm.com/download/mac
```
git --version
// output -> git version 2.5.1
```

* Cloning our Empty Sass Project Directory

  I have created an empty workspace for us to play around in, so lets use git to clone it to an empty directory on our local machine.
  ```
  git clone [add url here]
  ```

* Sass Compiler

  Installing sass is easy on OSX. Go to your terminal window and paste this command in. You will have to enter your computer password to install.
```
$ sudo gem install sass
$ sass --version
// output -> Sass 3.4.18 (Selective Steve)
```

##### Watcher Man, it's time to watch!

How cool would it be if every time we made a change to our sass file, it would recompile into the css file read by the browser?

```
sass --watch scss/app.scss:css/app.css
```

##### So what are you actually going to talk about?
* What is SASS
* Basic Structure and Concept
* How to watch and compile
* What does compile actually do

##### So what is some cool stuff to do with sass?
http://sass-lang.com/
