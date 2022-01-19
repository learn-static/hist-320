---
title: Digital Humanities and Texts
nav: Digital Humanities
permalink: /dh.html
order: 2
---

{% include alert.html text="This page is under construction! Visit again soon for the finished product." color="danger" align="center" %}

---

**Goals**: Explore examples of Digital Humanities projects; Gain familiarity with concepts of Digital Humanities/Digital History, text as data, text analysis, and topic modeling

**Estimated Time to Complete**: 60 minutes

---

## Defining Digital Humanities

As you create your multimedia essay for this course, you will be engaging in the practice of Digital Humanities and Digital History.

At its most general, Digital Humanities can be defined as the process of utilizing technology to ask (and answer) traditional humanities questions in new ways.
Digital History is this process applied specifically to History. 

This definition is necessarily vague, as digital research in History can range from asking traditional humanities-oriented questions about digital media and computing technologies, to using computational tools and methods to investigate historical data.
(To show just how wide-ranging definitions of Digital Humanities can be, follow this link and refresh the page to view the creative and varying definitions that Digital Humanists have come up with to define what they do: <https://whatisdigitalhumanities.com/>{:target='_blank'})

Because of this, Digital Humanities projects can take a variety of forms.
Take a few minutes to explore two or three Digital Humanities projects recently nominated for the 2020 Digital Humanities Awards: <http://dhawards.org/dhawards2020/results/>.
Scroll down the page to check out the different categories of projects. 
Which categories appeal to you to the most?

Most importantly, when we engage in Digital Humanities and Digital History projects, it is not to *replace* traditional humanities research methods.
Rather, the digital tools we use can *extend* the possibilities of deep thinking and criticism that characterize the humanities.

In the case of this class, we'll be extending our understanding of 20th century American history by performing computational analyses on and visualizing patterns in historical texts (20th century State of the Union Addresses and Party Platform texts, to be exact), and communicating our findings via the digital medium of a web essay. 

> The logical question at this point might be, "Why do we need to do this?"

And the answer is we don't necessarily *need* to do it--it's true that you might not discover anything useful from our analyses or visualizations and decide that you never want to dabble in Digital History again, and that's fine!

However, we *are* going to do it in this course for the following reasons:
1. To introduce you to methods of gaining information from--and determining patterns across--large collections of primary resources when you don't have time to read them all (consider: over the course of the 20th century there are a total of 103 State of the Union Addresses and 57 Party Platform statements!). Of course, you'll want to read some of them, but taken as a whole the data outputs and visualizations can become another resource for you along with the primary and secondary sources you gather as you form arguments and opinions about the events and people that shaped 20th century American history.
2. To introduce you to the experience of writing for the web in a professional way. What you do with your multimedia essay after the course ends is up to you--but even if you choose never to make your essay publicly findable or even choose to delete it, during this class you will gain the experience of writing an essay in a space other than a Microsoft Word Document and integrating resources such as supporting images and documents into the text, an activity that can open up possibilities for creativity that aren't always present in a typical term paper.
3. To introduce some real-world technical concepts and skills in a fun, low-stakes way. In this class we'll be utilizing the popular web platform GitHub, where developers all over the world collaborate on projects and code, to store our files and create our websites. Rest assured, though, we will be doing ***no coding*** in this course! But you will walk away with some very basic real-world skills (i.e. familiarity with spreadsheets, Markdown, and GitHub) that just might come in handy some day in your future.

In sum, the best advice I can give you is to approach this project with an open mind.
We're not expecting you to become experts in Digital Humanities methods over the course of this semester, but we are asking that you give these tools a try because you just might walk away with a valuable new insight or skill.

## Getting Started

Below, you'll find introductions to the following three Digital Humanities concepts:

1. [Text as Data](#data)
2. [Text Analysis](#analysis)
3. [Topic Modeling](#modeling)

{:data}
### Text as Data

To undertake the text analysis we'll be doing in this course, we need to think of our texts as data, or as information that can be separated, organized, and analyzed. 
In the case of this project, we have two "types" of historical political texts: 20th century State of the Union Addresses and Party Platforms.
Each "type" of text can be considered a "body," or "corpus," which can then be split into smaller "documents"
In the case of our research for this course, it makes the most sense to delineate each individual address as a separate document within the State of the Union corpus, and each Party Platform as a separate document within the Party Platform corpus.

We've already separated the corpora into these documents, as individual text files, which you can view on GitHub:
- [State of the Union texts](https://github.com/learn-static/text-analysis/tree/main/_data/state-of-the-union/txt){:target='_blank' rel='noopener'}
- [Party Platforms](https://github.com/learn-static/text-analysis/tree/main/_data/party-platforms/txt){:target='_blank' rel='noopener'}

Now that we've begun thinking about each document as part of a dataset, we can also start to understand a document's *words* as data (or "units of analysis").

Here's a snippet of text from William McKinley's 1900 State of the Union address:

```
Fourth Annual Message: To the Senate and House of Representatives: At the outgoing of the old and the incoming of the new century you begin the last session of the Fifty-sixth Congress with evidences on every hand of individual and national prosperity and with proof of the growing strength and increasing power for good of republican institutions. [See APP Note.] Your countrymen will join with you in felicitation that American liberty is more firmly established than ever before, and that love for it and the determination to preserve it are more universal than at any former period of our history. The Republic was never so strong, because never so strongly entrenched in the hearts of the people as now. The Constitution, with few amendments, exists as it left the hands of its authors. The additions which have been made to it proclaim larger freedom and more extended citizenship. Popular government has demonstrated in its one hundred and twenty-four years of trial here its stability and security, and its efficiency as the best instrument of national development and the best safeguard to human rights. When the Sixth Congress assembled in November, 1800, the population of the United States was 5,308,483.It is now 76,304,799. Then we had sixteen States. Now we have forty-five. Then our territory consisted Of 909,050 square miles. It is now 3,846,595 square miles. Education, religion, and morality have kept pace with our advancement in other directions, and while extending its power the Government has adhered to its foundation principles and abated none of them in dealing with our new peoples and possessions. A nation so preserved and blessed gives reverent thanks to God and invokes His guidance and the continuance of His care and favor.
```

When we look at this block of text, as humans we can understand the relationship between the words--combined together to form the sentences above, they communicate meaning to us.
A computer, however, cannot determine the relationship between the words above: The text contains no computer-readable structure or relationships between the units of analysis (words).

Because it has no computer-readable structure, this text can be classified as **unstructured data**.
The computer processes the text as a **bag of words**, keeping track of the number of times the words appear (in other words, the "frequency" of the words), but not the grammar or order of the words.

When we use tools that interpret documents as bags of words, some exciting possibilities occur.
We can analyze raw word frequency and relative word frequency to get an idea of which words appear the most often across documents.
And we can produce "topics," or clusters of words, that emerge as themes across a corpus. 

To this end, we'll using the methods of Text Analysis and Topic Modeling, described below, our corpora of State of the Union and Party Platform texts.

{:analysis}
### Text Analysis

{:modeling}
### Topic Modeling

## Additional Resources

- Kathleen Fitzpatrick, 
[Reporting from the Digital Humanities 2010 Conference](http://chronicle.com/blogs/profhacker/reporting-from-the-digital-humanities-2010-conference/25473){:target='_blank'}, *ProfHacker*, July 12, 2010.


http://dhawards.org/dhawards2020/results/

http://www.cameronblevins.org/posts/topic-modeling-martha-ballards-diary/

https://tedunderwood.com/2012/04/07/topic-modeling-made-just-simple-enough/

https://www.oah.org/tah/issues/2016/february/new-forms-of-history-critiquing-data-and-its-representations/