RATIONALE
-------------------------------------------------

Reflection:
	This project reminded me that it is cruicial when programing to begin with a clear head and a
	huge block of time reserved to code. Time flew by even when just developing the basic structure
	of each page. For example setting correct margins and coming up with appropriate CSS class names.
	I noticed that along with time management, pre-program planning is a must. When the nav page
 	(not the nav bar) was being built, for some reason the center wasslightly off-center which would annoy 
	anyone on the page. It turned out to be a very small margin on the left of a page made early in the code. 
	This is where a more thought out stratedgy would have saved time.

	The website began with the index, where a scaffold was created that every page used. This contained
	the nav bar and title. It also gave the correct classes to the elements that require them to make
	the background styled how it should be. One CSS file was used with the normalize styles first and
	then the CSS for the website after. This was done because CSS takes the very last code to implement.
	Meaning that any code written after will simply overwrite the normalize stylesheet. 

	One of the hardest elements was creating somewhat of a responisve website with no JavaScript,
	jQuery or any other language of its kind. What can be done with a line or two of script takes a
	lot more code, trial and error and persistence to create. For example I was unable to make the
	slideshow on the main page scroll automatically (i'm sure it can be done somehow). This also brought
	to realisation that knowing what code is and does is not enough. To be able to use HTML and CSS
	in a workplace, one must understand how a line of code actually works and how it can be used in
	conjunction with others to build a more efficient and effective website.

Comparison:
	The website was developing and changing over time. One of the main issues face was that a slideable
	menu was going to be use. This was a menu where at full screen the user could choose to hide the menu 
	tabs whenever they pleased. It was soon realised that another language would have to be use in order
	to do that. Instead a media query was used to detect if the pages size was under the value of 1024px.
	This number was used as 1024 is divisable by 2, 3, 4, 5, 6, 8, 10, 12 and 15. This accomodates best for
 	most widescreens with a 16:9 aspect ratio. When the screen size was under that value, the menu tabs
	dissapear and a burger menu appears inplace of it. The burger is a link to a html page with just the
	menu options. These options are allways center of page and work well with any small mobile screen.

	A changed made in the developmental process was having the nav bar set to an absolute position which
	prevented any overlap when scrolling. The plan shows a title and nav that always stays in the same 
	fixed position however the grid would have to be completely changed in order to do that. Instead it
	was voted by a group of 1 person to just have it all at the top of the page.