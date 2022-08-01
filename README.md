# Stage 0. Self-Study

### General
- [x] [Git Basics](https://github.com/kottans/frontend/blob/2022_UA/tasks/git-intro.md)
- [x] [Linux CLI and Networking](https://github.com/kottans/frontend/blob/2022_UA/tasks/linux-cli-http.md)
- [ ] [VCS (hello gitty), GitHub and Collaboration](https://github.com/kottans/frontend/blob/2022_UA/tasks/git-collaboration.md)
### Front-End Basics
- [ ] [Intro to HTML & CSS](https://github.com/kottans/frontend/blob/2022_UA/tasks/html-css-intro.md)
- [ ] [Responsive Web Design](https://github.com/kottans/frontend/blob/2022_UA/tasks/html-css-responsive.md)
- [ ] [HTML & CSS Practice](https://github.com/kottans/frontend/blob/2022_UA/tasks/html-css-popup.md)
- [ ] [JavaScript Basics](https://github.com/kottans/frontend/blob/2022_UA/tasks/js-basics.md)
- [ ] [Document Object Model](https://github.com/kottans/frontend/blob/2022_UA/tasks/js-dom.md) - practice
### Advanced Topics
- [ ] [Building a Tiny JS World (pre-OOP)](https://github.com/kottans/frontend/blob/2022_UA/tasks/js-pre-oop.md) - practice
- [ ] [Object oriented JS](https://github.com/kottans/frontend/blob/2022_UA/tasks/js-oop.md) - practice
- [ ] [OOP exercise](https://github.com/kottans/frontend/blob/2022_UA/tasks/js-post-oop.md) - practice
- [ ] [Offline Web Applications](https://github.com/kottans/frontend/blob/2022_UA/tasks/app-design-offline.md) - optional
- [ ] [Memory pair game](https://github.com/kottans/frontend/blob/2022_UA/tasks/memory-pair-game.md) — real project!
- [ ] [Website Performance Optimization](https://github.com/kottans/frontend/blob/2022_UA/tasks/app-design-performance.md) - optional
- [ ] [Friends App](https://github.com/kottans/frontend/blob/2022_UA/tasks/friends-app.md) - real project!

## Git Basics

Well, this is my very first message into the zero task of the zero stage, I'm very glad that I started this probably not easy, but interesting path.
Before this course, I already got acquainted with Git several times, but due to the fact that I did not use it in everyday life, I never fully mastered it. Although, thanks to it, I posted my first, lets call it parody on the Simpsons fan site on the network(in 2017), and even made my first site (hah, if you can call it that) for a customer (my colleague from the past work), and sold it for a symbolic $ 1, but that's already a completely different story ;)
So lets study further, wish me luck! Meow =^._.^= 
-- -


#### I decided to add some of the most basic git and github terms and commands, let my muscle and visual memory consolidate them once again.

**Git** is a version control system that can be downloaded from https://git-scm.com/downloads.

**Github** is a service that allows you to work with Git on the Internet, share your projects, edit other people's projects, and much more.
https://github.com.


<details>
  <summary>Main Git & Github commands:</summary>


**git init** - initialize the repository in the current directory

**git status** - show current status (use this in any unclear situation)

**git add <file_name>** - track file changes

**git add .** - track all files in the current directory

**git commit** - save changes in the commit (add a description of the commit through the code editor that will be open automatically, more suitable for long descriptions)

**git commit - m <commit desc>** - save changes in the commit and add a description of the commit (suitable for shorter descriptions)

**git commit -a -m <commit desc>** – this command includes git add and git commit in one line

**git branch** - show a list of branches

**git branch <branch_name>** - create a new branch with the name <branch_name>

**git branch -D <branch_name>** - delete branch <branch_name>

**git checkout <branch_name>** - switch to the last commit in branch <branch_name>

**git checkout -b <branch_name>** - create and switch to branch <branch_name>

**git merge <branch_name>** - merge the current branch with <branch_name>

**git log** - see the history of commits

**git log** --oneline - show the history of commits in one line

**git config** --global user.name - show user name

**git config** --global user.name <new_user> - change username

**git config** --global user.email - show the user's email address

**git config** --global user.email <new@mail.ua> - change the user's email address

**git push** - push current local commits to a remote repository

**git pull** - take changes from a remote repository to a local one

**git clone <link>** - clone a project from a remote repository

**code.** - open file in the directory using VSCode

</details>
  
-- -
  
<details>
  <summary>Udacity Version Control with Git</summary>

  ![udacity](https://github.com/Serge044/kottans-frontend/blob/main/task_git-intro/udacity.png)
  ![udacity](https://github.com/Serge044/kottans-frontend/blob/main/task_git-intro/udacity1.png)

</details>

-- -
  
[learngitbranching.js.org](https://learngitbranching.js.org/?locale=uk) - the killer feature of this resource is visualization. thanks to it, it is much easier and more pleasant to perceive information. a lot of useful information, can't single out anything because they all are main basic skills and I think they are all important
  
<details>
  <summary>learngitbranching</summary>

![learngitbranching.js.org](https://github.com/Serge044/kottans-frontend/blob/main/task_git-intro/learngitbranching.js.org.png)
![learngitbranching.js.org](https://github.com/Serge044/kottans-frontend/blob/main/task_git-intro/learngitbranching.js.org1.png)

</details>
  
-- -
  
**Communication using Markdown** - everything is well understood + interesting submission using GitHub bot, I will also save a few basic syntax expressions here:

<details>
  <summary>screenshot</summary>

![Communication using Markdown](https://github.com/Serge044/kottans-frontend/blob/main/task_git-intro/Communicating%20using%20Markdown.png)

</details>


# ```# Heading level 1```
###### ```###### Heading level 6```


**```**bold text**```**

  
*```*italic text*```*


```
- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item
```

> ```- [x] done```
> - [x] done

> ```- [ ] in progress```
> - [ ] in progress

> [link](https://en.wikipedia.org/wiki/Link) ```[<link_name>](<url>)```
  
> ![<kottans_logo>](https://github.com/Serge044/kottans-frontend/blob/main/task_git-intro/Kottans.png) ```![<img_name>](<url>)```

~~~
```
<add here some code>
```
~~~

<details>
  <summary>Dropdown:</summary>

```
<details>
  <summary>Dropdown:</summary>

  <add some dropdown text here>

</details>
  
```

</details>
  
> ```-- - long line```
> -- -
  
**TypingClub** - I can type quite well in Ukrainian, but in English still not so fast, so this is also a great sign to finally improve this skill and practice, in addition, this printing trainer is also quite beautiful visually!

-- -
  
And also a [link](https://stackoverflow.com/questions/729692/why-should-text-files-end-with-a-newline) to interesting explanations of why should text files end with a newline which I came across when encountering errors during a pool request.

-- -

## Linux CLI, and HTTP

<details>
  <summary>Linux Survival</summary>

  ![LinuxSurvival](https://github.com/Serge044/kottans-frontend/blob/main/task_linux_cli/LinuxSurvival0.png)
  ![LinuxSurvival](https://github.com/Serge044/kottans-frontend/blob/main/task_linux_cli/LinuxSurvival1.png)
  ![LinuxSurvival](https://github.com/Serge044/kottans-frontend/blob/main/task_linux_cli/LinuxSurvival2.png)
  ![LinuxSurvival](https://github.com/Serge044/kottans-frontend/blob/main/task_linux_cli/LinuxSurvival3.png)
  ![LinuxSurvival](https://github.com/Serge044/kottans-frontend/blob/main/task_linux_cli/LinuxSurvival4.png)

</details>

**Linux Survival** is preatty interesting resource with a rather old-fashioned design, but this, on the contrary, makes it more interesting visually. A good platform to learn theory and immediately practice, the only thing that I would like to change is that when you have to perform a task, it does not give you the opportunity to think for yourself, because even if you write the wrong command, the answer immediately appears to be correct, but I want to make one more try on my own ;)

**HTTP & HTTPS** is a very important and at the same time extensive topic. I especially liked the description of all types of errors. In the future(near future;)), it will be necessary to deal with this in more detail, because there is a lot of information, and it is quite difficult to catch everything at once.

**Configuring Linux Web Servers** - I will cover this topic a little later, but I will definitely dig in this direction, because I need it to create a smart home system with my personal settings.