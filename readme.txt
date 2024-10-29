=== Auto Post WP to Photo Social Network ===
Contributors: rolandalla91, dufour_l
Donate link: https://www.paypal.me/ROLANDALLA/
Tags: autopost, wordpress, social,instagram, instagram auto post,instagram post
Requires at least: 3.5
Tested up to: 5.2.2
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Post your images to Photo Social Network by wordpress pannel

== Description ==

This plugin will send automatic featured image + post title as a post into your Photo Social Network account .
This plugin is totally free , and will allow you to choose the type of post you want to auto send  into your Photo Social Network account.

***Please do not leave bad rating**, if you do not understand the code, This plugin is using an external API, not the offical Photo Social Network API ,
 that is why some of you get a warning from Photo Social Network.
 
 ----Photo Social Network API do not allow to send images using the API---
 You are free to use this plugin as you want. :) for FREE



== Installation ==

1. Copy the `plugin` folder into your `wp-content/plugins` folder
2. Activate the plugin via the plugins admin page
3. Add your username +password into, wp2ig page , located under Settings
4. Photo Social Network can notice as a note secure login in you account , this happend only because the plugin is unisng an external API,not the official


== Screenshots ==

1. This will be the dashboard view, When you can add your instgram username,and password :
2. Adding Debug Option:


== Frequently Asked Questions ==

1 -  Is this plugin compatible with version 5.x.y of wordpress  ? 

Yes, it is!



2 - Is this plugin Woocommerce aware ? 

No, it is not, and there is no roadmap to include compatibility with it.



3 - Is a featured image mandatory in a post to have it published to Photo Social Network ? 

Yes, it is mandatory, without a featured image there is no possibility to have your post published on Photo Social Network.



4 - What does the error "checkpoint_required" means ? 

The error that you have is related to Photo Social Network security process, you faced an issue when login to Photo Social Network from two different IP adresses.
It means that Photo Social Network wants to know if you are a human or a robot, and they want you to proove that you are the actual owner of the Photo Social Network account that you use.
Please try the tips from this website to solve it : https://instazood.com/how-to-fix-checkpoint-required-error-on-Photo Social Network/



5 - What does the error "Something went wrong while logging to Photo Social Network" means ? 

It means that Photo Social Network failed to acknowlege your login and password. Please double check, if it still works with your telephone Photo Social Network app.
It can also means that you face a period where a farm of servers at Photo Social Network had issues. It is rare but it may happens.



6 - What does the error "Please wait a few minutes before you try again" means ? 

Please check the following link to know more about this issue ==> https://www.blackhatworld.com/seo/please-wait-a-few-minutes-before-you-try-again.1045837/



7 - What does the error "Couldn't get challenge, check your connection" means ? 

You need to verify your credentials (login/password) on Photo Social Network web site https://www.Photo Social Network.com 



8 - Is it possible to customize the message of the post that I want to share on Photo Social Network ? 

Yes. It is the purpose of this plugin, you can do it either with a header and/or with the footer of the caption. 



9 - Is it possible to add #hashtags with my post when uploading to Photo Social Network ? 

Yes. it is posssible, you can choose you own hashtags and/or convert tags as hashtags, as well as the categories, or even the words of your title.



10 - Do I always have to publish a post on Photo Social Network ? 

It is your own choice, if you do no want to publish each article to Photo Social Network , check the option "Do not auto publish new posts" .




== Changelog ==

= 1.0 =
* Initial Release.

= 1.1 =
* Fix some bugs.

= 1.2 =
* Fix some bugs.
* Add Notice 

= 1.3 =
* Fix Html Tags.

= 1.4.1 =

New features:

