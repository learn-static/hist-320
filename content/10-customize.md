---
title: "Customize Your Site"
nav: Customize
permalink: /customize.html
order: 10
---

---

**Goals**: Make optional edits to your essay and website

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

{:#title}
## Step 3. Make edits to your site title and tagline

**This step is NOT required!**

You are welcome to edit your site title and tagline at any point.
To do this, follow the instructions below.
If you're happy with your site title and tagline, skip to the next step.

1. On the homepage of your GitHub repository, locate the file titled `_config.yml`. Click on this file to open it.
2. In the top right corner of the `_config.yml` file, locate and click on the pencil icon to enter GitHub's editing mode.

The `_config.yml` file is used to configure the core features of your project site (things like the site's title, author, and tagline).
The configuration options are made up of key-value pairs, separated by a colon (`:`), and written in a format called [YAML](https://collectionbuilder.github.io/cb-docs/docs/glossary/#yaml). 
For example, below is the **key** "title", followed by its **value**, "Analyzing Political Text of The 20th Century":

```
# title of site appears in banner
title: Analyzing Political Text of The 20th Century
```

Above "title," the line of text that starts with a pound sign (`#`) is a *comment*.
The comment is a note to you, the website creator, to tell you what value you should add to the title. 
The computer ignores the comment but processes the title key and value.
Any line in this `_config.yml` file that starts with a `#` is a comment.

You've already edited the following values, but you can edit them again if you're not happy with the title, tagline, or author name you chose: 

#### title: 

- `title` is the title of your digital project. This will appear as the title on your website's home page, and on every other page's header and footer. Change the words `Analyzing Political Text of The 20th Century` to a title of your choice.
```
title: Analyzing Political Text of The 20th Century
```

#### tagline: 

- `tagline` is an *optional* descriptive subtitle for the digital project. This will appear underneath the title on your site's home page and on every other page's header. Replace the words `A multimedia project for HIST 320, a Spring 2022 History course at the University of Idaho` with a tagline of your choice.
```
tagline: A multimedia project for HIST 320, a Spring 2022 History course at the University of Idaho
```

#### author: 

- `author` is you! The creator of the digital project. Use your GitHub username or your name. This will only appear in the site's meta tags and won't be visible on the site itself. Change the name `collectionbuilder` to your own name or username.
```
author: collectionbuilder
```

### Commit your changes to _config.yml

1. To commit the changes you just made to your `_config.yml` file, scroll to the bottom of the page where you made your edits. You'll see a box titled "Commit changes."
2. In the text box directly underneath "Commit changes," type a short message that describes your edits, such as `update site settings`.
3. Skip the option to add an extended description to the commit, and keep the box checked next to "Commit directly to the main branch".
4. Click on the green "Commit changes" button. This will save your changes and take you out of the "edit" mode.
5. Go back to repository's homepage (if you ever are confused about how to get back to the homepage, click on the "<> Code" tab in the top left section of the screen).

---

{:#homepage}
## Step 4. Add an introduction to your website's homepage

1. From your repository's homepage, locate and click on the "pages" folder.  
2. Inside the "pages" folder, click on the file titled "index.md." Then select the pencil button in the top right corner of the `index.md` file to open editing mode.
3. `index.md` contains the text content written on the homepage of your project website! It's written in markdown, just like your essay (notice that the title is a heading 1?). This is an opportunity for you to add your own introduction to your site. It doesn't need to be long, think of it as a brief welcome to the imagined future users of your site, and a short description of what your research is about.
4. When you're ready to write, delete the four paragraphs of stock content (starting with `This is the project site for the HIST 320...` and ending with `images into your essays`). Delete these four paragraphs, and add your own introduction in their place.
5. Replace the heading `# Digital History Project` with your own title for your homepage.
6. Remember **DO NOT** alter the frontmatter that exists at the very top of the page (lines 1-6). Leave the frontmatter exactly as it is, otherwise your site will not work correctly.
7. When you're happy with your title and introduction, commit your changes: add a commit message to the "Commit changes" box at the bottom of the page, then click the green "Commit changes" button.
8. Go back to repository's homepage (if you ever are confused about how to get back to the homepage, click on the "<> Code" tab in the top left section of the screen).
9. Head over to where you opened your website in a different tab or window, and make sure you've navigated to your website's Home page.
10. Wait a minute or two, then refresh your website's homepage.
11. Once you refresh your site, you should see your new introduction.
12. The updates may take a few seconds to a few minutes to appear, so hold tight and keep refreshing if you don't see them right away.

---

## Step 5. Add a custom image to your website's homepage

**This step is NOT required!**

You're welcome to change the image that is featured on the homepage of your website.

### Find an image

You can use an image of your choice, as long as you have the rights to it, or it is in the public domain (images created before 1927 are now in the public domain).
This means that it should be an image that you've created, or an image that is not under copyright.

Some options to find public domain include:

- Unsplash: <https://unsplash.com/>{:target="_blank" rel="noopener"}
- Wikimedia Commons: <https://commons.wikimedia.org/wiki/Main_Page>{:target="_blank" rel="noopener"}

### Upload your image

When you've found the image you want to use, upload it to your repository's "objects" folder following these steps:

1. In your repository, locate and click on the "**objects**" folder (directly above the "pages" folder). There are already some files in this folder, and we're going to add your new file to them.
2. Towards the top right of the page (where the pencil button would normally be) locate the "Add file" button and click on it. This is a dropdown button that gives you two options: "Create new file" and "Upload files." Select "**Upload files**."
3. This brings you to a page that says "Drag files here to add them to your repository or choose your files." Click on the "choose your files" link. This will open up your File Explorer application (on a Windows machine) or your Finder application (on a Mac).
4. In File Explorer/Finder, locate and select the image that you've decided to use.
5. Once you've selected the correct file, click the "Open" button in the bottom right of your File Explorer/Finder window. This will automatically trigger GitHub to upload the file.
6. In order to finalize the upload, you'll need to commit the change, so add a commit message to the "Commit changes" box at the bottom of the page, then click the green "Commit changes" button.
7. After you commit the file, GitHub will automatically redirect you to the repository's homepage. If you want to you can look inside your "**objects**" folder again to see the file you just uploaded, but this isn't necessary.

### Set up your image to display on the homepage

1. In your repository, locate and click on the "**_data**" folder (the folder at the very top of your repository!). Inside the _data folder, locate the `theme.yml` file and click on it. Then select the pencil button in the top right corner of the `theme.yml` file to open editing mode.
2. This file is written in [YAML](https://collectionbuilder.github.io/cb-docs/docs/glossary/#yaml), just like your `_config.yml` is! Remember, YAML is a data type made up of key-value pairs, separated by a colon (`:`). You will also see comments in this file (indicated by a pound sign (`#`) at the beginning of a line). Locate the comment that reads `# HOME PAGE`.

#### featured-image:

- In the `# HOME PAGE` section, locate the `featured-image: feature-image.jpg` key-value pair. To add your own image, replace the value `featured-image.jpg` with your image's filename (including file extension). For instance, if you just uploaded an image with filename `digital-project-homepage.jpg` to your objects folder, this is the exact value you'd use for `featured-image`. Note that any typos will cause your image not to appear, so be sure to double check that your spelling matches the actual filename. You can use either PNG or JPG files for your featured image.

#### home-title-y-padding:

- Underneath `featured-image`, there is the key-value pair `home-title-y-padding: 9em`. This key lets you adjust how tall your image appears on your homepage. You can reduce the size of the image by replacing the number 9 with a number less than 9 (example: `6em`). You can increase the size of the image by replacing the number 9 with a number greater than 9 (example: `12em`). Remember to include the letters `em` after the number you choose! The em unit is used in web development to measure padding around elements on the webpage.

#### home-banner-image-position:

- Finally, if desired, you can change the position of your featured image. By default, your image will display so that the center of the image is aligned with your site title. You can add a value to the key `home-banner-image-position` to make your image positioned from its top or bottom instead of center. To do this, add the value `top` or the value `bottom` to the right of the colon (`:`) after the `home-banner-image-position` key, but before the pound sign (`#`) (remember, everything after the pound sign is a comment, so if you add the value after the sign, the computer won't register it!). To keep the position at center, just leave the value for `home-banner-image-position` blank.

### Commit your changes:
- Add a commit message to the "Commit changes" box at the bottom of the page, then click the green "Commit changes" button.
- Head over to where you opened your website in a different tab or window, and make sure you've navigated to your website's Home page.
- Wait a minute or two, then refresh your website's homepage.
- Once you refresh your site, you should see the changes to the image on your homepage.
- The updates may take a few seconds to a few minutes to appear, so hold tight and keep refreshing if you don't see them right away.

{:.alert .alert-success}
**NOTE**: It's entirely possible that you won't like the edits you made to the padding or the image position! That's okay! Just go back into the theme.yml file and edit them again. If you find that you do not like the image that you added, feel free to use the default image that came with the site. Simply use the value `feature-image.jpg` for the `featured-image` key.

---

{:#block-quote}
## Step 6. BONUS: Add a block quote to your essay

**This step is NOT required!**

As you are writing your final essay, you may come across a quote that you'd like to visually highlight.
Follow the steps below to add a "block quote" to your Final Essay.

- Copy *all* of the code below:

```
<blockquote class="blockquote pt-3 pb-5" style="font-size: 1.75rem; margin-left: auto; margin-right: auto; max-width: 650px;">
  <p class="mb-0">I guess what everyone wants more than anything else is to be loved. And to know that you loved me for my singing is too much for me. Forgive me if I don't have all the words. Maybe I can sing it and you'll understand.</p>
  <footer class="blockquote-footer text-right">Ella Fitzgerald, <cite title="Source Title"><a href="http://www.ellafitzgerald.com/about/quotes" target="_blank" rel="noopener">Quotes</a></cite></footer>
</blockquote>
```

- Navigate to your `essay-02.md` file (inside your pages folder in your repository), click the pencil button to enter editing mode, and paste this code into your essay. Location doesn't matter, just paste it somewhere that will make sense with the surrounding essay text. 
- Now you'll need to change three values in the code you just pasted:

#### Quote
- Change the value of the quote by replacing `I guess what everyone wants more than anything else is to be loved. And to know that you loved me for my singing is too much for me. Forgive me if I don't have all the words. Maybe I can sing it and you'll understand.` with a new quote of your choosing.

#### Author
- Change the value of the person who said the quote by replacing `Ella Fitzgerald` with the person who said the quote you just added.

#### Source link
- Change the value of the link to the quote's source by replacing `http://www.ellafitzgerald.com/about/quotes` with the proper link.
- **If your source does not have a link**, delete these two values: `<a href="http://www.ellafitzgerald.com/about/quotes" target="_blank" rel="noopener">` and `</a>`, but leave the word "Quotes"

#### Source title

- Finally, change the word `Quotes` to the title of the source where you found your quote (this would be the title of a book, article, pamphlet, etc.).

### Commit your changes:
- Once you've updated all the values for your block quote, add a commit message to the "Commit changes" box at the bottom of the page, then click the green "Commit changes" button.
- Head over to where you opened your website in a different tab or window, and use the navigation menu to switch back to the "Final Essay" page.
- Wait a minute or two, then refresh the web page.
- Once you refresh your site, you should see the block quote appear in your essay.
- The updates may take a few seconds to a few minutes to appear, so hold tight and keep refreshing if you don't see them right away.

---

## Step 7. Finishing up

Head over to this week's Lab Discussion to post a link to your project site and answer a question about the work you completed in this Lab.