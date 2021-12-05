# Markdown-Study-Time

Source project ini [Markdown Guide](https://www.markdownguide.org/) dan [Github Docs](https://docs.github.com/).

# What is Markdown?

Markdown is a lightweight markup language that u can use to add formatting elements to plaintext documents. Created by John Guber in 2004, Markdown is now onr of the world's most popoular markup languages.

# Basic writing and formatting syntax

## Headings

to create heading, add on to six # symbols before your heading text. The number of # you use will determine the size of the heading. for example:

```
# The largest heading
## The second largest heading
###### The smallest heading
```

and the rendered output must be like this:

# The largest heading

## The largest second heading

###### The largest smallest heading

## Bold
This text is **bold**.  
**text all bold**

## Italic
*hello*.  
Muhammad _Ricky_ Firdaus

## Bold and Italic
This text is ***really important***.

## All bold and italic
**_All text is important_**.

## Strikethrough
~~This was mistaken text~~

## Blockquotes
> To create a blockquotes, add a > in front of paragraph.

## Blockquotes with multiple paragraphs 
> blockquootes one  
> blockquootes two  
> blockquootes three  

## Nested Blockquotes
> blockquotes one  
>
>> blockquotes two and blockquotes three  

## Blockquotes with Other Element  
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

## Ordered List
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

## Unordered List
added dashed ( - ),asterisk( * ),or plus sign( + ) in front of line items. Indent one or more itemsto create a nested list.
- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

## Starting Unordered List Items With Numbers
u can use blackslash ( / )
- 1968\. A great year!
- I think 1969 was second best.

### Adding elements in list 
* This is the first list item.
* Here's the second list item.

    I need to add another paragraph below the second list item.

* And here's the third list item. 

### Blockquotes 
* This is the first list item.
* Here's the second list item.

    > A blockquote would look great below the second list item.

* And here's the third list item.

# Code Blocks
1. Open the file.
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3. Update the title to match the name of your website.

# Quoting code
To format code or text into its own distinct block, use triple backticks
Some basic Git commands are:
```
git status
git add
git commit
```

# Horizontal Rules
***

---

________________

# Image 
You can display an image by adding ! and wrapping the alt text in[]. Then wrap the link for the image in parentheses ().

### Link Images
To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses.
[![An old rock in the desert](/assets/images/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)

# Links 
My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

### URL and Email Address
<https://www.markdownguide.org>
<fake@example.com>

### Formatting List
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).

# Reference-style Links
Reference-style links are a special kind of link that make URLs easier to display and read in Markdown. Reference-style links are constructed in two parts: the part you keep inline with your text and the part you store somewhere else in the file to keep the text easy to read.

### Formatting the First Part of the Link
The first part of a reference-style link is formatted with two sets of brackets. The first set of brackets surrounds the text that should appear linked. The second set of brackets displays a label used to point to the link you’re storing elsewhere in your document.

Although not required, you can include a space between the first and second set of brackets. The label in the second set of brackets is not case sensitive and can include letters, numbers, spaces, or punctuation.

This means the following example formats are roughly equivalent for the first part of the link:

[hobbit-hole][1]
[hobbit-hole] [1]

### Formatting the Second Part of the Link
The second part of a reference-style link is formatted with the following attributes:

The label, in brackets, followed immediately by a colon and at least one space (e.g., [label]: ).
The URL for the link, which you can optionally enclose in angle brackets.
The optional title for the link, which you can enclose in double quotes, single quotes, or parentheses.
This means the following example formats are all roughly equivalent for the second part of the link:

[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)
You can place this second part of the link anywhere in your Markdown document. Some people place them immediately after the paragraph in which they appear while other people place them at the end of the document (like endnotes or footnotes).

