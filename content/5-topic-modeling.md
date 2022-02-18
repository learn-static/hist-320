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

`Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent maximus ex vitae odio condimentum molestie. Cras porta, metus non tempus pellentesque, odio libero porttitor lectus, vel eleifend enim enim cursus nibh. Mauris aliquam dignissim nunc eget viverra.` 

`Duis in nisl in enim iaculis scelerisque. Ut congue ipsum nisi, nec ultrices nulla porta vel. In ultrices erat orci, in imperdiet dui tempor non. Nam placerat non ante nec viverra.`

**Front end view**: 

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent maximus ex vitae odio condimentum molestie. Cras porta, metus non tempus pellentesque, odio libero porttitor lectus, vel eleifend enim enim cursus nibh. Mauris aliquam dignissim nunc eget viverra. 

Duis in nisl in enim iaculis scelerisque. Ut congue ipsum nisi, nec ultrices nulla porta vel. In ultrices erat orci, in imperdiet dui tempor non. Nam placerat non ante nec viverra.

But the following two paragraphs will merge into one paragraph when rendered on your webpage:

**Back end view**:

```
Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
Praesent maximus ex vitae odio condimentum molestie. 
```

**Front end view**: 

Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
Praesent maximus ex vitae odio condimentum molestie. 

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

Spend some time using these guidelines to content to your Essay in Progress for practice.
The content you add doesn't need to be your actual essay.
If you'd like to, you can delete most of the Markdown on the page, *except* for the frontmatter at the very top (looks like this): 
```
---
title: Essay 1
layout: about
permalink: /essay-01.html
---
```

When you're finished adding content to essay-01.md, commit your changes by adding a message and clicking the green "Commit changes" button at the bottom of the page, then wait a minute and refresh your Essay In Progress webpage to see the changes on the front end.

## Step 3. 

Remember our discussion of topic modeling that we had back in [Lab 2](/2-dh.html)?

Your instructors prepared each of our text corpora (20th-century State of the Union texts and Party Platform texts, respectively) by inputting them into a topic modeling tool, which analyzed and clustered groupings of words based on the probability that they share a similar "theme" or "topic."
We've included the outputs of this analysis in this repository, for you to label and visualize.

- Keep your website up in one window/tab, and your GitHub repository up in another window/tab.
- Navigate to the homepage of your GitHub repository by clicking on the <> Code tab in the top left of your browser window.
- Locate and click on the `_data` folder in your repository (should be near the top of your repository files)
- Once inside the `_data` folder, click on the `topics` folder.
- Inside the `topics` folder are a series of spreadsheets, each containing topics for a specified subset of documents in our corpora.

A description of each spreadsheet and its filename are listed in the table below:

{% assign topicdocs = site.data.topic-data %}

<table class="table table-striped">
    <thead>
       <tr>
          <th>Description</th>
          <th>Filename</th>
       </tr>
    </thead>
    <tbody>
    {%- for t in topicdocs -%}
    <tr>
       <td class="topic">{{ t.description }}</td>
       <td class="words">{{ t.filename-topics }}.csv</td>
    </tr>
    {%- endfor -%}
    </tbody>
</table>

- In the `topics` folder, locate the State of the Union 20th century file (`sotu-20th-century-topics.csv`), and click on it.
- Take a look at the "words" and "topicname" columns in this spreadsheet. Each "words" cell contains 10 words that our topic modeler has designated a topic, but it's up to us to label them. Your instructors have already named four of the topics: labor in America, American economy, America as world power, America at war. Now it's your turn to name or rename some of the topics in this spreadsheet. You're welcome to stick with the topic names your instructors picked, but if you understand those topics differently, you're also welcome to change their names. This is an inherently subjective process! Some names for topics in this spreadsheet might seem very obvious to you, while other topics contain words that don't seem to have any similarities at all. You don't need to name every topic in this spreadsheet, but you shoudl spend some time seriously thinking about them, and when you're ready to name/rename at least three topics, click on the pencil button to edit this file.
- When you click on the pencil button, you'll notice that the spreadsheet changes form, so that instead of cells, each column of information is separated by commas. That's because this is a "CSV" file (remember the file extension?: `sotu-20th-century-topics.csv`), and CSV stands for comma-separated-values. This means that you'll add your topic names after the very last comma in each row. For instance, you'd add a topic name to the first topic, `law country made government service navy commerce officers proper duty`, by typing in your topic name after the comma that comes after duty, like this:

```
topic,tokencount,words,topicname
0,45231,"law country made government service navy commerce officers proper duty",Example Topic
```

To edit a topic name, look for the topicname you want to edit (such as "labor in America"), delete it, and add your new topic name in its place.

Remember, the *only* thing you'll be editing in this file are the topic names, not the words in the topics themselves.

Now that you're in editing mode, add or edit at least three topic names, then scroll to the bottom of the page, add a commit message, and press the gree "Commit changes" button to save your changes.

