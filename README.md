# SASS Flexbox mixins

This is a set of mixins for those who want to mess
around with flexbox using the native support of current
browsers. See [caniuse.com](http://caniuse.com/flexbox) for complete support documentation.

Basically this will use:

- Fallback, old syntax (IE10, Safari, mobile webkit browsers)
- Prefixed standard syntax (Chrome)
- Final standards syntax (FF, IE11, Opera 12.1)

------------------------
This was inspired by:

- http://dev.opera.com/articles/view/advanced-cross-browser-flexbox/
	
With help from:

- http://www.w3.org/TR/css3-flexbox/
- http://the-echoplex.net/flexyboxes/
- http://msdn.microsoft.com/en-us/library/ie/hh772069%28v=vs.85%29.aspx

A version compatible with Compass is provided by @trinonsense, on the compass branch.

---
### TODO:
- create bower component
- re-document (YARD syntax)
- update tests