=== Zoho Creator Forms ===

Contributors: RamyaD
Donate link: http://www.zoho.com/
Tags: forms, online forms, embed forms, zc forms, zohocreator forms, zc embed forms, zoho creator, creator forms, zoho forms, zoho online forms, embedding creator forms, zohocreator forms, embedding zohocreator forms, form builder, zohocreator forms and views
Requires at least: 2.8
Tested up to :4.3.1 
Stable tag:1.0.5

Embed Zoho Creator forms and views into your wordpress posts.

== Description ==

The ZohoCreator plugin can be used for embedding your [Zoho Creator](http://www.zoho.com/creator/online-form-builder/index.html "Zoho Creator") forms and views in WordPress blog posts. You can also customize your form background. 


To use this plugin you need an account in Zoho Creator. [Signup at Zoho Creator](https://www.zoho.com/creator/signup.html).

The plugin will add a button to the TinyMCE editor which, when clicked, will ask you to sign in, if you are not logged in Creator, then after sign in, you can choose your form or view. A shortcode will be created in the editor, and the form or view will be rendered in your WordPress blog.  Customizing your form background is also allowed, you can specify the background colors of the "Form", "Hedder"and "Footer".

You can also type the shortcode by yourself in the editor, like the one specified below.

[creator src="https://creator.zoho.com/username/form_link_name/form-embed/form_name"]

== Installation ==

You can download and install zohocreator using the built in WordPress plugin installer. If you download ZohoCreator manually, make sure it is uploaded to your "/wp-content/plugins/zohocreator/".

Activate ZohoCreator in the "[Plugins](http://codex.wordpress.org/Administration_Panels#Plugins)" of your admin panel using the "[Activate](http://codex.wordpress.org/Plugins_Screen)" link. After activating the plugin you can see a Zoho icon in your TinyMCE editor.

== Frequently Asked Questions  ==

= Can I provide the height and width of my form/view? =

Yes. You can change the default height and width settings while you provide the permalink in the TinyMCE editor. If you directly type the shortcode yourself, you can specify like the one given below

[creator src="https://creator.zoho.com/userName/application_link_name/form-embed/form_link_name" width=500 height=300]

== Changelog ==
= 1.0.5 =
* tinymce version related changes

= 1.0.4 =
* Issue Related to file path fixed

= 1.0.3 =
* Issue Related to installation fixed
 
= 1.0.2 =
* Allow selecting your Creator form or view

= 1.0.1 =
* Allow customization of background color

= 1.0 =
* Allow embed of form/view using their permalink


