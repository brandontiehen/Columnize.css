
# "Columnize.css" - Version 2.0
# By Brandon Tiehen
# Copyright 2024 (c) All Rights Reserved.

# - Based on a flex-grid system utilizing 10-column layout.
# - Responsive for all device/screen sizes and orientations
# - Mobile-First design

# * https://github.com/brandontiehen/
# * LICENSE INFO: General Use - See more online
# * INSTRUCTIONS: Use col-[size]-[columns] to denote classes. Example: col-md-5 will display a half-width column. Clearfix resets the float functions.

# Using the Layout:
# While Columnize.css (version 1) was used in a 12-column grid layout system, I decided to go with a 10-column system for ease of layout and add specific modifier classes.  Here's a tutorial.
# Nest a .col- classified div/container into a .row div/container. For example:
	<div class="row">
		<div class="col-md-10">
			<p>This will display cat full-page width. 10, 9, 8, etc. are abbreviations for 100, 90, 80, etc. percents.  On phones, this will mostly display in one or two columns based on the sizing preferences and screens. See more in the @media queries in the CSS file.</p>
		</div>
	</div>
#To display at 1/2, 1/3, or 1/4 (50%, 33.33333%, or 25%), we can use classes: .col-[size]-half, -third, and -quarter.
	
	
#Clear-Fix & Spacers:
#To reset the page from floats and such, use a .clear- empty div anywhere at the end of said content.
#* .clear-fix resets layout there down to keep progressing as you like with no padding or margins added.
#* .clear-single, .clear-double, and .clear-triple do the same as .clear-fix but with a 1, 2, or 3-percent padding added to the div, creating space between the previous and next sections/elements, vertically.
#
#Thanks for using Columnize-v2.css!  This has been a while since I revamped it, so please enjoy and hopefully a V3 will be out soon.