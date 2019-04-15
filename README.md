# Project 0

Web Programming with Python and JavaScript

a short writeup describing your project:

	homer simpson's family website
	consisting of 4 HTML pages, a couple of embedded images, and a styles.css and styles.scss
	Bootstrap is employed for page layout of each HTML page based on the bootstrap grid model. 

what’s contained in each file
	
	index.html:
		This is a welcoming page. It is directing to page1.html. It contains a list.
		
	page1.html:
		This page offers an overview of the simpson family in the shape of a table.
		The user can get more detailed information for select family members (Abbie and Bart). 
		The page allows returning to index.html, but it is most importantly directing to page2 (Abbie) and page3 (Bart).
		
		The table contains 2 rows with invisible entries. Obviously, Homer, the creator of the
		files wasn't sure about the exact number of his family numbers and implemented some "placeholders".
		
	page2.html:
		This page is providing us information about Abbie.
		We are using @media query to achieve a degree of mobile responsiveness (by controlling the image size depending on window size).
		The user may return to the family overview table HTML page.
		
	page3.html:
		This page is providing us information about little Bart.
		The "card" component of bootstrap (https://getbootstrap.com/docs/4.3/components/card/#using-utilities) help us achieve 
		a fancy layout.
		The user may return to the family overview table HTML page.
		
	styles.css:
		Our stylesheet uses at least five different CSS properties:
			color
			background-color
			font-size
			font-weight
			text-align
			border-collapse
			border
			visibility: hidden
			content: "⇒"			
			
		and five different types of CSS selectors (https://www.w3schools.com/cssref/css_selectors.asp):
			.class (.whoknows)
			#id	 (#Abbie)
			single element selector (h1)
			multiple element selector (th,td)
			Psuedoclass selector (a::before)

	styles.scss:
		This file relies on two SCSS variables (see code lines 1/2, and 5/6),
		on one case of SCSS nesting (see lines 20, 23 and 28 in particular => this relates to the hyperlinks within the table on page1.html),
		and one case of SCSS inheritance (see lines 4 and 15).
		Compiling it produces styles.css.
	
	abbie.png, bart.jpg, Homer_Simpson_2006.png:
		the embedded images