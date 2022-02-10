---
title: Set Up Your Website
nav: Web Setup
permalink: /web-setup.html
topics: GitHub; GitHub Pages; Websites
order: 4
---

---

**Goals**: Copy and GitHub repository template; edit the repository's configuration file; turn on GitHub Pages

**Estimated Time to Complete**: 1 hour

---

In the first lab for this course you created a GitHub account and practiced creating a repository. Now, you'll be working on GitHub to set up your project website. 

## Step 1. Log in to GitHub

1. Go to <https://github.com> and sign in.

## Step 2. Copy the project template repository

Remember, a GitHub repository is a folder that stores a project's files and keeps track of changes to those files over time.
Let's copy a the project template repository to your GitHub account so you can start editing it.

1. Go to the [Text Analysis Project Template](https://github.com/learn-static/text-analysis) repository and locate and click on the green "Use This Template" button (appears on the top right side of the screen above the code area). Note that the "Use This Template" button only appears if you're logged into GitHub!
2. This brings you to a "Create a new repository" form. Follow these steps:
    1. **Repository name**: Use a lowercase name without spaces or odd characters (no `$`, `#`, `@`, `?`, `!`, etc. -- in other words, no special characters). Hyphens (`-`) and underscores (`_`) are okay to use. Keep in mind that this repository name will become part of your project site's URL, so think through how it will look as a link!
    2. In the **Description** text box, add a very brief description of your project, something like: `My digital history project for HIST 320`.
    3. Select the option for "**Public**" repository.
    4. Leave the "Include all branches" option **Unchecked**!
    5. Click on the green button "**Create repository from template**". This will take you to your new repository (Note that it may take a few seconds to generate).

## Step 3. Edit the site settings

1. Take a look at the files in your repository and locate the one titled `_config.yml`. Click on this file to open it.
2. In the top right corner of the `_config.yml` file, locate and click on the pencil icon to enter GitHub's editing mode.

The `_config.yml` file is used to configure the core features of your project site.
The configuration options are made up of key-value pairs written in a format called [YAML](https://collectionbuilder.github.io/cb-docs/docs/glossary/#yaml). 
For example, below is the **key** "title", followed by its **value**, "Analyzing Political Text of The 20th Century":

```
# title of site appears in banner
title: Analyzing Political Text of The 20th Century
```

Above the "title", the line of text that starts with a pound sign (`#`) is a comment.
The comment is a note to you, the website creator, to tell you what value you should add to the title key. 
The computer ignores the comment but processes the title value.

Right now, placeholder values fill all the values in your `_config.yml` file.
You'll need to switch out these placeholders with the information you create about your individual site.

There are five values you need to edit.
Below, we'll walk through editing each one.

First, look for the SITE SETTINGS comment.
It should look like this:

```
##########
# SITE SETTINGS
```

Directly above the SITE SETTINGS comment, locate the "source-code" key.  

### source-code: 

- `source-code` is the full URL for the GitHub repository containing your project code. It is used on your website to add a link back to your project repository. Copy your repository's URL and paste it over the example text to the right of `source-code.`

For example, the default placeholder value is this:
```
source-code: https://github.com/learn-static/text-analysis
```

And will change to reflect your own repository's URL after you paste in your repository's URL:
```
source-code: https://github.com/my-github-name/my-repository-name
```

### title: 

- `title` is the title of your digital project. This will appear as the title on the home page, and on every other page's header and footer. Change the words `Analyzing Political Text of The 20th Century` to a title of your choice.
```
title: Analyzing Political Text of The 20th Century
```

### tagline: 

- `tagline` is an *optional* descriptive subtitle for the digital project. This will appear underneath the title on the home page and on every other page's header. Replace the words `A multimedia project for HIST 320, a Spring 2022 History course at the University of Idaho` with a tagline of your choice.
```
tagline: A multimedia project for HIST 320, a Spring 2022 History course at the University of Idaho
```

### description:

- `description` should be one or two sentences of explanatory text about the project. The description will appear on the home page under the featured image and in meta markup. Since this description may appear in search result lists, keep it around 160 characters max.
- **NOTE**: In order for the computer to interpret it correctly, you'll need to **keep quotation marks around your entire description, just like the example does**. Replace `"Learn-Static Text Analysis is a template for creating digital history projects on GitHub Pages"` with your own description in quotations.
```
description: "Learn-Static Text Analysis is a template for creating digital history projects on GitHub Pages"
```

### author: 

- `author` is you! The creator of the digital project. Use your GitHub username or your name. This will only appear in the site's meta tags and won't be visible on the site itself. Change the name `collectionbuilder` to your own name or username.
```
author: collectionbuilder
```

## Step 4. Commit changes to _config.yml
1. To commit the changes you just made to your `_config.yml` file, scroll to the bottom of the page where you made your edits. You'll see a box titled "Commit changes."
2. In the text box directly underneath "Commit changes," type a short message that describes your edits, such as `update site settings`.
3. Skip the option to add an extended description to the commit, and keep the box checked next to "Commit directly to the main branch".
4. Click on the green "Commit changes" button. This will save your changes and take you back to your repository's homepage.

## Step 5. Activate GitHub Pages

1. On your project repository's home page, click the "Settings" button (appears on the right along the tabs above the code area).
2. On "Settings" page: click "Pages" in the left side menu.
3. On the "Pages" page: in the "Source" section, change the dropdown button from "none" to "main" (leave the folder option as "/root"), then click the "Save" button. 

Once saved, the page will refresh with an alert providing the URL where your site will appear. 
It will take a few minutes for the build to happen and your site to go live--so wait it out! 

Meanwhile, you might want to copy the URL to display on your home page:

1. Copy the provided URL.
2. Go to repository's home page.
3. On right side of the code area, look for "About" section and click on the cog icon to edit. 
4. In the "About" box, paste in your URL, then click "Save". This will make it easy to access the site in the future!

Congratulations! 
Your site is now live. 