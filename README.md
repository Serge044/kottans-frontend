# Stage 0. Self-Study

### General

- [x] [Git Basics](https://github.com/kottans/frontend/blob/2022_UA/tasks/git-intro.md)
- [x] [Linux CLI and Networking](https://github.com/kottans/frontend/blob/2022_UA/tasks/linux-cli-http.md)
- [x] [VCS (hello gitty), GitHub and Collaboration](https://github.com/kottans/frontend/blob/2022_UA/tasks/git-collaboration.md)

### Front-End Basics

- [x] [Intro to HTML & CSS](https://github.com/kottans/frontend/blob/2022_UA/tasks/html-css-intro.md)
- [x] [Responsive Web Design](https://github.com/kottans/frontend/blob/2022_UA/tasks/html-css-responsive.md)
- [x] [HTML & CSS Practice](https://github.com/kottans/frontend/blob/2022_UA/tasks/html-css-popup.md)
- [x] [JavaScript Basics](https://github.com/kottans/frontend/blob/2022_UA/tasks/js-basics.md)
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
So lets study further, wish me luck! Meow =^.\_.^=

---

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

---

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

# `# Heading level 1`

###### `###### Heading level 6`

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

> `- [x] done`
>
> - [x] done

> `- [ ] in progress`
>
> - [ ] in progress

> [link](https://en.wikipedia.org/wiki/Link) `[<link_name>](<url>)`

> ![<kottans_logo>](https://github.com/Serge044/kottans-frontend/blob/main/task_git-intro/Kottans.png) `![<img_name>](<url>)`

````
```
<add here some code>
```
````

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

---

And also a [link](https://stackoverflow.com/questions/729692/why-should-text-files-end-with-a-newline) to interesting explanations of why should text files end with a newline which I came across when encountering errors during a pool request.

---

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

---

## Git Collaboration

**_[Introduction to Git and GitHub](https://www.coursera.org/learn/introduction-git-github) (week 3 and 4)_** -
I especially liked the explanation of the topic Tracking Issues (Week 4, Managing Projects), and in general quite good explanations and examples, I liked this course.

<details>
  <summary>screenshots</summary>

![coursera_week3](https://github.com/Serge044/kottans-frontend/blob/main/task_git_collaboration/coursera_week3.png)
![coursera_week4](https://github.com/Serge044/kottans-frontend/blob/main/task_git_collaboration/coursera_week4.png)

</details>

**_[learngitbranching.js.org](https://learngitbranching.js.org/?locale=uk)_** - as I said earlier (in Git Basics), this is a pretty good resource with cool visualization, although this time, despite some experience, it was more difficult.
And I also found an error in the word during the translation into Ukrainian (yes, I know that it is definitely not the most important thing, but I wanted to correct it first, and secondly to practice with pool requests), so I sent a request for a change with a detailed description of what and why I want to change. If for the time of the course will be answered, I will add an update to this topic.

upd. In just half a day, my pool request was approved and this small change is now in production. It's cool when authors actively support their products. Let's move on!

<details>
  <summary>screenshots</summary>

![learngitbranching.js.org](https://github.com/Serge044/kottans-frontend/blob/main/task_git_collaboration/learngitbranching.js.org.png)
![learngitbranching.js.org](https://github.com/Serge044/kottans-frontend/blob/main/task_git_collaboration/learngitbranching.js.org_2.png)
![pull-request](https://github.com/Serge044/kottans-frontend/blob/main/task_git_collaboration/pull-request.png)
![merged_pull-request](https://github.com/Serge044/kottans-frontend/blob/main/task_git_collaboration/merged_pull-request.png)

</details>

**_[An Introduction to Git and GitHub by Brian Yu (CS50 course)](https://www.youtube.com/watch?v=MJUJ4wbFm_A&ab_channel=CS50)_** -
in general, everything that was shown in the video I had already done personally at the previous stages, but it was still not superfluous to repeat the basics once again, especially since it is CS50, it can even be watched simply as a TV series ;)

**_[Oh shit, git!](https://ohshitgit.com/)_** - the description of the problems is really top! (in the English version)
Perhaps this is how the material should be presented, because it is fun, it is memorable, and you want to show it to other people, especially those who are just starting to learn git.
The only thing that was a little disappointing was the translation into Ukrainian, as for me there are too many identical swear words that could be replaced with more funny swear words, but again, this is my personal thought, besides, there is a version without swears ;)

**_[Flight rules for git](https://github.com/k88hudson/git-flight-rules)_** - great git cheat sheet for sure for any situation, just keep this link here for convenience.

And video ['Creating a Simple Github Pull Request'](https://www.youtube.com/watch?v=rgbCcBNZcdQ&ab_channel=JakeVanderplas) which explains as simply and clearly as possible how to make a pull request if you find an error.

---

## Intro to HTML & CSS

**_[Intro to HTML & CSS (Eng)](https://www.coursera.org/learn/html-css-javascript-for-web-developers)_** - I liked the explanation of the basic terms (what is HTML, CSS, JS..), in simple words and quite clearly.
Also discovered how to add a 'ban' on word spacing or how to add multiple spaces in a row, and some [special characters](https://www.w3schools.com/html/html_entities.asp) such as <> ”” (c) &.

A good [site](https://validator.w3.org/#validate_by_input) for testing are my html tags correct or not.

Learned about ':nth-child CSS', will see how useful it will be in practice.

[Lecture 17, Part 1: Conflict Resolution](https://www.coursera.org/learn/html-css-javascript-for-web-developers/lecture/WDDCB/lecture-17-part-1-conflict-resolution) - really cool explanation.

Lecture 22, [Part 1](https://www.coursera.org/learn/html-css-javascript-for-web-developers/lecture/AtyKw/lecture-22-part-1-relative-and-absolute-element-positioning), [Part 2](https://www.coursera.org/learn/html-css-javascript-for-web-developers/lecture/YWC0N/lecture-22-part-2-relative-and-absolute-element-positioning): Relative and Absolute Element Positioning - important stuff.

`<div>` is short for “division” or a container that divides the page into sections. Never thought about this abbreviation, now I know ;)

- Paragraphs (`<p>`) contain a block of plain text.
- `<span>` contains short pieces of text or other HTML. They are used to separate small pieces of content that are on the same line as other content.

<details>
  <summary>screens</summary>

![coursera_week1](https://github.com/Serge044/kottans-frontend/blob/main/task_html_css_intro/coursera_week1.png)
![coursera_week2](https://github.com/Serge044/kottans-frontend/blob/main/task_html_css_intro/coursera_week2.png)

</details>

<br>

**_[Learn HTML(Eng)](https://www.codecademy.com/learn/learn-html)_** - it's cool that you can read the theory and immediately practice and see the result, this is probably my favorite training format.

The most difficult thing was to complete the task [Ordered Lists](https://www.codecademy.com/courses/learn-html/lessons/intro-to-html/exercises/ordered-lists-html), because I had to write russia with a capital letter, I hope that temporary phenomenon and it will be fixed soon ;)

alt='' - alternative text, brings meaning to the images on our sites.

Also a good explanation about the tables, never come across that before so it was interesting.

<details>
  <summary>screens</summary>

![learn_html](https://github.com/Serge044/kottans-frontend/blob/main/task_html_css_intro/codecademy%20html%26css.png)

</details>

<br>

**_[Learn CSS(Eng)](https://www.codecademy.com/learn/learn-css)_** - good explanations about positioning, I am sure that I will return to them in future practice.

<details>
  <summary>screens</summary>

![learn_css](https://github.com/Serge044/kottans-frontend/blob/main/task_html_css_intro/codecademy%20html%26css.png)
![TheBoxModel](https://github.com/Serge044/kottans-frontend/blob/main/task_html_css_intro/TheBoxModel.png)
![ActualRenderedWidth](https://github.com/Serge044/kottans-frontend/blob/main/task_html_css_intro/ActualRenderedWidth.png)
![VerticalMarginCollapse](https://github.com/Serge044/kottans-frontend/blob/main/task_html_css_intro/VerticalMarginCollapse.png)

</details>

<br>

**_[Can't Unsee](https://cantunsee.space/)_** - a cool thing to train your sense of pixel perfect and generally look at good visual examples.

<details>
  <summary>screen</summary>

![CantUnsee](https://github.com/Serge044/kottans-frontend/blob/main/task_html_css_intro/CantUnsee.png)

</details>

---

## Responsive Web Design

**_[FLEXBOX. Вчимося верстати на флексах](https://www.youtube.com/playlist?list=PLM6XATa8CAG5mPV60dMmjMRrHVW4LmV2x)_** & **_[CSS Grid Layout](https://www.youtube.com/watch?v=GV92IdMGFfA&list=PLM6XATa8CAG5pXQrW_kDaeZb_uIAMNZIm&ab_channel=%D0%A4%D1%80%D1%96%D0%BB%D0%B0%D0%BD%D1%81%D0%B5%D1%80%D0%BF%D0%BE%D0%B6%D0%B8%D1%82%D1%82%D1%8E)_** - it's funny that I watched almost all of Zhenia's videos (in most cases while practicing at the same time), but I missed these topics ;)
Well, I will definitely return to them in future tasks.

Also pretty cool cheat sheets: [FLEXBOX](https://fls.guru/flexbox.html) and [Grid Layout](https://fls.guru/grid.html).

**_[Flexbox Froggy](http://flexboxfroggy.com/#uk)_** - cool! Really cool! Practice in the format of the game is love <3
I've desire to implement such a game on my own, but the more I think, the more difficulties and pitfalls I see, but perhaps this is the first stage - to analyze the task and break it into sub-tasks. Let's see, maybe one day I will implement this idea.

<details>
  <summary>screen</summary>

![FlexboxFroggy](https://github.com/Serge044/kottans-frontend/blob/main/task_responsive_web_design/FlexboxFroggy.png)

</details>

<br>

**_[Grid Garden](http://cssgridgarden.com/)_** - In general, the same impressions as from Flexbox Froggy.

<details>
  <summary>screen</summary>

![GridGarden](https://github.com/Serge044/kottans-frontend/blob/main/task_responsive_web_design/GridGarden.png)

</details>

<br>

**_[11 things I learned reading the flexbox spec](https://medium.com/hackernoon/11-things-i-learned-reading-the-flexbox-spec-5f0c799c776b)_** - nice article, but the background color is so toxic to my eyes.. But I'm glad that I'm a FED beginner, and I can fix it in a couple of clicks ;)

<details>
  <summary>screen</summary>

![ToxicBC](https://github.com/Serge044/kottans-frontend/blob/main/task_responsive_web_design/toxic_layout.png)

</details>

---

## [HTML & CSS Practice](https://serge044.github.io/HTML-CSS-Popup/)

Honestly it was really challenging at first glance and it was a bit difficult to understand where to start, but after starting and writing the first lines of code it became easier, I looked at the result of my code, tested, refined and so on in a circle until it looked like something similar to the popup that was in the technical task.

One of the last challenges was to complete the optimization (which was not necessary for the task, but considering that most people now access the Internet using mobile phones, I think it is a necessary thing). And I couldn't do it exactly as I wanted, a lot of hours was spent until the answer was found - the `<viewport>` line was missing in the head of my HTML code... That's such a banal, but such a necessary thing))

And in general, I liked doing optimization, it's not easy sometimes, but it's really interesting. I also decided to make custom icons, and it also took quite a lot of time, but I personally like the result, I hope you do too ;)

Chat in Telegram helped me a lot, most of the questions were raised and clarified there. Now I have a whole collection of screenshots with useful information))
And a little bit of material that I would like to highlight separately, which was useful to me and answered my questions:

[Box-Shadow CSS Generator](https://html-css-js.com/css/generator/box-shadow)

[Background CSS property](https://fls.guru/cssbackground.html)

[A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-background)

[Custom checkboxes](https://www.youtube.com/watch?v=E6kLaaQFctU&ab_channel=%D0%92%D0%B0%D0%B4%D0%B8%D0%BC%D0%9C%D0%B0%D0%BA%D0%B5%D0%B5%D0%B2)

[w3schools](https://www.w3schools.com)

[MDN Web Docs](https://developer.mozilla.org/en-US)

…and two best friends - [stack overflow](https://stackoverflow.com) and [Google](https://www.google.com/)))

And of course, I am very grateful to my buddy, [Serhii Shytikov](https://github.com/SergeyShytikov), who gave me a lot of advises and support.

Stay tuned ;)

---

## JavaScript Basics

[Intro to javascript](https://www.coursera.org/learn/html-css-javascript-for-web-developers/home/week/4) - good explanations, but I think in case if it was my very first familiarity with my first programming language - then it would be difficult for me to orient myself to what, why and how to use all the stuff, the console, and how to add some "magic to the real site". I saw a lot of good explanations on Youtube for the first enter, for example, [Zheka's videos](https://www.youtube.com/watch?v=yJcCKuxfb2o&list=PLM6XATa8CAG7DDIBjNVd78Fv5Ueo930IV&ab_channel=%D0%A4%D1%80%D1%96%D0%BB%D0%B0%D0%BD%D1%81%D0%B5%D1%80%D0%BF%D0%BE%D0%B6%D0%B8%D1%82%D1%82%D1%8E), and I would strongly recommend getting acquainted with JS with these materials, especially now that Zheka's channel has become completely Ukrainian-language (p.s. No, I was not paid for advertising ;))

I also really enjoyed [Bohdan Staschuk's](https://www.youtube.com/c/CodingTutorials) materials, especially the [11-hours video](https://youtu.be/CxgOKJh4zWE), I watched it, paused it and simultaneously rewrote the code and tested it, maked changes, then commented it and moved on. I think it was a great time investment.

<details>
  <summary>screen</summary>

![Coursera](https://github.com/Serge044/kottans-frontend/blob/main/task_js_basics/Coursera.png)

</details>

<br>

[FreeCodeCamp](https://www.freecodecamp.org/) is a great resource, similar to codecademy.
Some things were very easy, and some of them (especially towards the end) made my brain boil))

If I couldn't solve the task at all or just couldn't understand from what side to start - I watched detailed solve
& explanation on YouTube. Thanks to the fact that FreeCodeCamp is quite popular there are a lot of materials. It helped to understand the logic much better than just looking at the solution

The only minus, and in my opinion it is the most significant, the draft with the solution is saved only until the moment the task is not solved, as soon as it is solved, the solution disappears forever. But I would like to look over time to past tasks, review the solve and try to optimize it with new skills, or simply grab a piece of code for another project.
When I understand it, I started saving solves in a draft.
I also used the IDE for some tasks to figure out step by step how to make it works.

<details>
  <summary>screens</summary>

![BasicJS](https://github.com/Serge044/kottans-frontend/blob/main/task_js_basics/BasicJS.png)

![ES6](https://github.com/Serge044/kottans-frontend/blob/main/task_js_basics/ES6.png)

![BasicDataStructures](https://github.com/Serge044/kottans-frontend/blob/main/task_js_basics/Basic%20Data%20Structures.png)

![BasicAlgorithmScripting](https://github.com/Serge044/kottans-frontend/blob/main/task_js_basics/Basic%20Algorithm%20Scripting.png)

![FunctionalProgramming](https://github.com/Serge044/kottans-frontend/blob/main/task_js_basics/Functional%20Programming.png)

![IntermediateAlgorithmScripting](https://github.com/Serge044/kottans-frontend/blob/main/task_js_basics/Intermediate%20Algorithm%20Scripting.png)

</details>

<br>

In general, the main difficulty was that there was a lot of new information in a short period of time, if it was divided into a longer period of time, it would be of course easier, but there is no time for complain. Moving on!

---
