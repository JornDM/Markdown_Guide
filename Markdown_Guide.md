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

example:

**_This is an itallic bold sentence_**

Code:

```Markdown
**_This is an itallic bold sentence_**
```


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
If you need to refer to a quote from another source, want to mention a quote written in a newspaper, ... then you need to use Markdown's blockquotes-syntax! 
<br>
<br>
This is a sentence/paragraph that has been formatted to draw attention to the reader.
<br>
<br>
Example: <br>
> "I like learning Markdown!!!" 


To create this, you just have to add a ">" in front of the text you want to represent as a blockquote
<br>
<br>
Other Example: <br>
> "Blockquotes are not that hard!"

<br>
Code:

```Markdown
> "Blockquotes are not that hard!"
```

<br>
You can also use this ">" sign for multiple lines in a paragraph. This is usefull when your quote spans over multiple paragraphs.
<br>
<br>
Example:

> His words seemed to have struck some deep chord in his own nature. Had he spoken
of himself, of himself as he was or wished to be? Stephen watched his face for some
moments in silence. A cold sadness was there. He had spoken of himself, of his own
loneliness which he feared.
>
> —Of whom are you speaking? Stephen asked at length.
>
> Cranly did not answer.

Code:

```Markdown
> His words seemed to have struck some deep chord in his own nature. Had he spoken
of himself, of himself as he was or wished to be? Stephen watched his face for some
moments in silence. A cold sadness was there. He had spoken of himself, of his own
loneliness which he feared.
>
> —Of whom are you speaking? Stephen asked at length.
>
> Cranly did not answer.
```

You can also combine blockquotes with itallic and bold styling, or even links and images. 

Example:
>He left her quickly, fearing that her intimacy might turn to jibing and wishing to be out of the way before she offered her ware to another, a tourist from England or a student of Trinity. Grafton Street, along which he walked, prolonged that moment of discouraged poverty. In the roadway at the head of the street a slab was set to the memory of Wolfe Tone and he remembered having been present with his father at its laying. He remembered with bitterness that scene of tawdry tribute. There were four French delegates in a brake and one, a plump smiling young man, held, wedged on a stick, a card on which were printed the words: _VIVE L'IRLANDE_!

Code:

```Markdown
>He left her quickly, fearing that her intimacy might turn to jibing and wishing to be out of the way before she offered her ware to another, a tourist from England or a student of Trinity. Grafton Street, along which he walked, prolonged that moment of discouraged poverty. In the roadway at the head of the street a slab was set to the memory of Wolfe Tone and he remembered having been present with his father at its laying. He remembered with bitterness that scene of tawdry tribute. There were four French delegates in a brake and one, a plump smiling young man, held, wedged on a stick, a card on which were printed the words: _VIVE L'IRLANDE_!
```

## Lists
In this part of the guide, we'll take a closer on look on **Lists**.
<br>
There are 2 types of links in Mardkwon: **Ordered** and **Unordered**.
<br>
Let's first learn a bit about unordered lists.
<br>
<br>
To create this kind of list, you have to put in front of every item you want the list to contain an asterisk ( * ) and after this asterisk you put a space. <br>

Example:
* Milk
* Butter
* Chocolate
* Geforce RTX 3060

Code:
```Markdown
Don't forget to add the space!
* Milk
* Butter
* Chocolate
* Geforce RTX 3060
```

Let's now take a look at the other variant, namely **Ordered Lists**.

This kind of list is different from the other one because it contains a number in front of earch element in that list.

And just like that, you make this kind of list. Just add a number (1,2,3 ...) in front of each element, followed by a dot ( . ) and then a space.

Example:

1. Emerald
2. Ruby
3. Sapphire

Code:
```Markdown
Don't forget to add the space and dot!
1. Emerald
2. Ruby
3. Sapphire
```

Of course, you can also add itallic or bold styling to each element in the list.

Example:
* **Azalea** (_Ericaceae Rhododendron_)
* **Chrysanthemum** (_Anthemideae Chrysanthemum_)
* **Dahlia** (_Coreopsideae Dahlia_)

Code:
```Markdown
* **Azalea** (_Ericaceae Rhododendron_)
* **Chrysanthemum** (_Anthemideae Chrysanthemum_)
* **Dahlia** (_Coreopsideae Dahlia_)
```

There is also an option to **nest your list**. <br>
This means that you can put **more depth in your lists.** <br>
You can do this by adding an extra space after the space you have already put behind the asterisk ( * ).

Example:
* Tintin
  * A reporter
  * Has poofy orange hair
  * Friends with the world's most awesome dog
* Haddock
  * A sea captain
  * Has a fantastic beard
  * Loves whiskey
    * Possibly also scotch?

Code:
```Markdown
Don't forget to add the extra space!
* Tintin
  * A reporter
  * Has poofy orange hair
  * Friends with the world's most awesome dog
* Haddock
  * A sea captain
  * Has a fantastic beard
  * Loves whiskey
    * Possibly also scotch?
```

Lastly, there is also an option to give more information about a certain list-item. 
You just do this by adding the content beneath the item and making sure there is a blank line inbetween. 
It would look like this:
<br>
<br>
1. Crack three eggs over a bowl.

 Now, you're going to want to crack the eggs in such a way that you don't make a mess.

 If you _do_ make a mess, use a towel to clean it up!

2. Pour a gallon of milk into the bowl.

 Basically, take the same guidance as above: don't be messy, but if you are, clean it up!

3. Rub the salmon vigorously with butter.

   By "vigorous," we mean a strictly vertical motion. Julia Child once quipped:
   > Up and down and all around, that's how butter on salmon goes.
4. Drop the salmon into the egg-milk bowl.

   Here are some techniques on salmon-dropping:

   * Make sure no trout or children are present
   * Use both hands
   * Always have a towel nearby in case of messes

   
