---
title: Text Analysis With Voyant
nav: Voyant
permalink: /voyant.html
topics: Content; Markdown; Includes
order: 3
description: >
    This text is a 'section description'. 
---

---

**Goals**: Explore at least two corpora of text in Voyant; use the Cirrus, Trends, and Summary visualizations to make some observations about each corpus

**Estimated Time to Complete**: 45 minutes

---
{% include alert.html text="This page is under construction! Visit again soon for the finished product." color="danger" align="center" %}

# Use Voyant to Explore Text

Last week, we learned about text analysis, a method of finding patterns across a large collection of texts by looking at characteristics like word frequency (how many times words appear) and word co-occurrence (what words appear near one another).

This week, we're going to explore our two corpora of texts (20th-century State of the Union Address and Party Platform texts) using [Voyant Tools](https://voyant-tools.org/){:target='_blank' rel='noopener'} and following the steps below.

Before we begin, however, a note on our data:

As you explore the visualizations in this activity, you might find that you want to read a president's State of the Union Address or a candidate's Party Platform in full.
The 20th-century text we are working with was taken from UC Santa Barbara's [American Presidency Project](https://www.presidency.ucsb.edu/documents){:target='_blank' rel='noopener'} site.
To quickly access the full text of an Address or Platform statement on the American Presidency Project site, use this table: <https://learn-static.github.io/text-analysis/data.html> to search for the president/document in question, and click the corresponding link in the table to view the full text.

## Step 1. Open a Corpus in Voyant

Determine whether you'd first like to look at State of the Union Addresses or Party Platforms, and click the corresponding button below:

<div class="text-center" markdown="1">
<div class="mx-1 pt-3" markdown="1">
{% include button.html text="20th-Century State of the Union Addresses" link="https://voyant-tools.org/?corpus=3331b9ec3186b714ca53835d5b3ed722" color="success" %}
</div>
<div class="mx-1 py-1 pb-3" markdown="1">
{% include button.html text="20th-Century Party Platforms" link="https://voyant-tools.org/?corpus=58d4b2d396da18270928ed9fa8066005" color="success" %}
</div>
</div>

You've now opened a set of documents in the Voyant Tools platform. 
Your webpage will be broken into five different visualizations, looking something like this:

{% include figure.html img="partyplatforms-homepage.png" alt="image of Voyant homescreen showing visualizations of 20th-century party platforms" caption="Voyant homescreen showing visualizations of 20th-century Party Platforms" width="75%" %}

## Step 2. What Am I Looking At?

Let's take the State of the Union Addresses as an example.
Your instructors have separated each Address into a separate document, then uploaded all of those documents at once into Voyant.
For example Woodrow Wilson's Address from 1917 is in a file titled 1917-Woodrow-Wilson, the text from Richard Nixon's 1970 Address is in a file titled 1970-Richard-M-Nixon, etc. 
Once these files are uploaded to Voyant, Voyant processes them in several different ways.
Let's take a closer look at a few of them.

## Step 3. Word Clouds

Remember the "bag of words" approach we encountered last week, where a computer takes all the words from a corpus of documents in no particular order and counts the number of times they appear?
Voyant uses this method to generate a word cloud, which shows the raw frequency of the top-appearing words in our corpus.

Look to the top left corner of your browser window.
See all the colored words jumbled together?
That's a word cloud.

Hover your mouse just above the word cloud content, to the right of the "Links" button in the toolbar.
Look for the icon of a box with an arrow pointing up and out of it. 
Click on this icon.

[image]

A popup will appear with the Title "Export."
Without clicking on anything options in the popup, click on the blue "Export" button in the bottom left of the popup.

[image]

This opens up the word cloud as a full-screen visualization.
(Note that you can also click on the box-arrow icon on any other visualization to view it in full-screen mode too).

Take a look at the words in this word cloud.
Do any surprise you?

Now let's adjust some parameters.
In the bottom left of the screen, find the slider to the right of the word "Terms." 
Slide it to the right.
What happens?
Is this change helpful?
Slide it back to the left to view less words.

Right now you are viewing a word cloud that's been generated from the entire 20th-century State of the Union Address corpus, by default.
If you'd like to view a word cloud generated from just one or a few chosen documents in the corpus, you can click on the button in the bottom left of the browser screen that says "Scale."
A list of all the documents in the corpus will appear.
Click one or more documents you'd like to see combined into a word cloud.

Do the words change a lot depending on the documents you select?

To go back to viewing a word cloud created from the entire corpus, click on the "Scale" button again, and select the "Corpus" option.
This will regenerate the word cloud from the full corpus.

Switch back over to your original Voyant browser tab (or click one of the buttons in the "Open a Corpus in Voyant" section of this page) to get back to the Voyant home screen.

## Step 4. Word Trends Over Time

On the Voyant Homescreen (the homescreen should look similar to the image below), find the "Trends" visualization in the top right corner of the browser window.

{% include figure.html img="partyplatforms-homepage.png" alt="image of Voyant homescreen showing visualizations of 20th-century party platforms" caption="Voyant homescreen showing visualizations of 20th-century Party Platforms" width="75%" %}

Hover your mouse in the toolbar just above the visualization, next to the "Document Terms" button, until you see the icon of a box with an arrow pointing up and out of it. 
Click on this icon.

[image]

A popup will appear with the Title "Export."
Without clicking on anything options in the popup, click on the blue "Export" button in the bottom left of the popup.

[image]

This opens up the Trends graph as a full-screen visualization.

The Trends graph shows you the relative frequencies of words used over time.
Remember relative frequency from last week? 
Relative frequency is number of times a word appears in a text, relative to the size of that text. 
This is in comparison to raw frequency, which is the number of times a word appears in a text.
When we looked at our word cloud, we were looking at raw frequency.
When we look at this Trends graph, we are looking at relative frequency, or the relative number of times a word appears in each of the texts in our corpus.

Voyant gives us some default terms to visualize at first.
You can find these words at the top of the visualization, above the line graph (recognize any of them from the word cloud?).
Each word has a circle with a color to the left of it. 
That color corresponds to a line on the graph.
You can click on one of these default terms to make it disappear from the graph, then click on it again to make it reappear.

You probably have other terms you'd like to visualize besides the default terms that Voyant chose for you.
Let's get rid of the default terms and enter some words we'd like to investigate.

Look in the very bottom left corner of your browser window and locate a blank text box with a dropdown to the right of it.
Click into the text box.
A list will pop up above the text box that contains all the terms currently on the graph.
Ignore this list and type in your own term.
For instance, type the word "war" into this box.
You'll see a list of options for war appear in the list above the text box.
Click on the very top option (war*).
The asterisk is a wildcard symbol that tells Voyant to select not only the word "war," but also any words that start with the letters "war."

Once you've chosen war, your graph should change so that the only word at the top is "war*".
Let's add another word.
Without deleting "war*", click into the text box in the bottom left corner of the browser window again.
This time, type in the word "peace."
Select "peace*".
Now analyze your graph.
Are war and peace mentioned most frequently by the same people, in the same time periods?

To get rid of the terms war and peace, click on the "x" that appears to the right of each of them in the text box.
Add your own words to the text box and have fun exploring!
Keep your word cloud in mind--do any of the words that appear in the word cloud display surprising patterns in the Trends graph?

Note that if you'd like to visualize the data in a format other than a line graph you can click on the button titled "Display" in the bottom left corner of the browser window, and select from any of the options that appear.
You can also reset the Trends graph to the default words Voyant chose for you by clicking on the "Reset" button in the bottom left corner of the browser window.