Proceed to the next step to discover how to visualize the topics you've just named.

## Step 5. Visualize your topics

When we topic model a collection of texts, we not only get a set of topics (like the one we just looked at!), but we also get some data that shows *how much* a topic *appears* in a specific text. 
So, once we've determined that we think a topic should be named, "labor in America," we want to know *who talks the most about "labor in America"* out of all of our 20th-century State of the Union Addresses.
This is most easily visualized using a line graph that shows a topic's percentage in each document.
Your website will automatically generate a line graph just like this for every topic that you name.
Let's check out the graphs that were created for the topics you just named:

1. Click over to your browser tab/window where you have your website pulled up.
2. In the navigation bar for your website, locate and click on the label Topic Visualizations. A dropdown list will appear. Select "State of the Union 1900-2000."
3. This takes you to the visualization page for "State of the Union Addresses, 1900-2000." After the title and description, the first thing you'll see is a list of all of the topics you've named, along with the ten words that make up each of those topics.
4. Scroll down the page a bit until you see the first section titled "Line Chart." Below the words "line chart" you'll see the title of the data you're using (in this case, "State of the Union 20th century"). Then, you should see a topic name in bold, followed by that topic's words. Below the topic name is the graph of that topic. The x-axis represents each president's speech and the year they gave it, while the y-axis communicate percentage (0.02 = 2%, 0.10 = 10%, and so on), and each point on the graph represents the percentage that the topic appears in a document. Hover over a point with your mouse to see what year and which speaker that point represents, as well as its percentage.
5. All of the line graphs work in this same manner, so scroll down the page to view the graph for each of the topics you've named. Do the topics peak/dip across history when you expect them to? Do you notice anything surprising about a particular topic? Are there any topics you'd like to rename?

Spend as much time exploring the State of the Union topics and graphs as you'd like, then click back over to your browser window/tab that contains your GitHub repository, and navigate back to the `topics` folder.

Once in the `topics` folder, locate the Party platforms 20th century file (`party-platforms-20th-century-topics.csv`), and click on it. 
Your instructors have added a few topic names to this file, just as they did with the State of the Union 20th century file.
As you did above, select the pencil button to edit this file, and name or rename at least three topics by adding them after the last comma in a row.
Don't worry if you don't think your topic name matches the topic words exactly, this is just an exercise to get you thinking and hopefully inspire some questions about your research topic or what you're learning in this class.
Once you're ready to view the topics you've named, add a commit message and press the green "Commit changes" button at the bottom of the file, then wait a minute, and navigate over to your website to click on the Topic Visualizations tab and select "Party Platforms 1900-2000." 
Your new topics should appear as graphs on this page soon.
If you don't see them right away, wait a minute or two then refresh the page and your changes should appear.

## Step 6. More exploring

Since your Essay in Progress will be focused on the first half of the 20th century, your instructors have prepared some additional topics for you, just using the State of the Union Addresses and Party Platforms from 1900 to the 1940s. 
You can find these topic files in the `topics` folder, and you can edit them just as you did the full 20th-century topics above, then view their graphs on your website.
The only difference is your instructors did not pre-name any topics in these files for you, so its up to you to determine some topic names! 

1. Choose *at least one* of the following files, and name *at least two topics* in that file, then look at the resulting line graphs on your website.

<table class="table table-striped">
    <thead>
       <tr>
          <th>Description</th>
          <th>Filename</th>
       </tr>
    </thead>
    <tbody>
    {%- for t in topicdocs -%}
    {% if t.filename-topics contains '1900-1944' or t.filename-topics contains '1900-1945' %}
    <tr>
       <td class="topic">{{ t.description }}</td>
       <td class="words">{{ t.filename-topics }}.csv</td>
    </tr>
    {% endif %}
    {%- endfor -%}
    </tbody>
</table>

## Step 7. Activity

Explore all of the line graphs that you've generated, either from the 20th-century data sets or from the 1900-1944/45 data sets, and select one topic's graph that is especially interesting to you.

Look immediately underneath that graph, where you should see a section titled "Include Code," followed by a bracketed line of pink text, similar to this: 

`{% raw %}{% include feature/line-chart.html data="party-platforms-20th-century-all" topic="freedom and prosperity" %}{% endraw %}`

Copy the pink text and paste it under the title in your essay-01.md file.
This pink text is called an "include" and is a handy way to add any graph into your multimedia essay.
You'll be adding in images and pdfs using includes, too, but we'll cover those next week.

Underneath the include that you just pasted into your essay-01.md file, include two or three sentences that explain why this particular topic graph is interesting to you and/or relevant to your essay topic.
Make sure to add a commit message and push the green "Commit changes" button to save your changes, then view the graph and your new sentences on the Essay In Progress webpage on your website (remember you'll need to wait a few seconds and refresh the page to see your changes).

Paste a link to your Essay In Progress page as your response for this week's Lab Discussion.