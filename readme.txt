=== PrePublish Checks by Kgaurav ===
Tags: prepublish checks,prepublish posts,checks before publishing,prepublish checklist,checks before posting
Donate link: https://paypal.me/kgaurav6791?country.x=IN&locale.x=en_GB
Requires at least: 4.1
Tested up to: 6.1.1
Requires PHP: 5.6
Stable tag: 1.0.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A plugin that checks to ensure variety of conditions are being met before any new post can be published.Eg-Minimum Title length,Featured Image,etc.

== Description ==
A simple plugin to enforce variety of checks before publishing any new post.Define minimum and maximum title length.
Make presence of a featured image compulsory.
Specify the minimum/maximum height and width for your featured images.
Bonus feature check for post slug to be in english.

Do you own a multi-author website,who keeps publishing posts with too small or too big title?
Or do you yourself keep forgetting to add featured image before clicking on that "publish" button?
Maybe people keep making posts on your website with featured images of such small  resolution that they start looking blurry on your landing page?

This plugin will ensure that you can set custom conditions that need to be met before someone could publish a post.
If anyone clicks on the 'publish' button and one of the conditions are not met(For eg-if publish button is clicked without adding a featured image.) then the publish event will be intercepted,post will be saved as a draft instead and user will get an appropriate error showing what they did wrong and how they can correct their mistake before publishing.
   

== Installation ==
= Automatic installation =

Automatic installation is the easiest option as WordPress handles the file transfers itself and you don't need to leave your web browser. To do an automatic install of PrePublish Checks by Kgaurav, log in to your WordPress dashboard, navigate to the Plugins menu and click Add New.

In the search field type "PrePublish Checks by Kgaurav" and click Search Plugins. Once you've found the plugin you can view details about it such as the point release, rating and description. Most importantly, of course, you can install it by simply clicking "Install Now".

= Manual installation =

The manual installation method involves downloading the plugin and uploading it to your web server via your favourite FTP application. The WordPress codex contains [instructions on how to do this here](https://codex.wordpress.org/Managing_Plugins#Manual_Plugin_Installation).

1. Download "PrePublish Checks by Kgaurav"
2. Upload the "PrePublish Checks by Kgaurav" folder to the '/wp-content/plugins' directory of your WordPress installation
3. Activate "PrePublish Checks by Kgaurav" from your Plugins page


== Frequently Asked Questions ==
= What checks and limits can be set on new posts using this plugin?=

You could check for these conditions(If any of these conditions are not met,Post will not be published) -
-Title Minimum Length(default 10 characters).
-Title Max Length(default 280 characters).
-Check to see if slug is in English(default yes).
-Make Featured Image Compulsory(default yes).
-Minimum Featured Image Width(default 500px).
(only works if 'Make Featured Image Compulsory option' above is selected).	
-Minimum Featured Image Height(default 400px).
(only works if 'Make Featured Image Compulsory option' above is selected).	
-Maximum Featured Image Width(default 4000px).
(only works if 'Make Featured Image Compulsory option' above is selected).	
-Maximum Featured Image Height(default 4000px).
(only works if 'Make Featured Image Compulsory option' above is selected).

= How does it work technically? =

This plugin is triggered on "transition_post_status" hook.
Everytime a post status is changed the plugin checks for all of the set conditions to be true and if any of the set conditions are not met,
then post status is changed to draft instead of publish.
Also user is shown an error with which conditions they didn't meet.

= Is PrePublish Checks by Kgaurav free? =

Yes! PrePublish Checks by Kgaurav's core features are and always will be free.

= Where can I find the settings for this plugin? =

Go to **Settings -> Prepublish Checks**. There you will find the options to change all the settings for this plugin.

= Where could I ask for new features, suggest new changes,report bugs etc for this plugin? =

Right Here.Feel free to suggest any new changes or report bugs I will look into it whenever I am free.Please rate and share if you like this plugin. :-)


== Screenshots ==
1. Prepublish Checks Settings Page
2. Prepublish Checks failed on publishing - 1
3. Prepublish Checks failed on publishing - 2