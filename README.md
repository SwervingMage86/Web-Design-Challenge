#Web-Design-Challenge

## Exploring the Weather

The purpose of this project was to create a website based on data that was collected in graphed in an earlier project.
This previous project involved collecting weather data from OpenWeather, analyzing it, and creating plots.
This website now allows the user to explore that data and analysis with an interface that is easy to use anywhere from large desktop screens to small mobile phones.
This website was made possible with the help of Bootstrap, Google Font APIs, and Font Awesome.

### Key Features

One of the biggest goals of this website, other than organizing and displaying weather data, was to design the website in a way that is able to be easily used on different sized screens.
These are the key features that make that possible:

	* Using Bootstrap's container capabilities, key elements such as text boxes and images collapse and stack on each other as screen size changes.
	* Using Bootstrap's navbar that is consistent on every page, links to different pages are organized in a way that makes it easy for the user to navigate throughout the website.
		* This navbar features active links that stay highlighted to remind the user which page they are on, as well as a dropdown menu to find specific pages, that are as well highlighted when active.
	* Using Font Awesome's icons, glyphs are included with the navigation tabs to help the user visualize what each tab links to.  When screen size collapases, instead of the tabs stacking on top of each other, the words on the links collapse leaving only the glyphs to make the website easier on the eyes in smaller views.

### Bugs

While the website interface works well and compliments multiple size screens, there are a few bugs that haven't been worked out.
I would like to list them here so that you are aware:

	* As the screen size collapses to under 500 pixels, the glyphs begin stacking, while this is fine on most screens when opened on mobile phones in verticle view, all icons are vertically stacked making the navbar uneasy to look at.
	* While not already on a "Plot" page, when selecting the "Plot" dropdown menu, the background stays blue instead of a dark green which matches the theme much better.
	* When on the "Data" page, the table does not collapse with screen size, leaving the user to have to scroll across the screen to view the entire width of the table, this also makes the header look poor.
