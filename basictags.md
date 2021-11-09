## Basic Tags

Let's start by learning some basic tags for our body.

Locate the `<body>` tag on your html file and let's add our first tag!

We can start with a heading so that we can have a title for our webpage.

There are 6 heading tags. `<h1>`, which is the biggest, `<h2>`, which is the second biggest, etc all the way up to `<h6>` which is really small.

**Here's an example:**

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

So start by adding your very first h1 element to the body tag.

```html
<body>
    <h1>My awesome webpage</h1>
</body>
```

Great! You now have an awesome page title. Let's make it even cooler with a subheading

```html
<body>
    <h1>My awesome webpage</h1>
    <h2>An awesome webpage by me!</h2>
</body>
```

You could use an h2 or an h3 for your subheading, it's really up to you.

Great! You can test out your new code by opening up your file (or reloading the page if you already have it open). You now have a super cool webpage with a heading!

But what if you want to add some text that isn't super huge? Well that's what the `<p>` tag is for! The p tag (which is short for paragraph) is a tag that allows you to have normal sized text in your webpages.

Here's an example:

```html
<body>
    <p>
        About me:
        My name is John Doe and I'm a learning to be a super cool html developer!

        I'm a million years old and have 1,000 cats who constantly need to be fed.
    </p>
</body>
```

But you'll notice that where you put a new line in your code, it didn't register in the actual webpage. In html, you need to actually add line breaks into the code if you want a line break on the actual webpage.

You can do this by using the `<br>` tag. The break or br tag is a tag that will insert a line break whereever it's inserted. The br tag has no closing tag (There's no such thing as `</br>` so it's one of the only tags that are fine on their own.)

With our new knolage we can fix the line break problem to get:
```html
<body>
    <p>
        About me:<br>
        My name is John Doe and I'm a learning to be a super cool html developer!<br><br> <!-- Two line breaks (By the way this is a comment and won't be read by the computer) -->

        I'm a million years old and have 1,000 cats who constantly need to be fed.
    </p>
</body>
```

Sweet. Your code is now line breakified!

But what if you want to style your text and make it real *fancy*? Well, there's tags for *italics* and **bold** as well as ~~strikethrough~~ and <u>underline</u>.

Here they are:
- `<em>` - <em>Italics</em>
- `<b>` or `<strong>` - <b>Bold</b>
- `<s>` - <s>strikethrough</s>
- `<u>` - <u>Underline</u>

And now you know some basic tags! Try and make an all about me page or anything else you want with these skills.