---
title: Tips for the Multimedia Essay
nav: In-Progress Essay
permalink: /essay01.html
order: 7
---

{% comment %}{% include alert.html text="This page is under construction! Visit again soon for the finished product." color="danger" align="center" %}{% endcomment %}

This week you'll continue writing your in-progress multimedia essay, using the skills you've learned throughout your recent Labs.

---

## Minimum number of visualizations to include

Please include at least **two** visualizations into your Essay in Progress:
***This can be two topic graphs, two Voyant visualizations, or one topic graph and one Voyant visualization. Whatever supports your argument the best!***

You can include *more* than two visualizations if you'd like, but the minimum should be two.

---

{:#do-not-delete}
## What ***Not*** to delete

Write your essay content into the `essay-01.md` file, just as we have our practice content the past couple weeks.
Right now you likely have a lot of extra material in your `essay-01.md` file.
It will probably help you to delete most of it, but be sure that you *don't* delete the following:

**Don't Delete** the frontmatter at the top of your page:

```
---
title: Essay 1
layout: about
permalink: /essay-01.html
---
```

**Don't Delete** the "Notes" heading, towards the bottom of your page. 
You'll add all of your citations below this "Notes" heading:

`## Notes`

You **may or may not** want to delete the table of contents at the top of the page. 
This is up to you!
To delete it, simply this line of text from your `essay-01.md` file:

`{% raw %}{% include feature/nav-menu.html sections="Introduction;Conclusion;Notes" %}{% endraw %}`

If you've done the last two Labs, you've added at least one topic graph, like this:

`{% raw %}{% include feature/line-chart.html data="sotu-20th-century" topic="Example Topic" %}{% endraw %}`

and one Voyant visualization, like this:

``

If these are the visualizations you'd like to use as supporting evidence for your essay, then keep them in your `essay-01.md` file!

Or, if you want to include other visualizations, follow the steps from the [Topic Modeling](/topic-modeling.html){:target="_blank" rel="noopener"} and [Voyant Image Includes](/includes.html){:target="_blank" rel="noopener"} Labs to create new visualizations that support your topic.

---

## Some tips and clarifications

**Editing permissions**:
- When you post your essay's URL to the Lab Discussion, your classmates can *look* at your site, but they *cannot edit* it. Only you, as the owner of your GitHub repository, can edit the content on your site.

**Viewing State of the Union and Party Platform full text**:
- Your website comes complete with links to the full text of every State of the Union Address and Party Platform created in the 20th century. Find these links by first locating and clicking on the "Data" tab in your site's navigation menu, then using the "Search" box at the top right of the table to filter by president, candidate, or year. When you click on a documents's link, it will take you to the full text hosted by the University of California Santa Barbara’s [American Presidency Project](https://www.presidency.ucsb.edu/documents){:target="_blank" rel="noopener"}.

---

## Image resources

Even though so far we've we only practiced adding images from Voyant Tools, now that you know how to add images to your multimedia essay, you can use images from other resources, too!

**NOTE that including images other than Voyant visualizations *is not required* for your Essay in Progress.** This is something to think about for the future.

These might include images of primary sources that you've found from the University of Idaho's Digital Collections, for instance:

- <https://www.lib.uidaho.edu/digital/collections.html>{:target="_blank" rel="noopener"}

Or you might find useful images on Wikimedia Commons:

- <https://commons.wikimedia.org/wiki/Main_Page>{:target="_blank" rel="noopener"}

Just remember to keep copyright in mind as you think about incorporating images into your essay. 

If you do use images from the U of I Digital Collections or Wikimedia, you'll want to be sure to include a link to where you found the image in the **Image link** option of the "Generate Include" form, and describe where you found the image in the image's caption, or in the text immediately above or below your image.

You probably noticed in the "Generate Include" form that there is an option to include PDFs, too. 
For example, you might want to include a historical document that you find in the UI Digital Collection or in another university's Digital Collections.

The PDF include works the same way the image include works--simply upload your PDF to the "objects" folder in your GitHub repository and then it will appear in the "Generate Includes" form on your website.
Fill out the form to generate the pink "include" code that you need to paste into your `essay-01.md` file.

---