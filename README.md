## Show Whitespace Characters
Like anything done arbitrarily or without thinking about it, trailing whitespace on lines is bad. Turn on your editor's draw whitespace setting so that you can catch those questionable characters trailing in after the other characters in the line have done all of the work.

This is also a good way to make sure indentation is done right, because it will be right in your face *all of the time* if it isn't.

## Distinguish Javascript Selectors From The Style System
Orthogonality. Single responsibility Principle. Not spaghetti code. Dissimilar to flying a helicopter. These are some of the things you can consider as synonymous with creating and using Javascript specific classes.

Using a common prefix is the best way to delineate these as JS hooks. For example: `.js-load-more`, `.js-remove-condiment` and `.js-elect-premier`. Each of these class names also sound like an action, maybe you should do that, too.

*If* it must be explained why this is a good idea, just spend some time thinking about the idea that your style system and your Javascript system are two separate systems. Think for yourself.
