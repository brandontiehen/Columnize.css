
# "Columnize.css" - Version 2.0 or 1.0
# By Brandon Tiehen
# Copyright 2024 (c) All Rights Reserved.

# - Based on a flex-grid system utilizing 10-column layout., 12 for Version 1
# - Responsive for all device/screen sizes and orientations
# - Mobile-First design

# * https://github.com/brandontiehen/
# * LICENSE INFO: General Use - See more online
# * INSTRUCTIONS: Use col-[size]-[columns] to denote classes. Example: col-md-5 for version 2 or col-md-6 for version 1 will display a half-width column. Clearfix resets the float functions.

# Using the Layout:
# Columnize.css (version 1) uses in a 12-column grid layout system.  Here's a tutorial., Version 2 is a 10-column system.
# Nest a .col- classified div/container into a .row div/container. For example:
	<div class="row">
		<div class="col-md-12"><!--12 only applies to version 1. Version 2 maxes out at col-[size]-10.-->
			<p>This will display cat full-page width. 12, 11, 10, 9, 8, etc. are abbreviations for 100, 90, 80, etc. percents.  On phones, this will mostly display in one or two columns based on the sizing preferences and screens. See more in the @media queries in the CSS file.</p>
		</div>
	</div>
	
# Thanks for using Columnize-v2.css! Please enjoy and hopefully a V2 will be out soon.
