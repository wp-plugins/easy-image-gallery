=== Easy Image Gallery ===
Contributors: sumobi
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=EFUPMPEZPGW7L
Tags: image gallery, image, galleries, simple, easy, sumobi
Requires at least: 3.5
Tested up to: 3.6
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Easily create an image gallery on your posts, pages or any custom post type

== Description ==

This plugin allows you to easily create an image gallery on any post, page or custom post type. Images are can be added and previewed from the metabox. Images can be re-ordered by drag and drop.

Features:

1. Drag and drop re-ordering
1. Add gallery to any post, page or custom post type
1. If more than one image is added to the gallery, the images become grouped in the lightbox so you can easily view the next one
1. CSS and JS are only loaded on pages where needed
1. Images link to larger versions (can be turned off)
1. Fully Localized (translation ready) with .mo and .po files
1. Add multiple images to the gallery at once
1. Uses the thumbnail size specified in Settings -> Media
1. Custom webfont icon for hover effect
1. Support for fancyBox and prettyPhoto (developers can easily add their preferred lightbox via hooks and filters)
1. Uses the new WP 3.5+ media manager for a familiar and intuitive way to add your images
1. WordPress 3.6 Ready

= Usage = 

Galleries are automatically appended to the bottom of your post/page unless you use the shortcode below. Using the shortcode will give you finer control over placement within the content area.

= Note =

fancyBox requires a [license for commercial use](http://fancyapps.com/fancybox/#license "fancyBox"). It's free to use for personal websites however.

= Shortcode Usage =

Use the following shortcode anywhere in the content area to display the gallery

    [easy_image_gallery]

= Template Tag Usage =

The following template tag is available to display the gallery
    
    if( function_exists( 'easy_image_gallery' ) ) {
	    echo easy_image_gallery();
    }

If you use the template tag above, you will need remove the default content filter:

    remove_filter( 'the_content', 'easy_image_gallery_append_to_content' );    

= Developer Friendly =

1. Modify the gallery HTML using filters
1. Developed with WP Coding Standards
1. Easily add your preferred lightbox script via hooks and filters
1. Easily unhook CSS and add your own styling
1. Pass in a different image size for the thumbnails via filter
1. Minimalistic markup and styling

**Stay up to date**

*Become a fan on Facebook* 
[http://www.facebook.com/sumobicom](http://www.facebook.com/sumobicom "Facebook")

*Follow me on Twitter* 
[http://twitter.com/sumobi_](http://twitter.com/sumobi_ "Twitter")

== Installation ==

1. Upload the entire `easy-image-gallery` folder to the `/wp-content/plugins/` directory, or just upload the ZIP package via 'Plugins > Add New > Upload' in your WP Admin
1. Activate Easy Image Gallery from the 'Plugins' page in WordPress
1. Configure the plugin's settings from plugins > Easy Image Gallery
1. Create a gallery on any post or page from the added 'Image Gallery' metabox.

== Screenshots ==

1. The plugin's simple configuration screen. Any existing custom post types will appear here
1. The plugin's simple metabox that is added to the publish/edit screens
1. WordPress 3.5's new media manager is launched when you click "Add gallery images". You can select multiple images to insert into the gallery
1. The plugin's Image Gallery metabox after images have been inserted and the post has been saved
1. The front-end of the website showing the gallery which has been automatically appended to the content
1. Clicking on an image launches the lightbox. Here it's shown with prettyPhoto

== Changelog ==

= 1.0 =
* Initial release