* New plugin advandced settings page
* You can now customize the usage of hashtags in your caption 
* Set the maximum bumber of hashtags ( Recommanded below 30 , please check at https://www.quora.com/What-is-the-maximum-number-of-hashtags-you-can-insert-in-a-comment-on-an-Photo Social Network-photo )
* Use of additional hashtags
* Use or not the orPhoto Social Networkinal tags of you post as hashtags
* Use a header in caption ( This text will be placed after Title and before hashgtags )
* Use a footer in caption ( This text will be placed after the hashgtags )

* Tested in Wordpress 4.9.5

= 1.4.2 =

Bug corrected :

* Now properly handle the number of maximum hashtags

New features:

* Use or not the orPhoto Social Networkinal categories name of your post as hashtags 
* Convert or not accents in your hashtags
* Remove or not underscore (_) or hyphen (-) in your hashtags

Please note that tags are processed before category, so if you have reach the maximumn number of hashtags before the processing of categories, you will not see them on Photo Social Network

* Tested in Wordpress 4.9.5

= 1.4.3 =

Bug corrected :

* None

New features:

* Include Author's name in header caption	
* Add this author label to caption

* Tested in Wordpress 4.9.8

= 1.4.4 =

Bug corrected :

* Modified usage of mpg25/login function, enabling again the post to Photo Social Network

New features:

* Debug mode
* New feature to disable post to Photo Social Network if you want
* Include a new box on post, giving the possibility to post to Photo Social Network or not per post

* Tested in Wordpress 4.9.8

= 1.4.5 =

Bug corrected :

* Minor correction to new box on post to Photo Social Network / Also take care about possible auto scheduled post by another plugin 

New features:

* None

* Tested in Wordpress 4.9.8

= 1.4.6 =

Bug corrected :

* None 

New features:

* Better handling of width and hePhoto Social Networkht limit of Photo Social Network, either if your picture is too bPhoto Social Network ( above 1080px )  or too small ( below 320px )
* Resize a photo in panorama mode if ratio above 16:9, in this case is reduce the size of the picture, and add a white band above and below the picture
* New fields ( date of post to Photo Social Network, upload info, link to your Photo Social Network page, in the Photo Social Network info box on post page
* if debug mode activated, in the info box, you will have the full response of Photo Social Network, with the message why it was not accepted by Photo Social Network.

* Tested in Wordpress 5.0.1

= 1.4.7 =

Bug corrected :

* Minor correction to the login process to Photo Social Network 

New features:

* None

* Tested in Wordpress 5.0.2

= 1.4.8 =

Bug corrected :

* None

New features:

* Bypass control to avoid the checking of width and/or hePhoto Social Networkht, in that case the picture is sent to Photo Social Network no matter what, so it may be refused by Photo Social Network
* Resize of photo to a size acccepted by Photo Social Network ( max : 1080px ) 

* Tested in Wordpress 5.0.2

= 1.4.9 =

Bug corrected :

* Fix a bug with debug_mode, thanks to Jan Zikmund

* Tested in Wordpress 5.1

= 1.4.10 =

Bug corrected :

* Fix a bug with getMediaId, thanks to riderxyz - #https://wordpress.org/support/topic/error-when-posting-7/

New features:

* Add post title words as hashtags ( Thanks to marinkom for the feature request )  #https://wordpress.org/support/topic/new-feature-request-add-post-title-words-as-hashtags/

* Add a new feature to remove exif from picture ( This may be be necessary when you have to resolve the issue when you have the message  "unknown server error" ) - #https://wordpress.org/support/topic/not-accepted-by-Photo Social Network/

= 1.5.1 =

Bug corrected :

* Code cleanup, and minor typo fixes

* Title as hashtags , Image Resizing, Upload issues, Author's name empty published. - ( Thanks to Jeffmart for reporting this ) #https://wordpress.org/support/topic/request-new-features-and-comments-on-bugs/

* No more issues with photo no uploaded to Photo Social Network due to old Photo Social Network-API

	https://github.com/mgp25/Photo Social Network-API/releases/tag/v4.1.0 ==> Critically important fixes to the cookie handling. All older versions of this library are slowly breaking completely, because Photo Social Network is currently moving all cookies to a new domain. Soon, all accounts will be affected. If your account is affected, you suddenly won't be able to do any API calls because the new token cookie location cannot be found by older library versions! Version 4.1.0+ of this library is the only version with support for the new cookie location. All older library version users MUST upgrade now.

New features:

* Updated library Photo Social Network-API to version 4.1 - Minimum PHP v5.6 compatible. All stuff belonging to the API is now in the vendor directory.

	This is Photo Social Network's private API. It has almost all the features the Photo Social Network app has, including media upload, direct messaging, stories and more.
	**Read the [wiki](https://github.com/mgp25/Photo Social Network-API/wiki)** and previous issues before opening a new one! Maybe your issue has already been answered.
	**Frequently Asked Questions:** [F.A.Q.](https://github.com/mgp25/Photo Social Network-API/wiki/FAQ)

* Add a column in admin page of posts to see Photo Social Network status

* In admin page you now have at the bottom the status of all required librairies and php version needed

* Add a new feature to attach your wordpress post link to the end of the Photo Social Network caption

* Add a new feature to receive notification by email of your succeeded/failed status of a photo posted to Photo Social Network

* Add a new feature to add more emails recipients to receive notification

* In Photo Social Network status you now have icons ( good , bad , or never published )

* Link to your photo on Photo Social Network now appears in the Photo Social Network status of your post

* Use of excerpt from a post - Feature request from jeffmar ( #https://wordpress.org/support/topic/request-new-features-and-comments-on-bugs/ ) and lmah200176 ( https://wordpress.org/support/topic/text-of-the-post-2/) 

* Tested in Wordpress 5.2.1

= 1.5.2 =

Bug corrected :

* Updating Logos and small fixes

New features:

* Tested in Wordpress 5.2.1

= 1.5.3 =

Bug corrected :

* Cosmetic fixes in the setting page

New features:

* It is now possible to use an Photo Social Network proxy - Request from Steffen(@stevie77) #https://wordpress.org/support/topic/auto-post-to-instagtram-1-5-2-not-working/

* Tested in Wordpress 5.2.2

= 1.5.5 =

* Change Plugin Name 