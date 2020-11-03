# How to Host a Resume on Github with Markdown and Jekyll

This article will go over the basics of using Markdown, a Markdown editor, Github Pages, and Jekyll. By the end of this, you should be able to host your own resume on Github using the described tools. This assumes a novice level of computer science knowledge, with no experience with Markdown or Github required (see the Table of Contents if you want to skip some sections). 

### Table of Contents

- [Introduction](Introduction)
  
  - [Markdown](#Markdown)
  
  - [Markdown editors](#markdown-editors)
  
  - [Github Pages]()
  
  - [Jekyll]()

- [Step by step guide]()

- [Frequently Asked Questions](#FAQ)

- [A note on Andrew Etter's *Modern Technical Writing*]()

- [Conclusion]()

### 

### Introduction

###### 

#### Motivation

"What's the point?" is often the first question I ask whenever learning something. Let's address this immediately. Here are some reasons to consider hosting a resume on Github:

- It shows technical proficiency.

- It shows initiative.

- It provides a convenient place to display side projects.

- It's quite easy to learn how to do.

- It gives you valuable practice in increasingly popular tools.

#### Technology Overview

"What tools do I need?" is often the second question I ask. Here's a quick overview of the technology we'll be looking at:

- [Markdown](https://en.wikipedia.org/wiki/Markdown): a lightweight [markup language](https://en.wikipedia.org/wiki/Markup_language) which has recently become quite popular. It is designed to be easy to write, read, and learn. The existence of markdown editors means that you don't even need to know the syntax to get started!

- [Marktext](https://github.com/marktext/marktext/blob/develop/README.md): a markdown editor. Markdown editors allow you to write markdown without much prerequisite knowledge. This specific editor is not required - other editors are acceptable (just ensure they use [GitHub Flavored Markdown](https://github.github.com/gfm/), or Github may give you difficulties).

- [GitHub Pages](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/about-github-pages) is a [static site](https://en.wikipedia.org/wiki/Static_web_page) [hosting service](https://en.wikipedia.org/wiki/Web_hosting_service) that takes files from Github and uses them to publish a website. It is quite intuitive once you get the hang of it. This can be used to publish things such as resume's. 

- [Jekyll](https://en.wikipedia.org/wiki/Jekyll_(software)) is a static site generator that is built-in to Github Pages. We won't go into much more detail than is required to use this, but links to guides will be provided.

#### Markdown

[Markdown](https://en.wikipedia.org/wiki/Markdown) has a plethora of concise online tutorials/references. For a quick two-minute introduction, see either [this quick reference](https://wordpress.com/support/markdown-quick-reference/) or [this quick guide](https://guides.github.com/features/mastering-markdown/). For something more in-depth, see [here](https://www.markdowntutorial.com/). In my experience, I think that a good Markdown editor plus some Google searches is really all you need to know about syntax to get going. Here is a quick rundown on the most important details:

- Markdown was designed to be easy to read and easy to learn.

- Markdown has many "flavours". These are slightly different implementations of the specification, tailored to different needs and specifications. We will use [GitHub Flavored Markdown](https://github.github.com/gfm/) because we will be hosting on [GitHub Pages](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/about-github-pages)

- Markdown is easy to use. 

- Did I mention Markdown is easy to use? You don't even need to understand the syntax to begin writing it. The existence of Markdown editors means that, if you can use a basic text editor, then you can write Markdown!

- Google is your friend. If you're trying to format something, it's almost guaranteed that someone else had the same problem. 

#### Markdown editors

Regardless of the individual, some sort of text editor will need to be used to write Markdown. If you will be spending significant time writing Markdown, it is important that you select one that will improve your productivity. 

A good Markdown editor will (in my opinion):

- Show you a preview of your Markdown as you write.

- Provide keyboard shortcuts (eg. being able to use `ctrl+b` to add bold tags).

- Offer auto-complete features (these improve productivity in the long run).

- Write in the flavour of Markdown that you intend on using.

- Require as few syntax Google searches as possible.

There are many Markdown editors which satisfy these requirements, but one that I would recommend is [Marktext](https://github.com/marktext/marktext/blob/develop/README.md). If you can use Microsoft Word, then you can use Marktext.

#### Github Pages

[GitHub Pages](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/about-github-pages) is a [static site](https://en.wikipedia.org/wiki/Static_web_page) [hosting service](https://en.wikipedia.org/wiki/Web_hosting_service) that takes files from Github and uses them to publish a website. We will use this to host our resume.

#### Jekyll

Jekyll is a software tool that can take some Markdown, and produce a static website. For the purposes of this tutorial, you don't really need to know much else. We will use the built-in features of Github Pages to apply Jekyll.

#### Github Desktop

I recommend using this if you are unfamiliar with Git. This will make it much easier to create a Github repository. 

### Step by Step Guide

The moment we've all been waiting for. Now that we know all our components, here is a step by step guide for hosting your resume on Github Pages:

1. Get a resume

2. Download [Marktext](https://github.com/marktext/marktext/blob/develop/README.md)

3. Use Marktext to write your resume in Markdown. This should be about as easy as using Microsoft Word. If you get stuck on something, remember that Google is your friend. 

4. Once you have a Markdown-formatted resume, it is time to upload it to a Github repository. See [this guide](https://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1/) or other guides if you're unfamiliar with Git or Github. 
   
   1. You will need a [Github](https://github.com/) account to get started.
   
   2. If you're unfamiliar with Git, I recommend downloading [Github Desktop](https://desktop.github.com/) to simplify things.
   
   3. Create a new repository. In Github Desktop on Windows, this is done through File > Create New Repository. 
      
      ![](C:\Users\Nathan\Desktop\COMP%203040\Pictures\New%20Repository.png)
   
   4. [Commit]((https://github.com/git-guides/git-commit) your changes to your local repository. This is done through the "commit" button at the bottom left of Github Desktop. 
      
      ![](C:\Users\Nathan\Desktop\COMP%203040\Pictures\Committing.png)
   
   5. [Push]((https://www.atlassian.com/git/tutorials/syncing/git-push#:~:text=The%20git%20push%20command%20is,exports%20commits%20to%20remote%20branches.)) your resume to your repository. In Github Desktop, this is done by moving your resume Markdown file into the repository's folder, and then clicking "push to origin" in the Github Desktop interface (you may need to "fetch" first)
      
      ![](C:\Users\Nathan\Desktop\COMP%203040\Pictures\Pushing.png)

5. Provided you didn't get any errors uploading, your resume should now be on a Github repository. 

6. Navigate to your Github repository at github.com/YourUsername/YourRepositoryName using a web browser. You can view all your uploaded files there. ![Github URL](C:\Users\Nathan\Desktop\COMP%203040\Pictures\Github%20URL.png)
   
   ![](C:\Users\Nathan\Desktop\COMP%203040\Pictures\Github%20Files.png)

7. Now we will set up Github Pages and Jekyll. 
   
   1. Navigate to Github settings.![picture of settings in Github UI](Pictures/Settings%20on%20Github.png)
   
   2. Scroll to the "GitHub Pages" section and press "Change Theme". This will let you choose some theme. Choose any theme for now, if you don't like it then you can come back to it later. 
      
      ![](C:\Users\Nathan\Desktop\COMP%203040\Pictures\change%20theme.png)

8. Your resume should now be visible on Github Pages at RepositoryName/FileName. In my case, since I named my resume file `resume.md` and in the main folder of the repository, I was able to access it at `https://nathancarriere.github.io/resume`



### A note on Andrew Etter's *Modern Technical Writing*

I can already hear you asking, "Why bother setting up a site this way?" That's a good question, thanks for asking. 

This guide is heavily based on Andrew Etter's book, [*Modern Technical Writing*]((https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS). There are some very advantageous features of this type of setup. Some of Etter's recommendations we used include:

- Using lightweight markup. Etter recommends this because it is easier to read and write and so is accessible to a wider range of people, which means that more people can contribute to documentation. 

- Using Markdown. Etter recommends this because it is the most widely used lightweight markup language, and so it has more text editors than other lightweight markup languages and is likely more future-proofed.

- Using distributed version control. Etter recommends this because it provides better performance, facilitates concurrent work on the same file, and makes "undos" quite simple. This also helps keep your documentation up to date, since a developer or tester can make a pull request upon making a change or upon noticing that something is out of date.

- Using a static website. Etter recommends this because static sites are very simple and are not prone to crashing or being hacked.

- Using a static site generator. Etter recommends this because it allows you to create a beautiful and highly functional website with minimal effort. This saves lots of time on your end. 

### 

### Frequently Asked Questions

###### Why is Markdown better than a word processor?

- Markdown is a markup language designed to be viewed on the web. It's designed to have CSS and other technology run through it efficiently. This is why websites use markup languages instead of Microsoft Word .docx files. (Also, good luck trying to navigate or read [the mess that is .docx raw source code](https://www.toptal.com/xml/an-informal-introduction-to-docx))

**I can see the README on Github Pages but not my resume. What's wrong?**

- If this is the case, there's a good chance you're just looking at the wrong URL. For example instead of viewing `https://www.RepositoryName`, you might want to go to `https://www.RepositoryName/`. 
