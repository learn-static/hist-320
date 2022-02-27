---
title: Including Images in Your Essay
nav: Image Includes
permalink: /includes.html
order: 6
---

{% include alert.html text="This page is under construction! Visit again soon for the finished product." color="danger" align="center" %}

---

**Goals**: Continue writing in Markdown; include images and pdfs in essay

**Estimated Time to Complete**: 1 hour

---

Last week we learned how to write in Markdown on our essay page, how to view the results of our topic modeling, and how to include topic graphs on our essay page.
This week we'll finish up learning about Markdown styling, and follow instructions to include images and PDFs to our essay.

## Step 1. Navigate to your project repository

1. Log in to GitHub (<https://github.com>{:target="_blank" rel="noopener"}).
2. Once you're logged in, select the dropdown arrow in the very top-right corner of your browser window. Once you select this, a dropdown list should appear that starts with the words "Signed in as [your username]." On the dropdown, locate the link titled "Your repositories" and click on it. This will take you to your GitHub account and a list of all the repositories you've ever created.
3. Locate the name of the repository you created last week, and click on it. This will bring you to your project repository and website, where you can continue editing files following the steps below.

---

## Step 2. Open your website in a new browser tab or window

1. In the "About" section of your repository homepage (the section to the right of the green "Code" button), locate the URL for your project site. Right click this URL and select either "Open link in new tab" or "Open link in new window."
2. Now you should have two tabs/windows open: **one with your GitHub repository** (the "*back end*" of your site) and **one with your website** (the "*front end*" of your site). You'll need both of these tabs/windows open for the duration of this Lab, and you'll work with both of them open in future Labs.

---

## Step 3. More Markdown

Beyond paragraphs, headings, lists, and bold and italic font, there are a few Markdown elements that we still need to cover:

### Citations

You'll need to cite the sources for your multimedia essay just as you would for any essay.
Remember you'll be using [Turabian Style](https://www.chicagomanualofstyle.org/turabian/turabian-notes-and-bibliography-citation-quick-guide.html){:target="_blank" rel="noopener"} to add your essay citations as footnotes.

To add a footnote in Markdown, directly after the sentence you'd like to cite, add a footnote number (i.e. `1`, `2`, `3`, etc.), preceded by a caret symbol (`^`) and enclosed by square brackets (`[]`), following this example:

`Example text to be cited.[^1]`

`Yet more text to cite.[^2]`

Then, at the very bottom of the page, you'll create a section with the heading `Notes`, and add the bracketed footnote numbers (i.e. `[^1]`, `[^2]`, `[^3]`, etc.), followed by a colon (`:`) and citation, like this:

`[^1]: Katie Kitamura, *A Separation* (New York: Riverhead Books, 2017), 25.`

`[^2]: Sharon Sassler and Amanda Jayne Miller, *Cohabitation Nation: Gender, Class, and the Remaking of Relationships* (Oakland: University of California Press, 2017), 114.`

On the front end of your essay page, your footnote number will automatically link down to the proper citation.
To see this in action, look at the cited text below, and click on the blue `1` and `2` footnotes at the end of each line.
When you click on them, you'll be taken to the `Example Notes` section at the bottom of the page.

Example text to be cited.[^1]

Yet more text to cite.[^2]

### Now try it yourself

1. In your GitHub repository, locate and click on the "pages" folder.  
2. Inside the "pages" folder, click on the file titled "essay-01.md." Then select the pencil button in the top right corner of the `essay-01.md` file to open editing mode. 
3. Locate the sentences you wrote last week to describe your topic graph.
4. At the end of one of those sentences, add `[^1]`.
5. Scroll to the bottom of the `essay-01.md` file.
6. At the bottom of the file, add a heading 2 with the title "Notes," like this: `## Notes` (you may already have `## Notes` in your essay file. If it's already there, just ignore this step!).
7. Two lines below the `## Notes` heading, add this citation: `[^1]: John D’Agata, ed., *The Making of the American Essay* (Minneapolis: Graywolf Press, 2016), 19–20.`
8. Notice the asterisks in the middle of that citation? Remember, they make the text look italicized on the front end of your webpage. You'll probably use asterisks quite a bit in your citations, for book titles and journal titles!
9. Scroll down to the bottom of the file and type a commit message into the "Commit changes" text box.
10. Click the green "Commit changes" button to save your changes.
11. Head over to where you opened your "Essay In Progress" page in a different tab or window.
12. Wait a minute or two, then refresh the "Essay In Progress" page.
13. Once you refresh your site, you should see your changes.
14. The updates may take a few seconds to a few minutes to appear, so hold tight and keep refreshing if you don't see them right away.

### Horizontal Line Breaks

Sometimes you may want to add greater distinction between sections of your essay.
You can do this by adding a "horizontal line break," which is a horizontal line that stretches across the width of the page.

Horizontal line breaks are easy to do in Markdown.
Simply add three hyphens in a row to a new line, and make sure the line with the hyphens is preceded and followed by one blank line, like this:

```

---
```

### Opening hyperlinks in a new tab

Last week we learned how to create hyperlinks in Markdown, like this:

`[GitHub Help](https://help.github.com/)`

You probably noticed that hyperlinks created this way cause a new website to open in your browser's *current tab*.
Sometimes this is what you want to happen, but there will be other times where you'd like a link to open in a *new browser tab* when a user clicks on it.
To make this happen, you'll need to copy and paste the snippet of text below to the *end* of your hyperlink parentheses:

Copy this: `{:target="_blank" rel="noopener"}`

And paste it after the parenthese in your hyperlink: 

`[GitHub Help](https://help.github.com/){:target="_blank" rel="noopener"}`

This will ensure that your link opens in a new tab, like this: [GitHub Help](https://help.github.com/){:target="_blank" rel="noopener"}

### Now try it yourself

1. Click the pencil button at the top right of your `essay-01.md` file to open editing mode.
2. Scroll down the file to where you added the `[^1]` after a sentence.
3. Two lines below the `[^1]`, add three hyphens: `---`. Make sure these are on a line by themselves, there should be no text on the lines directly preceding or following the line with the hyphens.
4. Two lines below the hyphens, add this hyperlink: `[GitHub Help](https://help.github.com/)`
5. Then ensure it opens in a new tab by adding this text right after the parentheses in your hyperlink: `{:target="_blank" rel="noopener"}`
6. Scroll down to the bottom of the file and type a commit message into the "Commit changes" text box.
7. Click the green "Commit changes" button to save your changes.
8. Head over to where you opened your "Essay In Progress" page in a different tab or window.
9. Wait a minute or two, then refresh the "Essay In Progress" page.
10. Once you refresh your site, you should see your changes.
11. The updates may take a few seconds to a few minutes to appear, so hold tight and keep refreshing if you don't see them right away.

### Table of contents

You have the option to title different sections of your essay if you'd like.
To do this, use the various heading sizes that we learned last week:

`# Heading 1`

`## Heading 2`

`### Heading 3`

You can have multiple headings of the same type throughout your essay, and nest headings hierarchically just as you would an outline, like this: 

```
# First Heading 1

## First Heading 2

# Second Heading 1

## Second Heading 2
```

**Remember, always separate a heading from the text below it with a blank line.** 

If you do incorporate headings, you'll probably find it convenient to make use of the table of contents feature at the top of the essay.

The table of contents is generated from the line near the top of your `essay-01.md` file that looks like this:

`{% raw %}{% include feature/nav-menu.html sections="Introduction;Conclusion;Notes" %}{% endraw %}`

If you don't see that line, you may have deleted it from your file already.
That's okay!
Just add it back in for now by copying and pasting this: 

`{% raw %}{% include feature/nav-menu.html sections="Introduction;Conclusion;Notes" %}{% endraw %}` 

right above your essay title in your `essay-01.md` file.

Look closely at this line of text: 

`{% raw %}{% include feature/nav-menu.html sections="Introduction;Conclusion;Notes" %}{% endraw %}`.

Let's call this the "Table of Contents Include."

See the word `sections`?

`sections` is followed by an equals sign (`=`) and three words separated by semicolons and encased with quotation marks.

The three words inside the quotation marks are headings in the default `essay-01.md` file:

`## Introduction`

`## Conclusion`

`## Notes`

Take a look at the front end of your essay page.
Immediately underneath the navigation bar, there's a box that contains the word "Contents" followed by the links "Introduction," "Conclusion," and "Notes."
Click on any of these links and your page will automatically scroll down to the specified section.

If it doesn't scroll to the section, it might be because you've already deleted that heading from your essay.
In order for the contents box to work correctly, the word in the Table of Contents Include needs to match a heading somewhere in your essay.
Your heading just needs to be preceded by one or more pound signs (`#`) (it doesn't matter how many). 

### Now try it yourself

1. Back in your your GitHub repository, click the pencil button at the top right of your `essay-01.md` file to open editing mode.
2. Add a new heading by copying the following: `### My First Subheading`, and pasting it into the `essay-01.md` file somewhere after the `## Introduction` heading but before the `## Conclusion` heading.
2. Locate the Table of Contents Include: `{% raw %}{% include feature/nav-menu.html sections="Introduction;Conclusion;Notes" %}{% endraw %}`
3. In the Table of Contents Include, add your new heading and a semicolon between the words "Introduction" and "Conclusion," like this: `"Introduction;My First Subheading;Conclusion;Note"`
4. Scroll down to the bottom of the file and type a commit message into the "Commit changes" text box.
5. Click the green "Commit changes" button to save your changes.
6. Head over to where you opened your "Essay In Progress" page in a different tab or window.
7. Wait a minute or two, then refresh the "Essay In Progress" page.
8. Once you refresh your site, you should see your changes.
9. The updates may take a few seconds to a few minutes to appear, so hold tight and keep refreshing if you don't see them right away.

You can add, edit, and delete as many headings in your Table of Contents Include as you'd like!

And if you decide you'd prefer not to have a Table of Contents on your essay, you can simply delete this line: 

`{% raw %}{% include feature/nav-menu.html sections="Introduction;Conclusion;Notes" %}{% endraw %}`

from your `essay-01.md` file and it will disappear from the front end.

---

## Step 4. Add an image to your essay

{% assign topicdocs = site.data.topic-data %}

<table class="table table-striped">
    <thead>
       <tr>
          <th>Description</th>
          <th>Voyant Link</th>
       </tr>
    </thead>
    <tbody>
    {%- for t in topicdocs -%}
    <tr>
       <td class="topic">{{ t.description }}</td>
       <td class="words"><a class="btn btn-outline-success" href="{{ t.voyant-link }}" target="_blank" rel="noopener">View in Voyant Tools</a></td>
    </tr>
    {%- endfor -%}
    </tbody>
</table>

---

## Step 5. Activity

---

## Example Notes

[^1]: Katie Kitamura, *A Separation* (New York: Riverhead Books, 2017), 25.

[^2]: Sharon Sassler and Amanda Jayne Miller, *Cohabitation Nation: Gender, Class, and the Remaking of Relationships* (Oakland: University of California Press, 2017), 114.