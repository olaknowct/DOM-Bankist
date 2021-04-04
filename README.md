# DOM-Bankist

Link: https://olaknowct.github.io/DOM-Bankist/index.html

## Description

- DOM-Bankist is a static banking website.

## About

- The Project is used for educational purposes only, its part of the lesson i took from Jonas Course.
- As part of my learnings and would benefit me, I've decided to document and deploy it. 
- I've listed down here **(See features section)** all the PSEUDO Code, SUMMARY or Feautures from this Project
- Uses Vanila Javascript to implement interactive and modern design
- Advance DOM and Events

#### Features, PSEUDO, Summary And Learnings

	- Keyboard Events
		○ Esc (for modal)
		○ Right and left arrow keyboard (for slider)
	- Getting Cordinates
		○ getBoundingClientRect
			§ Use to get the coordinates of an element specified
		○ scrollIntoView
			§ Navigation into specified coordinates via scrolling
				□ Behaviour can be set to smooth
			§ An old way is computing its coordiates via objects of getBoundingClientRect Method
	- Event Delegation
		○ To maximize code performance and efficient way of attaching  an event listener that has the same function
		○ Useful compare to foreach
			§ Foreach method might affect the performance especially if you a multiple elements that has the same function
			§ Attach an events listener to its parent element and use bubbling event propagation instead of attaching to each element
	- Nav Links
		○ Uses event Delegation
		○ ScrollintoView
	- Tabbed
		○ Uses an event delegation
		○ Logic 
			§ Initial Remove all active state
			§ Set the specified dataset as active
			
	- Mouseover and mouseout
		○ Use to set the active color when hover to navigation link to make
		○ Uses bind to own a THIS property
			§ Regular function set THIS as undefined
		○ Hover 
			§ Enter : set css using classlist
			§ Leave : unset and revert to normal state
			
	- IntersectionObserver API
		○ Sticky navigation executed as soon as it hits the element observe 
		○ Update/Add CSS of sticky navigation once reached a certain threshold defined from the option parameter
		○ Use to 
		○ Unobserve
			§ Useful if you want to define number of intersectionoberserver execution
		○ Lazy Loading Image
			§ Images can decrease website performance using I.O API we can set initially the image with low res and dynamically change to higher resolution only if a certain view port reaches. 
	- SLIDER / CAROUSEL
		○ Right/Left arrow button event listener
			§ Uses dataset attribute to relay on the next flow
		○ Right/Left Arrow keyboard event listener
			§ Uses dataset attribute to relay on the next flow
		○ Manipulate style attribute based from event listener trigger
			§ TransformX
	 

