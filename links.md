# Links

A quick lesson on html [links](https://www.youtube.com/watch?v=6n3pFFPSlW4).

Links are a way to transport users around your website and the web in general. I'm sure you know what a link is.

Links are created using the `a` element with the `href` attribute. Here's an example:

```html
<p>This is a <a href="https://example.com">link!</a></p>
```

<p>This is a <a href="https://example.com">link!</a></p>

Make sure that when you're setting the href attribute, you'll using a **full url** that **includes https:// or http://**. `https://example.com` will work, but `example.com` will not.

To make your links open in a new tab by default, simply set the `target` attribute to `"_blank"`.

```html
<p>This is a <a href="https://example.com" target="_blank">link!</a></p>
```

Because you created your html file inside of a folder, you can actually link other html files inside of the say directory. To test this, create another file in the same folder as your `index.html` file and call it whatever you want, just making sure that it ends in .html. Now put whatever code you want in there and create a link to it in your index.html file. Because it's another file in the folder, similarly to images you don't have to put the full url, just the exact name of the file.

```html
<p>This is a <a href="newfile.html">link to another html file</a></p>
```