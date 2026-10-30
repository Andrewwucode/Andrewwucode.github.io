---
layout: default
title: How to Create a GitHub Pages E-Portfolio
---

# How I Created My GitHub Pages E-Portfolio

## Introduction

This tutorial explains how I created my e-portfolio for Milestone I using GitHub Pages and the Jekyll Minimal theme. I followed the assignment instructions and will explain the steps I took, the tools I used, and the changes I made to customize my website. My goal was to create an e-portfolio that showcases my educational background, work experience, technical skills, and projects to potential employers.

## Step 1: Creating a GitHub Repository

I already had a GitHub account, so I did not need to create a new one. The first thing I did was click the plus sign in the upper-right corner of GitHub and select _New repository_. I named my repository `Andrewwucode.github.io` by replacing `username` in the required `username.github.io` format with my GitHub username. I made the repository public so that GitHub Pages could host my e-portfolio.

## Step 2: GitHub Desktop

Next, I installed [GitHub Desktop](https://desktop.github.com/). I chose to use GitHub Desktop because I find it easier to clone, commit, push, and pull changes using an application instead of writing terminal commands. After opening GitHub Desktop and signing in, I cloned the repository I had just created onto my computer. This created a local folder named `Andrewwucode.github.io`, where I could work on my website files.

## Step 3: Downloading the Minimal Theme

I downloaded the [Jekyll Minimal theme](https://github.com/pages-themes/minimal) from GitHub. I clicked _Code_, selected _Download ZIP_, and extracted the downloaded files. I then copied the theme files into my `Andrewwucode.github.io` repository folder. I chose the Minimal theme because it provides a simple and organized layout that allows visitors to focus on my background and projects.

## Step 4: Visual Studio Code

I already had [Visual Studio Code](https://code.visualstudio.com/) installed, so I did not need to download it again. I opened VS Code and selected _File > Open Folder_ to open my `Andrewwucode.github.io` repository. This allowed me to edit the files from the Minimal theme, including `_config.yml` and `index.md`.

## Step 5: Customizing the Minimal Theme

After opening the repository in VS Code, I started modifying the existing files to personalize my e-portfolio.

## Step 6: Editing `_config.yml`

The `_config.yml` file controls several settings for the website, including the title, profile picture, description, and theme. I used the following configuration:

```yaml
title: Andrew Wu
logo: /assets/img/pic.png
description: M.S. Business Analytics Student | B.S. Computer Science
show_downloads: false
google_analytics:
theme: jekyll-theme-minimal
```

I changed the `title` to my name because the website is my personal e-portfolio. I used `logo` to display my profile picture, which I saved as `pic.png` in the `assets/img` folder. I wanted visitors to be able to put a face to my name. I changed the `description` to show my educational background, including my current master's degree in Business Analytics and my bachelor's degree in Computer Science. I set `show_downloads` to `false` because I did not want the download buttons to appear underneath my profile information. I left `google_analytics` blank because I was not using Google Analytics. Finally, I used `theme: jekyll-theme-minimal` to specify the theme for my website.

![Customized Profile](/assets/img/profile.png)

## Step 7: Editing `index.md`

The `index.md` file contains the main content of my e-portfolio. I used Markdown headings, paragraphs, bullet points, and links to organize the information. I included the following at the beginning of the file to use the theme's default layout:

```yaml
---
layout: default
---
```

### About Me

When creating my introduction, I put myself in the reader's shoes and thought about what a potential employer would want to know about me when considering hiring me. I wanted visitors to know that I graduated with a degree in Computer Science from San Diego State University while also learning about my hobbies and interests. My goal was to make myself more personable because a resume can only tell someone so much about who I am. I used the `# About Me` heading to create the main section of my homepage.

### Education

I included an Education section to show employers that I have a background in Computer Science and am currently pursuing a master's degree in Business Analytics. I wanted to highlight both degrees because they represent my technical background and my growing knowledge of data analytics.

### Work Experience

For my Work Experience section, I wanted to include relevant experience because I am interested in pursuing a career in a technology-related field. I included my experience at Hive, where I worked as a Software Engineer using technologies such as Flutter, Dart, Firebase, Supabase, and LiveKit. I used bullet points to describe my responsibilities and the technologies I worked with.

### Notable Projects

I created a Notable Projects section to showcase projects I completed during my Computer Science degree. I wanted potential employers to see examples of my technical abilities beyond what I listed in my resume.

#### Smart Water Filter

I included my Smart Water Filter project because it was one of my favorite projects from my Internet of Things (IoT) class. For this project, I worked with microcontrollers, circuit boards, wires, and sensors. I also learned how to solder and used AWS to support the system. This was one of my first experiences building an IoT device on my own, which made the project particularly meaningful to me.

#### Baby Monitor

I also included my Baby Monitor project from my wireless class. Similar to my Smart Water Filter project, I built an IoT system using a microcontroller and sensors. The system monitored sounds and could send alerts using AWS and WhatsApp. I was proud of how this project turned out, so I wanted to include it as another example of my hands-on experience.

### Technical Skills

I added a Technical Skills section to show potential employers the programming languages, tools, and technologies I have worked with. I organized my skills into categories such as Programming, Data Analytics, Development, and Tools & Platforms. I also included Power BI as a tool I am learning through my Business Analytics program.

### Links

Finally, I included links to my GitHub and LinkedIn profiles so that visitors could learn more about my projects and professional background.

![Completed E-Portfolio](/assets/img/profile2.png)

## Step 8: Configuring GitHub Pages

To publish my e-portfolio, I used GitHub Pages.

1. I opened my `Andrewwucode.github.io` repository on GitHub
2. I clicked _Settings_
3. I selected _Pages_
4. Under _Build and deployment_, I selected _Deploy from a branch_
5. I selected the `main` branch and `/ (root)` folder
6. I clicked _Save_

This allowed GitHub Pages to publish my website using the files in my repository.

![GitHub Pages Configuration](/assets/img/pages.png)

## Step 9: Publishing My Changes

After editing my website files in Visual Studio Code, I saved my changes and opened GitHub Desktop. I reviewed the modified files, entered a commit message, and clicked _Commit to main_. Then I clicked _Push origin_ to upload the changes to GitHub. Once GitHub Pages finished deploying the updated files, I opened my website, `Andrewwucode.github.io`, to see if the changes had been applied. Sometimes, it took a few minutes for the website to update. I would check whether the changes looked the way I wanted. If they didn't, I would go back into the files and modify them again.

## Resources

- [GitHub](https://github.com/)
- [GitHub Desktop](https://desktop.github.com/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Jekyll Minimal Theme](https://github.com/pages-themes/minimal)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Markdown Guide](https://www.markdownguide.org/basic-syntax/)
