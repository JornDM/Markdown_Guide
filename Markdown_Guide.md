# Markdown Guide 
In this file, you'll get a brief summary on how to write and work with Markdown! 
I've studied Markdown by following these links: 
<br>
<br>
[Markdown tutorial](https://www.markdowntutorial.com/)


## Itallic and Bold
1. Surround a word with '_' to make it _itallic_
2. Surround a word with 2 '**' to make it **bold**

Note: You can combine these 2 to make a word _itallic_ AND **bold** <br>
example -> **_This is an itallic bold sentence_**

## Headers
There are 6 types of headers, each decreasing in size as we go downwards. <br>
You can choose the size of the header by adding one or more #'s in front of a word/sentence. <br>
Example: <br>
The header that you can see atop this page ("Markdown Guide") is the biggest header possible. You can create such a header by adding just one #. <br>
## I am a smaller header than the first one (2 #'s)
### I'm an even smaller header than the header above (3 #'s)
...
###### I'm the smallest header possible (6 #'s)

<br>

## Links 
There are 2 types of links in MD. <br>
The first type we are going to talk about is called the "**Inline Link**" <br>
To make such a link, you have to surround it with square brackets ( [ ] ) and after that you have to surround the link itself with normal brackets ( ( ) ). <br>
<br>
Example: A sentence "Go to GitHub" that refers to the main GitHub page. <br>
[Go to GitHub](https://github.com/) <br>
<br>
```Markdown
Code: "[Go to GitHub] (https://github.com/)" Without the space inbetween!
```
<br>

The other type of link is called the "**reference link**". This kind of link is used to refer to an other place situated in the document.
<br>
I'll need to ask this part, didn't really fully understand

## Images
Now that we know how to create links, we can also add images to our Markdown-page. The syntax is (almost) identical.
<br>
<br>
Just like links, an image can be declared by using 2 styles. The only difference is that you have to add a exclamation point ( ! ) if you want to add an image.
<br>
<br>
The first style we are going to discuss is the **inline image link**. <br>
You can create such an image link by adding an !, wrap the **alt text** in square brackets ([ ]) and then wrap the link of the image in normal brackets ( ( ) )
<br>
<br>
Example: <br>
![Benjamin Bannekat](https://octodex.github.com/images/bannekat.png)
<br>
```Markdown
Code: ![Benjamin Bannekat](https://octodex.github.com/images/bannekat.png)
```
The other style is called "**Reference Image**".

You can kind a compare it with working with variables. An example:
```markdown
![Black cat][Black]

[Black]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg
```

This will give the following result in this document: <br>
![Black cat][Black]

[Black]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg


## Blockquotes

