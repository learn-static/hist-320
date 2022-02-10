---
title: Set Up Your Website
nav: Web Setup
permalink: /web-setup.html
topics: GitHub; GitHub Pages; Websites
order: 4
---

{% include alert.html text="This page is under construction! Visit again soon for the finished product." color="danger" align="center" %}

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

1. Take a look at the files in your repository and locate the one titled `_config.yml`. Click on this file.

The `_config.yml` file is used to configure the core features of your project site.
The configuration options are made up of key-value pairs written in a format called [YAML](https://collectionbuilder.github.io/cb-docs/docs/glossary/#yaml). 
For example, below is the option "title", followed by its value, "Example Site Title":

```yaml
# title of site appears in banner
title: Analyzing Political Text of The 20th Century
```

Above the "title" line, the line of text that starts with a pound sign (`#`) is a comment.
The comment is a note to you, the website creator. 
The computer ignores the comment but processes the title value.

Right now, placeholder values fill all the options in your `_config.yml` file.
You'll need to switch out these placeholders with the information about your individual site.

For example, you'll need to change the words `Analyzing Political Text of The 20th Century` in the value below:

```yaml
# title of site appears in banner
title: Analyzing Political Text of The 20th Century
```

To the title you've chosen to give your site:

```yaml
# title of site appears in banner
title: My Example Site Title
```

### source-code: 

- `source-code` is the full URL for the GitHub repository containing your project code. It is used to add a link back to your project repository.

Look for the words "SITE SETTINGS."

Directly above SITE SETTINGS, find the "source-code" value.
The value of source-code should be a link to your repository.
Copy your repository's URL and past it over the example text to the right of `source-code:`
```yaml
source-code: https://github.com/learn-static/text-analysis
```

### title: 

- The title of your digital collection. 
- This will appear as the title on the home page, and on every other page's header and footer. 
```yaml
title: Donald R. Theophilus Boxing Photograph Collection
```

### tagline: 

- A *optional* descriptive subtitle for the digital collection.
- This will appear underneath the title on the home page and on every other page's header.
```yaml
tagline: Photographs of University of Idaho Boxers and Boxing Teams, 1934 - 1953
```

### description:

- One or two sentences of explanatory text about the collection.
- Appears on the home page under the featured image and in meta markup. Since this description may appear in search result lists, keep it around 160 characters max.
```yaml
description: "A digital collection composed of 52 photographs of boxers and boxing teams from the University of Idaho"
```

### author: 

- You! The creator of the digital collection.
- Use your GitHub username or your name. This will only appear in the site's meta tags.
```yaml
author: evanwill
```

```yaml
##########
# SITE SETTINGS
#
# title of site appears in banner
title: Analyzing Political Text of The 20th Century
# tagline, a short phrase that will appear throughout the site in the top banner
tagline: A multimedia project for HIST 320, a Spring 2022 History course at the University of Idaho
# description appears in meta tags and other locations
# this description might appear in search result lists, keep around 160 characters max
description: "Learn-Static Text Analysis is a template for creating digital history projects on GitHub Pages"
# creator of the digital project, to appear in meta tags; we typically use our GitHub usernames but feel free to just use your name
author: collectionbuilder
```

## Activate GitHub Pages

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

{:.alert .alert-green}
Congratulations! 
Your site is now live. 