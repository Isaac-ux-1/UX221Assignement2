=== Serious Slider ===
Contributors: Cryout Creations
Donate link: https://www.cryoutcreations.eu/donate/
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl.html
Tags: slider, slideshow, image slider, responsive slider, wordpress slider
Text Domain: cryout-serious-slider
Requires at least: 4.5
Requires PHP: 5.6
Tested up to: 6.6
Stable tag: 1.2.7

Serious Slider is a free highly efficient SEO friendly fully translatable accessibility ready image slider for WordPress. Seriously!

== Description ==

= Overview =

Serious Slider is a free highly efficient SEO friendly fully translatable accessibility ready image slider for WordPress. 

Create beautiful, responsive slideshows within seconds.  Use minimum styling and JavaScript with hardware accelerated CSS3 transitions to create a really fluid experience.

> [Live Demo](http://demos.cryoutcreations.eu/wordpress/serious-slider/) | [Documentation](https://www.cryoutcreations.eu/wordpress-tutorials/create-slider-serious-slider-plugin) | [Features](https://www.cryoutcreations.eu/wordpress-plugins/cryout-serious-slider) | [Support](https://www.cryoutcreations.eu/forums/f/wordpress/plugins/serious-slider)

Serious Slider uses the very familiar WordPress dashboard interface for creating slides and sliders so there's absolutely no learning curve. You just select the media image and press "Create Slider". After that it's like adding or editing WordPress posts, using featured images and other meta information like buttons and URLs.

Serious Slider works with all WordPress themes and has been designed to integrate seamlessly with our own [selected themes](https://wordpress.org/themes/author/cryout-creations/ "Cryout Creations Wordpress Themes").

= Main Features =

* **Create unlimited sliders with unlimited slides.** The only limit is your imagination on how to use them.
* **Add titles, texts, buttons and links to each slide.** All slide texts support HTML tags and even other shortcodes.
* **Easy to use media button.** Effortlessly add slideshows in posts, pages or custom post types via the "Add Slider" media button in the WordPress text editor. Then just select your desired image slider from a dropdown list, no need to remember or copy slider IDs
* **Auto-generated Shortcodes and PHP integration.** Use the auto generated shortcode to include slideshows with themes or other plugins. Copy-paste the auto generated PHP code to integrate with custom code.
* **Serious Slider Widget.** Display slideshows in sidebars via the provided Serious Slider widget
* **Use multiple sliders in the same page.**
* **Familiar admin user interface.** Create sliders and slides with the familiarity of managing posts and categories, without having to learn another user interface
* **Lightweight and powerful.** Only minimum JavaScript and CSS3 are being loaded on your site
* **Fast slider creation.** Create awesome, responsive WordPress slideshows in a matter of seconds
* **Browser compatibility.** The image slider looks and behaves great on various devices and browsers
* **7+ Appearance Styles.** Choose from different appearance styles to make the navigation arrows, bullets, buttons and colors match your site.
* **7+ Transition Effects.** Fade, Slide, Overslide, Underslide, Parallax, Horizontal flip and Vertical Flip.
* **5+ Caption Text Animations.** Choose how caption text appears on the slide: Fade, Slide, Blur and Zoom In/Out.
* **Highly customizable.** Customize image sizes, timings, text size and alignment, text shadow, background color and accent color.
* **Individual options for each slider.** All the customization options and set individually for every slider.
* **Translation ready.** Every single line of text in the slider is translatable both in the front-end as well in the back-end. Compatible with multi-language plugins (WPML, qTranslate, PolyLang).
* **SEO friendly.** Built with search engines in mind, the slider uses correct HTML semantics.
* **Accessibility ready.**
* **Once click demo content.** It's that easy, you're one click away from a working image slider to get you started.

= Customization Features =

* Add individual URLs to target specific pages
* Add slide buttons with customizable link, link text and "open in new window" option
* Choose how to make text over images more visible: either add text shadow, multiline text background or full caption background
* Choose from 7 slider styles, 7 transition effects and 5 caption text animations
* Customize your slider's transition duration and delay
* Choose between auto-height and fixed size for your images
* Customize your slider's font size, text alignment, caption size and accent color

= Functionality Features =

* Our image slider uses WordPress core functionality only, providing you with the familiar WordPress interface for creating both slides and slides.
* Easily transfer existing slides from one slider to another
* Schedule slides to automatically become visible at any time in the future.
* Quickly restore deleted slides from the Trash
* Use WordPress' text editor to add HTML content and even shortcodes to your slides
* Bulk edit slides and slides


== Installation ==

= Automatic installation =

1. Navigate to Plugins in your dashboard and click the Add New button.
2. Type in "Cryout Serious Slider" in the search box on the right and press Enter, then click the Install button next to the plugin title.
3. After installation Activate the plugin, look for Serious Slider in the dashboard menu to set up a slider.

= Manual installation =

1. Upload `cryout-serious-slider` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Navigate to Serious Slider in the dashboard menu to set up a slider.

= Creating the first slider =

* Create a sample slider using the plugin's demo content functionality, or
* Follow our [slider set-up tutorial](https://www.cryoutcreations.eu/wordpress-tutorials/create-slider-serious-slider-plugin)


== Screenshots ==

1. Serious Slider default (Light) style
2. Serious Slider Dark style with caption text background
3. Serious Slider Caption Left style 
4. Dashboard - create new slider 
5. Dashboard - manage slides overview
6. Dashboard - slider integration


== Changelog ==

= 1.2.7 =
*Release date - 2024.11.16*

* Fixed insufficient sanitization on shortcode parameters to address an XSS vulnerability that could be exploited by a malicious user with at least contributor level access - reported by Bob from WPScan
* Confirmed compatibility with PHP 8.3

= 1.2.6 =
*Release date - 2024.10.24*

* Fixed over-sanitization of 'base font size' value filtering out float numeric values
* Fixed PHP 8.3 deprecation warnings: 'creation of dynamic property' and 'using ${var} in strings, use {$var} instead'
* Tested with WordPress 6.6

= 1.2.5 =
*Release date - 2024.06.09*

* Added sanitization and additional existent content check to address CSRF vulnerability in sample slider generation - reported by [Steven Julian to patchstack.com](https://patchstack.com/database/vulnerability/cryout-serious-slider/wordpress-serious-slider-plugin-1-2-4-cross-site-request-forgery-csrf-vulnerability)
* Strengthened sanitization to address CSRF vulnerability in slider option fields - also reported by Steven Julian to patchstack.com
* Added extra format check for malformed numbers in shortcode attributes
* Incresed the number of supported caption buttons to 4
* Fixed deprecation warning about jQuery.fn.bind()
* Confirmed compatibility with PHP 8.2

= 1.2.4 =
*Release date - 2022.12.09*

* Fixed slide meta options not getting saved or updated with WordPress 6+

= 1.2.3 =
*Release date - 2022.01.02*

* Added configurable slider shadow effect
* Improved usability of the "Add new slider" functionality
* Fixed incorrect RTL behaviour of next/previous slider buttons
* Fixed notice displayed on frontent when running on PHP 8.0+

= 1.2.2 =
*Release date - 2021.04.28*

* Fixed jQuery.mobile enqueued with the wrong URL since 1.2.1 on older WordPress releases
* Fixed some deprecation notices about jQuery.fn.bind() with WordPress 5.7

= 1.2.1 =
*Release date - 2021.03.06*

* Updated bundled jQuery-Mobile to 1.5-rc for WordPress 5.6+ without jQuery-Migrate and fixed JavaScript errors
* Fixed panels overlapping on smaller screens on the edit slider screen
* Fixed 'forced' size mode responsiveness to remove unwanted gap under the slider

= 1.2.0 =
*Release date - 2020.06.03*

* Added the third 'forced' images size mode for sliders
* Added forced support for Polylang multilingual plugin
* Added privacy policy info
* Updated plugin dashboard menu icon
* Fixed 'cryout_serious_slider_buttoncount' filter
* Fixed 'Deprecated: media_buttons_context' notice

= 1.1.1 =
* Added option to disable slider transitions autoplay
* Added option to hide slider captions
* Changed slider caption title from using h3 to div tag
* Fixed 'hidden' option not working to navigation indicators
* Fixed navigation indicators misalligned on IE 11 with some styles
* Fixed caption going too wide on 'Caption Left' style with large captions
* Fixed typo in no sliders hint
* Fixed create_function() deprecation usage notifications in widgets.php with PHP 7.2+
* Fixed slider image responsiveness position on RTL

= 1.1.0 =
* Improved slider responsiveness under 640px and 480px breakpoints
* Improved new slider interface in 'Manage Sliders' screen
* Added 'random' sort option in slider options
* Fixed larger images overflowing slider container when using the 'Adapt to images' mode
* Fixed styling overlaps from themes on the dark, tall and caption- styles
* Fixed background color text style option no longer applying since 1.0.4

= 1.0.5 =
* Small styling fix to remove an erroneous bottom margin
* Cleaned up some leftover dev code

= 1.0.4 =
* Added responsiveness option to choose between the new responsiveness mode and the pre-1.0 behaviour
* Fixed slider multi-swipe issue on mobile devices
* Restored paragraph support in slider captions (and added the necessary styling)
* Added info message when slider button is used with Text editor
* Minified custom styling added to the footer
* Slightly improved accessibility

= 1.0.3 =
* Fixed slider indicators being left aligned in Webkit browsers
* Tweaked and re-checked all slider styles

= 1.0.2 =
* Fixed shortcode attributes filter in wrong location and not working
* Fixed slider missing indicators when 'cryout theme' style is used
* Fixed slider description field being visible when HTML descriptions are enabled
* Improved 'manage slider' section appearance and responsiveness

= 1.0.1 =
* Fixed notice of undefined function call in shortcodes.php
* Updated info on plugin about page

= 1.0.0 =
* Added 4 new design styles (Square, Tall, Caption Left & Caption Bottom)
* Totally revamped design of existing styles (Light, Dark, Bootstrap & Cryout)
* Added slider buttons with up to 2 buttons per slide (with customizable label and link); removed in-caption links styling
* Added caption alignment and caption max-width options
* Added caption text styling option
* Added accent color option
* Added caption animation option with 4 effects
* Added quick image management (add/change/remove) in the slides list section
* Added 'orderby', 'hidecaption', 'hidetitle' slider shortcode parameters
* Updated caption markup for compatibility with our Kahuna and Anima themes built-in styling
* Several minor tweaks:
   - link to slides management in the slider section, added 'Insert Slider' button next to 'Insert Media';
   - moved toolbar button to secondary TinyMCE Editor row;
   - updated plugin info and links;
   - new banner and icon images;
   - added missing 'no sliders' message;

= 0.6.5 =
* Added 'shortcode' column in sliders list
* Fixed animation hiccup on some versions of Safari
* Fixed slider bullets alignment
* Fixed unclosed label in widget HTML markup
* Changed class initialization hook to 'setup_theme'

= 0.6.4 =
* Added check to hide caption titles and text when they are not defined
* Fixed widget slider no longer displaying slider output buffering shortcode in 0.6.1
* Improved styling to remove prev/next buttons border on some themes

= 0.6.3 =
* Fixed leftover debug output in 0.6.2

= 0.6.2 =
* Fixed slides links always opening in a new window

= 0.6.1 =
* Fixed extraneous slide/term fields being visible after double quick edit
* Fixed version information not updated in about page
* Fixed slide image not vertically center-aligned when image is narrower than screen
* Improved slider captions responsiveness
* Fixed slider being displayed at top of content due to improper outputting (also separated inline script and moved to footer enqueue)
* Removed some log messages that would appear in the browser's console
* Fixed overslide, underslide and parallax transitions functionality on 3D-enabled browsers

= 0.6 =
* Enabled quick-edit functionality on the sliders
* Fixed slider query overlapping WordPress query in specific usage scenarios (thanks to webdragon)
* Limited dashboard resource loading only to plugin's sections
* Fixed multiple instances of the same slider missing styling after moving inline styling to footer in 0.5.1
* Added extra taxonomy hook for support in Cryout themes
* Fixed animation glitch on Fluida theme

= 0.5.1 =
* Moved inline styling to footer
* Fixed responsive styling issue on about page
* Added widget HTML wrapper for better compatibility with themes
* Added get_sliders_list() function for custom theme integration
* Improved 'No slides' message to link to slider management / sample slider loader.
* Corrected slider selection label in slider metabox
* Corrected insert slider window to display 'no slider available' message when there are no sliders
* Fixed missing closing bracked in template code example
* Fixed slider image tag to only be outputted when an image was defined
* Improved contrained slider layout
* Fixed missing insert slider icon in TinyMCE editor

= 0.5 =
* Initial release.
