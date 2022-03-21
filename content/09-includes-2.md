---
title: "Review: add an Image and/or PDF to your Multimedia Essay"
nav: Add Supporting Items
permalink: /includes-2.html
order: 9
---

{% include alert.html text="This page is under construction! Visit again soon for the finished product." color="danger" align="center" %}


---

**Goals**: Review: include images and/or PDFs in essay

**Estimated Time to Complete**: 1 hour

---

You can apply the same process you used to upload Voyant visualizations to your essay to uploading images and documents. 
Follow the steps below to practice.

## Step 1. Locate an image or PDF that you'd like to use in your essay

Find digitized primary source material that you can use as supporting evidence for your essay. Many of you have already been using the online sources listed below. Even if you've already found an image or document that you're using in your essay, use this time to search these sources to see if you can find more.

The University of Idaho has a growing set of digitized sources in its [Digital Collections](https://www.lib.uidaho.edu/digital/collections.html){:target="_blank" rel="noopener"}. Pretty much every university has these now, so search out other universities and find their archival sources.

The [National Archives](https://www.archives.gov/research){:target="_blank" rel="noopener"} have a great deal of sources available online. A lot of them are government reports, and that might sound boring, but they often contain fabulous resources.

The [Internet Archive](https://archive.org/index.php){:target="_blank" rel="noopener"} has also compiled a huge set of digital resources. Not all sources here are primary, so you’ll need to be careful.

Newspapers are better sources than you might imagine. [Chronicling America](https://chroniclingamerica.loc.gov/){:target="_blank" rel="noopener"} has digitized a vast number of American newspapers going far back into the past, as you have learned in your WWI propaganda assignment.

[Digital Public Library of America](https://dp.la/){:target="_blank" rel="noopener"} pulls together items from digital libraries all over the country so you can search and find a variety of sources in one place.

There are many, MANY others; these are not meant to limit you! If you can't find what you're looking for, you're welcome to look elsewhere!

Once you've found an item or two that you can use in your essay, follow the steps below to practice incorporating it.

## Step 2. Navigate to your project repository

1. Log in to GitHub (<https://github.com>{:target="_blank" rel="noopener"}).
2. Once you're logged in, select the dropdown arrow in the very top-right corner of your browser window. Once you select this, a dropdown list should appear that starts with the words "Signed in as [your username]." On the dropdown, locate the link titled "Your repositories" and click on it. This will take you to your GitHub account and a list of all the repositories you've ever created.
3. Locate the name of the repository you created for your class project, and click on it. This will bring you to your project repository and website, where you can continue editing files following the steps below.

---

## Step 3. Open your website in a new browser tab or window

1. In the "About" section of your repository homepage (the section to the right of the green "Code" button), locate the URL for your project site. Right click this URL and select either "Open link in new tab" or "Open link in new window."
2. **NOTE: if you *don't* see your URL listed in the "About" section, you'll need to paste it into the "About" section manually.** Follow these steps:
   - On your project repository's homepage, click the "Settings" button (appears on the right, towards the top of the page, just above the green "code" button).
   - On the "Settings" page, locate the "Code and automation" section of the menu on the left.
   - Under "Code and automation," click on "Pages." This will take you to a page titled "GitHub Pages."
   - On the "GitHub Pages" page, you should see a green box that contains a green checkmark followed by the words "Your site is published at [your URL]." Right click on the URL, and select the "Copy Link" option (this will copy the link for you so you can paste it into the "About" section on the homepage of your GitHub repository).
   - Navigate back to the homepage of your GitHub repository by clicking on the "<> Code" tab above your repository files.
   - On right side of the code area, to the right of the green "Code" button, look for the word "About". Click the cog icon to the right of "About." A box titled "Edit repository details" will pop up.
   - In the "Edit repository details" popup, paste your URL into the "Website" section, then click the green "Save changes" button. This will post your URL below the "About" section on your GitHub repository's homepage, making it easy to access the site in the future!
3. While viewing your website, click on the "Final Essay" link in the navigation menu. 
4. Now you should have two tabs/windows open: **one with your GitHub repository** (the "*back end*" of your site) and **one with your website** (the "*front end*" of your site). You'll need both of these tabs/windows open for the duration of this Lab, and you'll work with both of them open in future Labs.

---

## Step 4. Copy and paste your Essay In Progress content into your Final Essay

Your Essay In Progress should stay just as you submitted it for your midterm.
You're going to copy the content from your `essay-01.md` file into the `essay-02.md` file and continue building on it there!
This will allow you to use the Essay In Progress as a reference point, to help you remember how to format your Markdown and includes in your Final Essay.
Follow the steps below.

### Copy

- In the browser tab containing your GitHub repository (the back end of your site), locate and click on the "pages" folder.  
- Inside the "pages" folder, click on the file titled `essay-01.md`. Then select the pencil button in the top right corner of the `essay-01.md` file to open editing mode. 
- Select *all the content* within your `essay-01.md` file, *except* for the frontmatter (lines 1-5 of your file). Your frontmatter for the `essay-01.md` file looks like this:
```
---
title: Essay 1
layout: about
permalink: /essay-01.html
---
```
- Don't copy this! Select everything *except* this (you can select content by clicking and dragging your cursor so that all the content of your essay is highlighted, then release the mouse). Right-click the highlighted content and select "Copy" from the dropdown menu.
- Once you've copied the content of `essay-01.md`, scroll to the bottom of the page but *instead of creating a commit message and clicking "Commit changes", **click the "Cancel" button!*** (You just copied content; you didn't make any changes to this file, so there's nothing to commit.)

### Paste

- Navigate to the homepage of your GitHub repository by clicking on the <> Code tab above your repository files.
- Locate and click on the "pages" folder.  
- Inside the "pages" folder, click on the file titled `essay-02.md`. This is the file for your Final Essay! This is where you'll be working from here on out. Go ahead and select the pencil button in the top right corner of the `essay-02.md` file to open editing mode. 
- Now select *all the content* within your `essay-02.md` file, *except* for the frontmatter (lines 1-5 of your file). Then delete this content by pressing the "Backspace" key on your keyboard, or right-clicking the highlighted content and selecting "Delete" from the dropdown menu.
- Once this content is deleted, paste in the content from your `essay-01.md` file: right-click on line 7 of your `essay-02.md` file, and select "Paste" from the dropdown menu. Leave your frontmatter on lines 1-5 just as it is. It should look like this:
```
---
title: Essay 2
layout: about
permalink: /essay-02.html
---
```

- Immediately commit your changes: add a commit message to the "Commit changes" box at the bottom of the page, then click the green "Commit changes" button.

---

## Step 5. Upload an image or PDF to the GitHub repository

1. Make sure your GitHub repository is still open in one browser tab/window, and your project website is still open in another tab/window. 
2. Switch to the tab that holds your GitHub repository, and navigate to the homepage of your GitHub repository by clicking on the <> Code tab above your repository files.
3. In your repository, locate and click on the "**objects**" folder (directly above the "pages" folder). There are already some files in this folder, and we're going to add your new file to them.
4. Towards the top right of the page (where the pencil button would normally be) locate the "Add file" button and click on it. This is a dropdown button that gives you two options: "Create new file" and "Upload files." Select "**Upload files**."
5. This brings you to a page that says "Drag files here to add them to your repository or choose your files." Click on the "choose your files" link. This will open up your File Explorer application (on a Windows machine) or your Finder application (on a Mac).
6. In File Explorer/Finder, locate your Downloads folder (or the folder where you saved the image or PDF you downloaded), and then locate the file you'd like to upload. 
7. Once you've selected the correct file, click the "Open" button in the bottom right of your File Explorer/Finder window. This will automatically trigger GitHub to upload the file.
8. In order to finalize the upload, you'll need to commit the change, so add a commit message to the "Commit changes" box at the bottom of the page, then click the green "Commit changes" button.
9. After you commit the file, GitHub will automatically redirect you to the repository's homepage. If you want to you can look inside your "objects" folder again to see the file you just uploaded, but this isn't necessary.

---

The steps above can seem complex when you're working through them for the first time.
If you'd like a visual demonstration of how to upload an image to your GitHub repository, watch the video below:

{% include video-embed.html youtubeid="_huFCz1LDyQ" caption="Upload an Image to Your GitHub Repository" %}

---

## Step 6. Include an image or PDF in your essay

1. Now switch to the browser tab that holds the "front end" of your project website.
2. In the navigation bar, locate and click on "Include Generator." We are going to use this form to generate an "include," a snippet of text that will allow us to display images on our essays, just as we displayed topic graphs last week.
3. In the middle of the "Include Generator" page, click on the dropdown that says "Select include type," and select the type of item you uploaded (either "image" or "pdf").
4. Click on the **filename** dropdown. You should see the filename of the image you just uploaded to your GitHub repository as an option in the dropdown list! Select this file.
5. The next field on the form that you'll need to fill in is "Image alt text." Besides selecting a file from the "Image filename" dropdown, this is the only other "required" piece of information that you'll need to fill in before you submit this form; everything below it is optional. 
    - **Why?**: The reason it is required is because "alt text" makes the internet a more inclusive place for people with visual impairment, by allowing screen readers to describe images to them as they navigate the web. The "alt text" for an image lives in the HTML code for that image, on the back end of the website, so you won't actually see the value you enter into this field anywhere on your essay page, but if you decide to make your essay public at the end of this project it will allow people with visual impairment to fully experience your site, images included.
    - **Guidelines**: The value for "alt text" should be brief but descriptive text that identifies the image you've uploaded. For instance, `image of a word cloud generated from Party Platform texts from the years 1900-1944` would be an appropriate value.
6. **Image caption** is an optional field that allows you to add a brief caption underneath the image you are including. Keep your caption length to a sentence or less. In some cases--but not always--your caption may be very similar to the text that you added for the "alt text" value. If you don't want to include a caption, simply leave this field blank.
7. **Image width** is an optional field that allows you to control how big your image is displayed on your essay. You can choose from four values: 25%, 50%, 75%, and 100%. If you leave this field blank, your image will automatically display at 100%.
8. **Image link** is an optional field that allows you to link back to the place where you found your image. In this case, you could add the URL for the Voyant Tools dashboard from which you downloaded the word cloud image. Note that an image link is not required for Voyant Tools screen shots, but it may be important to add links for future images that you obtain from other sources and which you'd like to add to your essay. So even if you don't use the image link option in this tutorial, you may need to use it for other images that you include as you write your essay.
9. Once you've filled in the desired fields in your form, click the blue "Submit" button at the bottom of the form. This will generate a box that appears beneath the form, titled "Include code," and containing a line of pink "include" text that looks similar to this:

`{% raw %}{% include feature/image.html filename="sotu-word-cloud.png" alt="image of a word cloud generated from corpus of 20th century State of the Union Addresses" width="50" %}{% endraw %}`

Copy **all** of the pink include text (brackets and all), then follow these steps to paste it into your `essay-01.md` file:

- Click over to the browser tab that holds your GitHub repository, and navigate to the homepage of your GitHub repository by clicking on the <> Code tab above your repository files.
- Locate and click on the "pages" folder in your repository.
- Inside the "pages" folder, locate and click on the `essay-01.md` file.
- Click the pencil button at the top right of your `essay-01.md` file to open editing mode.
- Create two new lines below the title of your Essay (**not** the title in the [frontmatter](/hist-320/topic-modeling.html#frontmatter){:target="_blank" rel="noopener"}, which is the content between three hyphens (`---`) at the very top of your file. Your essay title should be a Heading 1--a title you created that starts with a single pound sign (`#`)) in your `essay-01.md` file, and paste the "include" text that you copied from your website.
- Scroll down to the bottom of the file and type a commit message into the "Commit changes" text box.
- Click the green "Commit changes" button to save your changes.
- Head over to where you opened your website in a different tab or window, and use the navigation menu to switch back to the "Essay In Progress" page.
- Wait a minute or two, then refresh the "Essay In Progress" page.
- Once you refresh your site, you should see the new image appear below your essay title.
- The updates may take a few seconds to a few minutes to appear, so hold tight and keep refreshing if you don't see them right away.
- Are you happy with how the image looks? Remember you can regenerate the include for this image with a different width and caption. Once you've generated the new include text, delete the include text that you just added into the `essay-01.md` file and past the new include text into `essay-01.md` instead.

---

The steps above can seem complex when you're working through them for the first time.
If you'd like a visual demonstration of how to generate an image include and add it to your essay, watch the video below:

{% include video-embed.html youtubeid="_zzZnXaAp0o" caption="Generate an Image Include and Add It to Your Essay" %}

---