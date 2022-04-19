---
title: "Finishing Up"
nav: Finish Up
permalink: /finish.html
order: 11
---

---

**Goals**: Optional instructions to make your site visible to Google (so anyone can search for it) and/or turn off or delete your site after the semester is over

**Estimated Time to Complete**: 30 minutes

---

## Step 1. Navigate to your project repository

1. Log in to GitHub (<https://github.com>{:target="_blank" rel="noopener"}).
2. Once you're logged in, select the dropdown arrow in the very top-right corner of your browser window. Once you select this, a dropdown list should appear that starts with the words "Signed in as [your username]." On the dropdown, locate the link titled "Your repositories" and click on it. This will take you to your GitHub account and a list of all the repositories you've ever created.
3. Locate the name of the repository you created for your class project, and click on it. This will bring you to your project repository and website, where you can continue editing files following the steps below.

---

## Step 2. Open your website in a new browser tab or window

1. In the "About" section of your repository homepage (the section to the right of the green "Code" button), locate the URL for your project site. Right-click this URL and select either "Open link in new tab" or "Open link in new window."
2. Now you should have two tabs/windows open: **one with your GitHub repository** (the "*back end*" of your site) and **one with your website** (the "*front end*" of your site). You'll need both of these tabs/windows open for the duration of this Lab, and you'll work with both of them open in future Labs.

---

## Step 3. Make your site visible to Google

**This step is NOT required!**

Right now, Google is ignoring your website (meaning it won't appear in search results if someone were to search Google for your research topic).
If you're okay with Google ignoring your website, you don't need to do this step.
If you'd like to make your site visible to Google so that it does appear in search results, follow the instructions below.

1. On the homepage of your GitHub repository, locate the file titled `_config.yml`. Click on this file to open it.
2. In the top right corner of the `_config.yml` file, locate and click on the pencil icon to enter GitHub's editing mode.

You've already edited the `_config.yml` file to configure the core features of your project site (things like the site's title, author, and tagline).

Now, scroll down the file until you see this section of text:

```
##########
# ROBOTS EXCLUDE
#
# set noindex to true if you do NOT want Google to index your site
noindex: true 
```

Remember, any line with a pound sign (`#`) in front of it is a comment, meaning the computer will ignore it.
Right now we can see that the line `noindex: true` does NOT have a pound sign in front of it, meaning that currently Google is ignoring your site. 

If you'd like for anyone to be able to find your website by searching google, you can make your site accessible to google by adding a pound sign in front of the `noindex: true` line of text, like this:

`# noindex: true`

If you'd like for Google to continue ignoring your website, simply leave this line as it is and don't add a pound sign in front of it.

### Commit or cancel your changes

If you've made a change to the `_config.yml` file that you'd like to commit, follow these steps:

1. To commit the changes you just made to your `_config.yml` file, scroll to the bottom of the page where you made your edits. You'll see a box titled "Commit changes."
2. In the text box directly underneath "Commit changes," type a short message that describes your edits, such as `update site settings`.
3. Skip the option to add an extended description to the commit, and keep the box checked next to "Commit directly to the main branch".
4. Click on the green "Commit changes" button. This will save your changes and take you out of the "edit" mode.
5. Go back to repository's homepage (if you ever are confused about how to get back to the homepage, click on the "<> Code" tab in the top left section of the screen).

Otherwise, select the "Cancel" button at the bottom of the "Commit changes" box to cancel your changes to the file.

---

## Step 4. Turn off your website (after the semester is over)

**This step is NOT required!**

If you'd like to remove your project website from the web, **please wait until after May 18, 2022** to do so, to allow time for your instructors to review your essay.

### Keep the repository, turn off the website

If you'd like to keep your GitHub repository, but turn off your website, follow these steps:

1. On your project repository's homepage, click the "Settings" button (appears on the right, towards the top of the page, just above the green "code" button).
2. On the Settings > General page (the landing page after you click on the "Settings" button), scroll down until you see a section titled "Danger Zone", outlined in red.
1. On your project repository's homepage, click the "Settings" button (appears on the right, towards the top of the page, just above the green "code" button).
2. On the "Settings" page, locate the "Code and automation" section of the menu on the left.
3. Under "Code and automation," click on "Pages." This will take you to a page titled "GitHub Pages."
4. Underneath the title "GitHub Pages," locate the section titled "Source." Change the dropdown button from "main" to "None."
5. Click the "Save" button.
6. You have successfully turned off your website. If you'd like to turn on your website again, follow these instructions to [activate GitHub Pages](/hist-320/web-setup.html#gh-pages){:target="_blank" rel="noopener"}   

### Delete the repository and website permanently

If you'd like to delete your website and your repository, follow the steps below. 
Note that if you delete your website and repository before May 18, you will have to start your project over from scratch!

{% include alert.html text="The following steps are **irreversible**!! Please wait to complete them until after May 18." color="danger" %}

1. On your project repository's homepage, click the "Settings" button (appears on the right, towards the top of the page, just above the green "code" button).
2. On the Settings > General page (the landing page after you click on the "Settings" button), scroll down until you see a section titled "Danger Zone", outlined in red.
3. In the "Danger Zone" section, click on the button titled "Delete this repository." Deleting your repository will delete both your website's code and your website itself. There is no way to keep your website but delete your repository.
4. Since this action is irreversible, GitHub will ask you to type in the name of the repository owner and the name of the repository (i.e. 'username/digital-history-project') to confirm that you really want to delete it. Copy and paste or carefully type the requested information into the text box, and then select the "I understand the consequences, delete this repository" button to delete your repository and website.