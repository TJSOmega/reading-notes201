	1. 3 Different types of lists in HTML: (Taken from Book)
	
		a. Ordered lists are lists where each item in the list is numbered. For example, the list might be a set of steps for a recipe that must be performed in order, or a legal contract where each point needs to be identified by a section number.
		
		b. Unordered lists are lists that begin with a bullet point (rather than characters that indicate order).
		
		c. Definition lists are made up of a set of terms along with the definitions for each of those terms.
	
	- Each time an item is entered into a list it is given an li element.
	- When using a definition list items use the <d> tag and the <dd> tag.
	
		○ <dt>  This is used to contain the term being defined (the definition term).
		○ <dd>  This is used to contain the definition.
	
	- There are also things such as nestled lists. Which is when you put a second list inside of an li element in order to create a sub list. Using <ul> and then <li>.


	
	Summary from Book:
	
	X There are three types of HTML lists: ordered, unordered, and  definition
	
	X Ordered lists use numbers. 
	
	X Unordered lists use bullets. 
	
	X Definition lists are used to define terminology.
	
	 X Lists can be nested inside one another.
	
	
	
	2. Boxes:
	
	
	- By default in CSS a box is sized just big enough to hold its content.
		○ This can be changed using width and height
		
	- The most popular terms to change a boxes size are percentage, pixels, and ems(?) . Primarily though pixels is used.
		○ Percentage does however match the box to the size of the browser.
		○ Ems sets the box size relative to the text within it.
		
	-  min-width and min-height determines the lowest possible width and height content is allowed to shrink to.
	
	- Overflow content tells the browser what to do if the content contained is bigger than the box it is held in and creates a scrollable content box or hides the extra text.
	
	- Every box has 3 available properties to control how it appears on the page.
		○ Border: Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another
		○ Margin: Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.
		○ Padding: Padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents.
