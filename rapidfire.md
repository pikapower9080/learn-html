# Rapid fire tags

Tags so fast you can't even catch up! (Hopefully that's not the case!)

### audio
A tag that lets you insert a mini audio player provided by your browser into your webpage. 

```html
<audio src="source_direct_link.mp3" controls></audio>
```

<audio src="https://htmlreference.io/assets/Hal.mp3" controls></audio>

*Thanks to [htmlrefrence.io](https://htmlreference.io/) for the sample audio!*

### button

A super simple button useful for running code and submitting forms (a very complicated thing in html that you shouldn't worry about for now)

```html
<button onclick="alert('Hello!') // This is javascript!">Click me!</button>
```
<button onclick="alert('Hello!')">Click me!</button>

### code

A tag that will make text inside of it look different than everything else indicating that it's a command you can run or something.

```html
<p>The HTML <code>body</code> tag is where everything inside of your webpage that is displayed is contained.</p>
```
<p>The HTML <code>body</code> tag is where everything inside of your webpage that is displayed is contained.</p>

### div

Useful for writing CSS which is how you make your webpages look nice. Basically an invisible (not always) box that contains a portion of your website

```html
<h3>This is some heading text</h3>
<div id="articlebody"> <!-- You usually mark div elememnts with an ID (you can do this with any element)-->
<p>This is some body text</p>
</div>
```

<h3>This is some heading text</h3>
<div id="articlebody" style="border-style:solid; border-width: 1px; padding-left: 5px; /* This is some css code ;) */">
<p>This is some body text</p>
(Div elements won't normally have a border, but I used some css magic to make it have one so you could tell the difference)
</div>

### i

Used to make a section of text different from the rest (similar to the span tag which I'll show later). You can apply some custom styles to your i text but by default it will make it *italic*. 

```html
<p>This is some <i>text inside of the i tag</i></p>
```
<p>This is some <i>text inside of the i tag</i></p>

### iframe

Iframe is a little bit complicated but basically it allows you to create a mini preview of another webpage inside of a webpage. It's the way that you can embed youtube videos and stuff like that.

```html
<iframe src="https://example.com" width="100%"></iframe>
```
<iframe src="https://example.com" width="100%"></iframe>

It's pretty much a mini web browser window inside of your web browser!

Here's an example of a youtube video that you can play on this website using the iframe tag. You can generate code for this stuff on the share option of a youtube video  under embed.

<iframe width="560" height="315" src="https://www.youtube.com/embed/j5a0jTc9S10?controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### progress

The progress tag is a tag that allows you to create a progress bar.

```html
<progress value="0.7">Progress</progress>
```
<progress value="0.7">Progress</progress>

This is very similar to the meter tag which just does it with a different style.

```html
<meter value="0.7">Progress</meter>
```

<meter value="0.7">Progress</meter>

### select

The select tag creates a dropdown menu with options. This goes with the option tag which goes inside of a select tag to define one of said options.

```html
<select name="favcolor">
	<option>Red</option>
	<option>Orange</option>
	<option>Yellow</option>
	<option>Green</option>
	<option>Blue</option>
	<option>Indego</option>
	<option>Violet</option>
</select>
```

<select name="favcolor">
<option>Red</option>
<option>Orange</option>
<option>Yellow</option>
<option>Green</option>
<option>Blue</option>
<option>Indego</option>
<option>Violet</option>
</select>

### span

The span tag is kind of like the i tag without the italics part. It's pretty useless without css code, but here's how to use it anyway. This example contains some css code which you shouldn't have to worry about yet.

```html
<head>
	<style>
		.red{
			color: red;
		}
	</style>
</head>
<body>
	<p>This text is <span class="red">red</span>!</p>
</body>
```

<p>This text is <span style="color: red;">red</span>!</p>

### strong

Basically the b element. Makes **bold** text.

```html
<p>Do I really need to make an <strong>example</strong> for this??</p>
```
<p>Do I really need to make an <strong>example</strong> for this??</p>

### textarea

A box of text where the user can type.

```html
<textarea placeholder="Type here"></textarea>
```

<textarea placeholder="Type here"></textarea>

### Video

The video tag allows you to insert a basic video player provided by the browser and not something like youtube or vimeo.

```html
<video src="https://pikapower9080.github.io/assets/downloads/shreksophone_short.mp4" controls></video>
```

<video src="https://pikapower9080.github.io/assets/downloads/shreksophone_short.mp4" controls width="100%"></video>

### And that's it!

There you have it. 11 Rapid fire tags that you know for later! As always, try to come up with something cool using your new tag smarts. See you next time!

Hey I have an idea! Why don't you click on this [link](links.html) to learn about links!