---
title: Splitting stories like a journalist
date: 2018-12-08
---
When people are new to (agile) software development, I have found that splitting stories can be a confusing and difficult exercise for many. Splitting (also synonymous with slicing) stories is the activity of dividing stories too big for effective development into new, smaller, stories.

Many good techniques and tips for splitting stories exists already (some linked to at the end of this post). Yet, I’d like to introduce **a simple alternative to splitting stories, that doesn’t care about story formats, software development terms, and other jargon.**

> “The Five Ws (sometimes referred to as Five Ws and How, 5W1H, or Six Ws) are questions whose answers are considered basic in information gathering or problem solving. They are often mentioned in journalism, research and police investigations.”
> 
> [Five Ws – Wikipedia](https://en.m.wikipedia.org/wiki/Five_Ws)

**Splitting stories like a journalist** is asking questions, using the the Five Ws and How, to learn more about a story and expand our thinking about how it can be divided into smaller stories. The questions all start with either What, Why, When, Where, Who, or How.

## Splitting stories using the Five Ws and How on the story’s solution, problem, and context.

{% image "./splitting-stories-like-a-journalist-illustration.png", "" %}

## Example: “Formatting toolbar”

To demonstrate how this might work, we’ll continue with an example.

* “**What** is the story about?”
* * “Oh, it’s a formatting toolbar. You know, like the one in Microsoft Word. Our users want to style their texts in different ways.”
* “**Why** do you users want to style their texts in different ways?”
* * “To improve readability and communication with their readers.”
* “**What** kind of different ways?”
* * “Well, we’re thinking a few. Making the text bold, in italics, different colors, and highlight words and phrases. That last one is often wished for by many.”
* “**Who** exactly wishes for highlighting of words and phrases?”
* * “That would be the editors. They want to be able to highlight certain words and phrases so that they more easily can provide feedback.”
* “**Who** are the other users?”
* * “The writers, of course!
* “**How** would writers like to style their text?”
* * “It’s the writers whom asked for being able to make their text in italics, and sometimes bold. To emphasize certain words, dialogue, and so on.”
* “**When** would our users use the formatting toolbar?”
* * “Writers use our service night and day. You never know when they get the inspiration for their next masterpiece. Editors, they’d would use it at work.”
* “**Where** are they using our service?”
* * Writers use all our applications. Editors, they only use it from their desktop computers at work. They don’t really care about the mobile app or web.”

## What we learned from our questions

Alright. Before we continue, let’s take a look at what we’ve learnt already:

* There are two kinds of users for the formatting toolbar: writers and editors.
* Writers and editors both need styling options, but different actual options.
* Writers use the service provided day and night, from anywhere.
* Editors, however, only use the desktop app.

## What’s next?

That should give you an idea about how the Five Ws and How can be used to explore and expand our understanding of a story. From this short conversation there’s already quite a few opportunities for splitting the original story, “formatting toolbar”, to smaller stories, which we then can ship one after another.

Since there’s also, in this example, fewer styling alternatives needed for each kind of user. A toolbar might even not be needed. Maybe there’s a simpler user interface that is available now that we don’t need as many styling options.

I hope that gave some ideas of how you can work with dividing stories into smaller stories. And when you’re ready to level up your game, I suggest you use the same questions on the story’s problem statement and context as well, and not just on the proposed solution.

If you have any story splitting techniques or tips to share. Please do, below in the comments.