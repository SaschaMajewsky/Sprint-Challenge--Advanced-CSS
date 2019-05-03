Q:
What is the difference between an adaptive website and a fully responsive website?

A:
Adaptive Websites:
-Uses media queries
-Designs are seperated for desktop, tablet, mobile
-Are faster to build up
-The width in the Media Queries is still hard coded
-The server determines over the device what pre-templated page the device will get

Responsive Websites:
-Uses media queries
-Designs are seperated for desktop, tablet, mobile
-Are more difficult to create but reaches more devices well
-Uses media queries und units from the viewport to shrink or grow the webpage accordingly to the device
-Responsive websites provide access to thousands of different shaped devices as the device itself gets detected through media query

Q:
Describe what it means to be mobile first vs desktop first.

A:
It means that you start to draft the layouts for your designs at first for the mobile (shrinked) version.
Then later on when the basic functionalities are well established for your mobile version you expand 
to bigger screen sizes and layout stuff more nicely for this size. So by nature you use min-width media queries.
Mobile resolutions are a big part of the modern web and by not focusing the quality of your layout on these
devices you lose a good chunk of your targetes audience.


Q:
What does font-size: 62.5% in the html tag do for us when using rem units?

A:
It sets the root em (rem) to 10px so we can better calculate from there on with it. Otherwise 1rem would equal 16px.

Q:
How would you describe preprocessing to someone new to CSS?

A:
With preprocessing through LESS, SCSS or SASS you can write code that is way better structured, easier to understand/maintain
and tinier than plain CSS. By doing that you still have access to all CSS functionalities but even more like using variables, 
nesting classes or create your own custom template parametric mixins. Preprocessing is necessary as a developer because it is the only way
to keep your growing CSS codebase structured. Preprocessed code cannot be understand by a browser directly like CSS, so you need to
compile it into complex, sometimes jibberish CSS but you only need to focus on the LESS/SCSS/SASS codebase to read so that isn't a big problem.

Q:
What is your favorite concept in preprocessing? What is the concept that gives you the most trouble?

A:
The most I liked to create my own parametric mixins so that you can access it like a function and create custom CSS elements
with way less codelines used. Also structuring LESS into several files is really good to conquer and divide complexity away.
But it sometimes can also be a struggle for example when working with nested container and having your relevant less code separated
away over several files. Handling this is sometimes not as intuitive as maintaining a tiny CSS codebase is.

