# Lists, Details and Images, Oh my!

### Lists

Let’s learn about lists! Lists can be bulleted or numbered.

- This is an example of a bulleted list
- Hello
- world!
1. This is an example of a
2. Numbered list
3. wow
4. so cool

So what tags do we use? It’s actually quite simple. Here’s an example:

```html
<h3>The colors of the rainbow are:</h3>
<ul> <!-- Unorganized List (Bulleted) -->
	<li>Red</li> <!-- List item -->	
	<li>Orange</li>
	<li>Yellow</li>
	<li>Green</li>
	<li>Blue</li>
	<li>Indego</li>
	<li>Violet</li>
</ul>
<h3>How to bake a cake:</h3>
<ol> <!-- Organized List -->
	<li>Get materials</li>
	<li>Mix them together :O</li>
	<li>Bake the cake</li>
	<li>And you're done. You should now have a cake. This has been a very detailed tutorial for making a cake</li>
</ol>
```

Awesome right?

---

### Details

The <details> element is an element that creates a dropdown menu that will show you more details when clicked. Basically it’s just expandable text. (For example you could create a learn more dropdown with this).

Example:

```html
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
<details>
	<summary>Read More</summary> <!-- Make sure all of your details have a summary otherwise you'll just get the regular old boring "More details"-->
	<p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
</details>
```

<details>

Peek-a-boo!

</details>

### Images

Want to put a snazzy pic into your website? Here’s how!

Images are inserted using the <img> tag. Img is one of those tags that don’t need a closing tag. If you just use the tag on it’s own, nothing will happen. Instead you seed to set the “src” attribute. Attributes are like settings for tags that you put inside of them. For example, to set the src attribute of an img tag you would do:

```html
<img src="(url)">
```

Attributes work on any tag but certain attributes will only work on certain tags.  Want to add multiple attributes? It’s easy!

```html
<img src="url" width="100px">
```

As you can see all attribute decelerations have to start and end with a space to separate them. You start by adding a space in between the name of the tag and the closing bracket (>). Then you type the name of the attribute followed by an equals sign and quotes. Inside the quotes you put the value of the attribute.

What about changing the source of an image?

The way that you tell the computer what image to show is with the src attribute we just talked about. The src element needs to include a **direct url** to the image. A direct url would be something like `https://example.com/image.png` and NOT `https://example.com/coolimage` The url doesn't have to end in .png, just an image file like png, jpeg, webp, etc.

```html
<!-- This is an example of a direct link that leads right to an image. Paste this link into your browser and you should only see the image on your screen.-->
<img src="https://i.imgur.com/keJY0gV.png">

<!-- This is an example of a NON direct link to a page that contains other content. The computer doesn't understand this, so your image won't show up. -->
<img src="https://imgur.com/keJY0gV">
```

![](https://images.unsplash.com/photo-1636955779321-819753cd1741?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwxNDIyNzR8MHwxfGNvbGxlY3Rpb258NXwzMTcwOTl8fHx8fDJ8fDE2MzcxODg4OTU&ixlib=rb-1.2.1&q=80&w=1080)

Example of an image from Vackground on Unsplash

Great! Now you’re a master at Lists, Details and Images! Try and create something cool with your new skills. See you next time!
