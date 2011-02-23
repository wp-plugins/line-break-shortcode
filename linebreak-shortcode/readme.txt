Line Break Shortcode plugin. 
Licensed under the freebsd license. 
Be free. BSD free. 

Use this to force line breaks into your posts and pages. It is simple. [br] will add a line break. It won't be filtered out by TinyMCE. 

There are no attributes. Not much else to see here. I couldn't find a plugin that did this anywhere. Thought that was odd. 


Example time!

If your text editor content looks like this:
	Hello this is my 
	[br]
	example!

The HTML will end up:
	<p>Hello this is my</p>
	<p><br /></p>
	<p>example!</p>

Because the default styling of a paragraph tag adds an area of white space below it this may result in more of a break than you wanted. Solution:
	Hello this is my [br] example!

Which results in the following HTML:
	<p>Hello this is my <br /> example!</p>

	
Question/Comments: Please hit up the forum or drop me a line at Reynolds.TimJ+LinebreakPlugin@gmail.com
