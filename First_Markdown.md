# My Hello World in Markdown

First, I learned that you do not _run_ Markdown files (xD), you see a preview of it.

That being said, let's start again with the Hello World. This file is a step-by-step exercise of the Markdown tutorial available in [markdowntutorial.com](https://www.markdowntutorial.com)

# Italics and Bold
## Italics
In Markdown, you use the underscore (_) to apply Italic style. For example, the following sentence:
```
Writing in Markdown is _not_ that hard!
```
Will be displayed as:

* Writing in Markdown is _not_ that hard!

It seems that (*) has the same effect as the undescore, i.e.:

```
Writing in Markdown is *not* that hard!
```
Will be displayed as:

* Writing in Markdown is *not* that hard!

## Bold
For Bold, you use two asterisks (**), i.e.:

```
I **will** complete these lessons!
```

Will be displayed as:

I **will** complete these lessons!

## When using both Italic and Bold
The tutorial recommends to place the asterisks outside in order to make it more legible. However, it also will be displayed if you place the underscore first.
I.e.:
```
**_This_** will be displayed the same as _**this**_
```
**_This_** will be displayed the same as _**this**_

## Headers
At this point, I've been using headers one and two, but you can go down to header six, like this:
### This is an
#### example of
##### subtypes of
###### headers in Markdown.

## Links and References
### Links
At the beggining of this file, I used a link to the Markdown tutorial website. This is done with the following structure:
```
[Link](someplace)
```
That is called an _inline link_. I.e.:
[My repo for this markdown tutorial](https://github.com/JuanD-Pimiento/Markdown-Hello-World)

### References
If you want to define a link just once, like it's done in the _References_ section of scientific literature, you change the set of parentheses for a second set of brackets.

_From the Markdown tutorial website, the structure is as follows:_
```
Here's [a link to something else][another place].
Here's [yet another link][another-link].
And now back to [the first link][another place].

[another place]: www.github.com
[another-link]: www.google.com
```
I will define here the link of the [markdown tutorial website][md_tutorial_website] as a reference.

[md_tutorial_website]: https://www.markdowntutorial.com

It is worth noting that the definition of the reference itself is not displayed.

## Images
Adding images follows the same structure for links, just adding an exclamation point (!) at the beggining. For an inline image link, you would place it like this:
```
![Image](Link to the image)
```
I.e., loading an image of the ![Moon](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e1/FullMoon2010.jpg/330px-FullMoon2010.jpg). Here we just load it without modifying its size.

The text you write in the brackets is _Alternative Text_ provided to describe the image for the visually impaired.

We also can create references in order to define a link just once. The structure is the same for link reference, just adding the exclamation point at the beggining. I.e:

![Octopus][wikipedias_octopus]
![Squid][wikipedias_squid]

[wikipedias_octopus]: https://upload.wikimedia.org/wikipedia/commons/thumb/5/57/Octopus2.jpg/1280px-Octopus2.jpg
[wikipedias_squid]: https://upload.wikimedia.org/wikipedia/commons/thumb/e/e1/Sepioteuthis_sepioidea_%28Caribbean_Reef_Squid%29.jpg/250px-Sepioteuthis_sepioidea_%28Caribbean_Reef_Squid%29.jpg

## Blockquotes
The block quotes are sections to draw attention to the reader. You can add _"other Markdown elements, such as italics, images, or links."_ To generate a blockquote you simply place a "grater than" caret (>) before the text you want to put into the blockquote:
```
> The text
```
I.e.:
> "... Like the ceiling can't hold us"- Macklemore & Ryan Lewis in _Can't Hold Us_

To add the next line in the block you need to place the caret again. Like this:

> The _Octopus_ and the _Squid_ are **_Cephalopods_**
>
>![Octopus][wikipedias_octopus]
>
>![Squid][wikipedias_squid]

It has come to my attention that the text is displayed the same if I do not add empty newlines in between.

> The _Octopus_ and the _Squid_ are **_Cephalopods_**
Octopus
Squid

It'll be explained later in the paragraph formatting section.

## Lists
Lists are a piece of cake. You can add unordered and ordered lists (bullet points and numbers, respectively).

For a bullet point list you write something like this:
```
* Item 1
* Item 2
* Item 3...
```
And it'll be displayed as:
* Item 1
* Item 2
* Item 3...

For ordered lists you just write the number, place a period afterwards and the item of the list:
```
1. Item 1
2. Item 2
3. Item 3
```
And it'll be displayed like this:
1. Item 1
2. Item 2
3. Item 3

Lists can contain other Markdown elements, i.e.:
1. An Image ![The Octopus image again][wikipedias_octopus]
2. A [Link][md_tutorial_website]
3. And common text _with **styles**_, or plain text.

### Nested List
A Nested list is sublists, a list within an item of another list.
```
* Item 1
    * Item 1.1
    * Item 1.2...
* Item 2
    * Item 2.1
    * Item 2.2...
```
One can add sublists indefinitely, but usually 3 levels is enough.

### Identitation
If you need to add mor information, you could change the sublist for a text that is aligned with the list. You do that by identating the paragrap bellow the item of the list:
```
* Item 1
  Paragraph 1
* Item 2
  Paragrap 2
```
Identation with spaces or Tab is up to you.

You can add all the aforementioned Markdown elements in between the items of the list. I.e.:
1. An image

   An image of an octopus ![the octopus again][wikipedias_octopus]
   * An then a sublist
     * Of two levels
2. Text

   Then plain text
   1. Or text with **bold**
   2. > Or a quote"
   3. Or maybe a [Link][md_tutorial_website]

In this case the label of ordered list is not a nested sequence like 2.1, 2.2 and so on.

## Paragraphs
In markdown you can format paragraph with _soft brakes_ and **hard brakes**. The hard brakes would be the newlines made with _enter_ and make leave a spece between lines. A soft brake is made with two spaces and it tighten the paragraphs.

I.e.:

After this text I'll place a hard brake.

Now I'll place a soft brake  
This allows me to write in a newline without leaving such a big space like in the hard brake.

## The End
This step-by-step exercise following the [Markdown tutorial][md_tutorial_website] covers the basics of Markdown. In other exercises I'll cover "extended" implementations of Markdown, in order to write more creative md files.
