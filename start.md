## Getting Started
### What is HTML?

HTML or Hyper Text Markup Language is a markup language (go figure) which allows you to create webpages.

To begin, create a folder on your computer for your "website". You can call this whatever you want. Now inside this folder make a new file called "index.html".

This will be the homepage of your website.

Now, paste the following into your file.
```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>title</title>
</head>
<body>

</body>
</html>
```

This is called the HTML shell. The html shell is some code that should be in every webpage to make it work. Let's break this down.

Everything you see \<thatlookslikethis\> is what's called a **tag**. A tag is basically how you tell the computer where something starts and ends. 

Most tags will have a different closing tag that tells the computer where it ends. For a paragraph you might see `<p>` for where it starts and `</p>` where it ends.

The first tag you see is a little different. It says `<!DOCTYPE html>`. This basically just tells the computer that it's a html file (again, go figure). Next up we have the `<html>` tag. Anything inside of this tag (in between the `<html>` and `</html>`) is part of your webpage's code.

Next up is `<head>`. The head tag contains stuff like metadata and things like css and scripts. It's a set of rules and stuff for your computer to follow before and as it loads the page.

Inside of the head tag we have the `<title>` tag. This is pretty self explanatory. This tag tells the browser what the title of your webpage is. This is the text that shows up in your browser's tab. You don't need to worry about the `<meta charset="UTF-8">` thing for the most part.

There's more stuff you can add to the head tag, for example a website icon, but you'll mostly use these when you're more experienced.

Lastly and most importantly, the body tag. This is the tag that contains all the code that will appear on your webpage. This is where you'll put any text, images, etc.

Right now if you open up your index.html file with your web browser, you won't see anything. We'll get into adding some stuff in the [next lesson](basictags.html).
