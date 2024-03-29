README.TXT // Black Hole theme for Drupal 7.

Thank you for downloading this theme!


ABOUT THE BLACK HOLE THEME:
-------------------------------------------------------------------------+
Black Hole is an advanced theme, with layout and style configuration options built 
in that you can control through Drupal's UI, to be ideal for a wide range of sites. 
It contains the same kinds of features as Zero Point theme in a dark look.

The theme validates XHTML Strict, CSS 2/CSS 3, and it is cross-browser compatible.

Layout features
===============
- 1, 2, or 3 column layout with adaptive width (min. 1040px max.1200px at 1440px 
	disply width) based on "The Jello Mold Piefecta Layout" 
	(http://www.positioniseverything.net/articles/jello.html); 
- 17+1 collapsible block regions; 
- 10 colour styles; 
- Advanced SEO optimization; 
- built-in IE transparent PNG fix; 
- jQuery CSS image preload (optional) 
	(http://www.filamentgroup.com/lab/update_automatically_preload_images_from_css_with_jquery/); 
- Fixed / Variable width sidebars (optional); 
- Round corners for page elements and primary menu (optional); 
- Block icons (optional); 
- Page icons (optional); 
- Drop-down primary links menu (optional); 
- Primary links menu position (center, left, right); 
- Helpful body classes (unique classes for each page, term, website section, 
	browser, etc.). Everything can be controlled via CSS, including each menu
	item (for static menu), how colours and other items will be displayed in
	different browsers, or by terms, sections, etc.; 
- Full breadcrumb; 
- Bi-directional right to left (RTL) theming; 
- Works perfect in Multilanguage installations. 

Advanced theme settings features
===============================
Layout settings
- Style - Choose a colour palette from 10 options: Nebula, Protostar, Star, Planet, Red Giant, 
  Planetary Nebula, Darf, Supernova, Black Hole and Themer. More colour options to come.
- Layout width - adaptive, fluid and fixed width;
- Sidebars layout - Fixed width sidebars or variable width sidebars;
- Themed blocks;
- Block icons - Choose between none, 32x32 pixel and 48x48 pixels icons, positive or negative icons;
- Page icons - Choose a layout with or without page icons;
- Menu type - Two-level Static or SuckerFish drop-down menu;
- Menu position - Left, center or right;
- Rounded corners - Option to have rounded corners in all browsers but IE;
- Header image rotator;
- jQuery CSS image preload;
- No-followed login/register links.

Breadcrumb 
- Display Breadcrumb.

Search results
- Customize what should be displayed on the search results page. 

Theme development settings
- Site ID bodyclass.

To know more, read Black Hole handbook (http://drupal.org/node/507792).



MODULE SUPPORT
-------------------------------------------------------------------------+
This theme can support virtualy any module.


  
THEME MODIFICATION
-------------------------------------------------------------------------+
If you feel like giving the theme a look of your own, I recommend to play
with /_custom/custom-style.css; please read the comments in this file.



SIDEBARS DIMMENSIONS
-------------------------------------------------------------------------+
The maximum with available for sidebars is as follow:

                                         | left | right | both
-----------------------------------------------------------------
Variable asyimmetrical sidebars (wide)   | 250  |  300  | 160-234
-----------------------------------------------------------------
Fixed asyimmetrical sidebars (wide)      | 160  |  234  | 160-234
-----------------------------------------------------------------
Variable asyimmetrical sidebars (narrow) | 230  |  280  | 140-214
-----------------------------------------------------------------
Fixed asyimmetrical sidebars (narrow)    | 140  |  214  | 140-214
-----------------------------------------------------------------
Equal width sidebars (narrow)            | 155  |  155  | 155-155
-----------------------------------------------------------------

NOTE: Do not exceed the available width (especially with images) or IE6 will 
not behave so the sidebars may drop. 



USING THE SuckerFish DROP-DOWN MENU
-------------------------------------------------------------------------+
The menu can either be a two-level static menu or a suckerfish drop-down menu.

Out of the box the theme will show the primary and secondary menu. If you select 
(/admin/build/menu/settings) the same menu as primary links then secondary 
links will display the appropriate second level of your navigation hierarchy.

To activate the drop-down menu put the Main menu block in the "Drop Down menu" 
region and set the correct levels to "expanded" (the parent item). 
NOTE: Go to /admin/build/menu and expand all parents in your primary menu.



INSTALLATION INSTRUCTIONS
-------------------------------------------------------------------------+

1) Place the black_hole directory into your themes directory (sites/all/themes/black_hole).

2) Enable the Black Hole theme (/admin/appearance).

3) You can configure settings for the Black Hole theme at /admin/appearance/settings/black_hole. 

If you place the theme in a location other than /sites/all/themes/black_hole you should 
modify the path in /black_hole/css/iepngfix.htc and /black_hole/css/ie.6, accordingly.



UPGRADING to a new version of Black Hole
-------------------------------------------------------------------------+

1) If possible, log on as administrator user. 

2) Put the site in "Off-line" mode.

3) Place the black_hole directory into your themes directory (sites/all/themes/black_hole).
   In case you have done customization to Black Hole theme, remember to overwrite theme
   custom-style.css with your custom-style.css file.

4) Clear the Drupal cache option and put the site in "On-line" mode. It is always a good 
   idea to refresh the browser's cache (CTRL+F5).

5) Check the settings for the Black Hole theme at /admin/appearance/settings/black_hole. 

NOTE: In some very rare cases, if after upgrading the theme can not be configured you should 
delete all the black_hole records in the data base.



SITES USING "BLACK HOLE" THEME
-------------------------------------------------------------------------+
Various implementations of Black Hole theme can be found here:
http://www.wac.ro/
http://www.streight.co.uk/
http://www.draculea.net/

Test page: http://d7.sofpedia.ro/

If you look for a white version of "Black Hole", then choose "Zero Point". 
Check the theme's project at http://drupal.org/project/zeropoint.


CONTACT
-------------------------------------------------------------------------+
My drupal nick is florian <http://drupal.org/user/35316> � and I can be reached 
at florian@radut.net (http://www.radut.net).

I can also be contacted for paid customizations of Black Hole theme as well as
Drupal consulting, installation and customizations.
