---
title: Topic Modeling
nav: Topic Modeling
permalink: /topic-modeling.html
order: 5
---

{% include alert.html text="This page is under construction! Visit again soon for the finished product." color="danger" align="center" %}

---

**Goals**: Write in Markdown; name topics; view topic visualizations

**Estimated Time to Complete**: 1 hour + 30 minutes

---

Now that your project site is set up, we're going to learn how to add content to your essay and how to visualize topics in our 20th century State of the Union Address and Party Platform corpora.

## Step 1. Navigate to your project repository

1. Log in to GitHub (<https://github.com>).
2. Once you're logged in, select the dropdown arrow in the very top-right corner of your browser window. Once you select this, a dropdown should appear that starts with the words "Signed in as [your username]." On the dropdown, locate the link titled "Your repositories" and click on it. This will take you to your GitHub account and a list of all the repositories you've ever created.
3. Locate the name of the repository you created last week, and click on it. This will bring you to your project repository and website, where you can continue editing files following the steps below.

## Step 2. Practice adding content to your essay page

1. In the "About" section of your repository homepage (to the right of the green "Code" button), locate the url for your project site. Copy this url and open it in a ***new*** browser tab or window. While viewing your website, click on the "Essay In Progress" link in the navigation menu. This should take you to a page titled "My Essay Title." Scroll down this page, taking note of the different heading styles, font styles, bullet point lists, images, pdfs, and citations.
2. To edit the content on this page, navigate back to the browser tab or window that contains your repository homepage, then locate and click on the "pages" folder.  
3. Inside the "pages" folder, click on the file titled "essay-01.md." Then select the pencil button in the top right corner of the essay-01.md file to make your edits. Once in editing mode, at the very top of the file, you'll see the following:
```
---
title: Essay 1
layout: about
permalink: /essay-01.html
---

{% include feature/nav-menu.html sections="Introduction;Conclusion;Notes" %}
```

Skip to *below* this content, to where you see the line `# My Essay Title`.
This is the same content that you just saw on the "In Progress Essay" page.
In other words, when you write content into the essay-01.md file, it will show up on the "In Progress Essay" page on your website.

You'll notice that the content currently in essay-01.md looks a little different. 
This is because you'll be writing your essay content in a format called "Markdown."
Markdown was developed as a simple way to write content for the web without using HTML (hyptertext markup language), the language used to write websites.
We're using Markdown for your essays because it will allow you to incorporate images, pdfs, and visualizations into your essays easily.

Markdown is very similar to the way you write content in Microsoft Word documents, with a few key differences:

### Headings

Headings are used to title a section in your essay, and are indicated with one or more pound signs (`#`) in front of them.
One `#` indicates the largest heading, heading one.
Two `##` indicates heading two, which is slightly smaller than heading one.
Three `###` indicates heading three, and so on.

In your essay-01.md file, replace the words in the first heading `# My Essay Title` with a new title for your essay (note, this doesn't have to be what you officially title your essay, it can be anything you want right now).
Make sure you include one `#` in front of your essay title, like this: `# My New Essay Title`.

Now, you'll notice that `# My Essay Title` doesn't appear with a `#` in front of it on your actual website.
This is because the computer translates it into the appropriate code, so that it appears as a large title on your page, without displaying the `#` that you added on the back end.
Let's see this in action with your new title:

- After you've added a new title to your essay-01.md file, scroll down to the bottom of the file and time a commit message into the "Commit changes" text box.
- Then click the green "Commit changes" button to save your changes.
- Head over to where you opened your "Essay in Progress" page in a different tab or window.
- Wait a minute or two, then refresh the "Essay in Progress" page.
- You should see your new title displayed where `# My Essay Title` used to be.
- The updates may take a few seconds to a few minutes to appear, so keep refreshing if you don't see them right away.

Now that you've seen how the backend is translated into the front end of your website, you can continue to learn a few other features of Markdown:

### Paragraphs

Paragraphs in Markdown can be written exactly as they are in Microsoft Word, but without a tabbed first sentence and with a blank line in between paragraphs.
In other words, you can string together sentences one after another as are used to doing when you write papers or emails, and they will appear in a paragraph on the front end of the webpage.

*However*, also be aware that if you don't put an empty line between your paragraphs in your essay-01.md file, they will all join into one paragraph.

For example, these two paragraphs will look exactly as they do here on the webpage:

**Back end view**:

```
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent maximus ex vitae odio condimentum molestie. Cras porta, metus non tempus pellentesque, odio libero porttitor lectus, vel eleifend enim enim cursus nibh. Mauris aliquam dignissim nunc eget viverra. 

Duis in nisl in enim iaculis scelerisque. Ut congue ipsum nisi, nec ultrices nulla porta vel. In ultrices erat orci, in imperdiet dui tempor non. Nam placerat non ante nec viverra.
```

**Front end view**: 

```
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent maximus ex vitae odio condimentum molestie. Cras porta, metus non tempus pellentesque, odio libero porttitor lectus, vel eleifend enim enim cursus nibh. Mauris aliquam dignissim nunc eget viverra. 

Duis in nisl in enim iaculis scelerisque. Ut congue ipsum nisi, nec ultrices nulla porta vel. In ultrices erat orci, in imperdiet dui tempor non. Nam placerat non ante nec viverra.
```

But the following two paragraphs will merge into one paragraph when rendered on your webpage:

**Back end view**:

```
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent maximus ex vitae odio condimentum molestie. Cras porta, metus non tempus pellentesque, odio libero porttitor lectus, vel eleifend enim enim cursus nibh. Mauris aliquam dignissim nunc eget viverra. 
Duis in nisl in enim iaculis scelerisque. Ut congue ipsum nisi, nec ultrices nulla porta vel. In ultrices erat orci, in imperdiet dui tempor non. Nam placerat non ante nec viverra.
```

**Front end view**: 

```
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent maximus ex vitae odio condimentum molestie. Cras porta, metus non tempus pellentesque, odio libero porttitor lectus, vel eleifend enim enim cursus nibh. Mauris aliquam dignissim nunc eget viverra. Duis in nisl in enim iaculis scelerisque. Ut congue ipsum nisi, nec ultrices nulla porta vel. In ultrices erat orci, in imperdiet dui tempor non. Nam placerat non ante nec viverra.
```

So, make sure to leave empty lines between your paragraphs, and between headings and paragraphs.

### Font styles

To make a word or phrase *italic*, add one asterisk before and after that word or phrase, like this: `*example phrase*`.
The asterisks won't be visible on your webpage, but your text will appear italicized.

To make a word or phrase **bold**, add two asterisks before and after that word or phrase, like this: `**example phrase**`.
Again, the asterisks won't be visible on your webpage, but your text will appear bold.

### Hyperlinks

To link to another page or site, insert the link title (what you want displayed to the site visitors) into square brackets, followed by a URL in parentheses: 
`[GitHub Help](https://help.github.com/)` will look like [GitHub Help](https://help.github.com/) on the front end of your webpage.

### Lists

You can create lists in two different ways:

A bullet list is created using `-`, like:

- dog
- cat
- muffin

A numbered list is created using a number + `.`, like:

1. one
2. two
6. three
2. four

## Tasks

- write content into your essay page.
- name topics
- view topic visualizations