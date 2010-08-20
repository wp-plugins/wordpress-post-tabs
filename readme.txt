=== WordPress Post Tabs ===
Contributors: Tejaswini Deshpande, Sanjeev Mishra
Tags:post, page, tabs, menu, ui-tabs, sections, options, edit, shortcode, navigation 
Donate link: http://www.clickonf5.org/go/donate-wp-plugins/
Requires at least: 2.7
Tested up to: 3.0.1
Stable tag: 1.0

You can add various tabs to your WordPress Post or Page easily through the edit post/page panel so that your posts and pages have well organized tabbed sections.

== Description ==

WordPress Post Tabs is a plugin for WordPress that will help you add as many tabs to your WordPress post or Page. So, say if you want to write some review, you can create various sections of the review post and display them in a tab view, i.e. separate tab for each section. This can be looked as a menu for your individual post, so that your readers can easily notice the distinct sections of your article or post or page. 

As you can see the format of gadgets review on PCWorld and CNET where they provide different sections like specifications, user review, full review, shop etc in different tabs. Similar format is visible on different automobile review sites. In fact the tabbing format is useful for movies review and recipes sites. You can use one tab for picture gallery and other tab for detailed review. To make your post more interesting, you can add videos under one tab as well.  

=Features:=

* You can choose from different styles, the looks of your post tabs. In fact you can easily create your own style, or download some pre-designed styles from the plugin page.
[Download Custom Styles] (http://blogern.com/wordpress-post-tabs/)
* You can choose to reload or not to reload the page (AJAX like) every time the tab is clicked by the reader.
* If you disable the loading of the plugin on posts and pages, this plugin will not load any extra script on your other pages where you do not select to use the tabs. You would get a checkbox on each post and page, to enable the plugin on that particular page. So, for other posts and pages, there is no extra script load in the footer, and your pages remain optimized.
* The tabs are unobtrusive and will make your posts and pages very well organized and readable for the readers.

[Demo](http://blogern.com/2010/08/20/review-dell-mini10-inspiron-netbook/) |
[Plugin Information](http://blogern.com/wordpress-post-tabs/)

== Installation ==

This plugin is easy to install like other plug-ins of WordPress as you need to just follow the below mentioned steps:

1. Copy Folder 'wordpress-post-tabs' from the downloaded and extracted file.

2. Paste it in 'wp-Content/plugins' folder on your WordPress Installation 

3. Activate the plugin from Dashboard / Plugins window.

4. Now Plugin is Activated, Go to the Usage section to see how to use WordPress Post Tabs.

== Usage ==

* To insert the tabs, you would need to use two shortcodes on your Edit Post/Page admin panel. The first shortcode is for tab names and the second shortcode represents the end of the set of the tabs. You can insert multiple number of tabset on a single page.
* Example how to put tabs:


`[tab name='Overview']
This is the overview section.
[/tab]

[tab name='Specifications']
Various product Specifications can be entered here.
[/tab]

[tab name='Screenshots']
You can insert images or screenshots of the product. 
[/tab]

[end_tabset]`

**Do not forget to insert the 'name' attribute for each tab. It is important 
** Just remember to put the 'end_tabset' shortcode at the end of all tab contents as shown above.
* On the 'Post/Page Tabs' Settings on your WordPress admin, you can select your style. Currently there are three styles - default, gray and red. You can add your own styles easily. Please refer the plugin page how to add the custom styles, its just 2 minute work.
* In case you wish to reload the page every time another tab is clicked, you can select that option from the settings page. This would be helpful if you wish to count these pageviews as well.
* If you check the 'Disable loading on all Posts' option, this will disable the plugin on the posts all together and you will get a custom box 'Enable Post/Page Tabs Feature' on your Edit Post panel. Now you can check this checkbox for those posts only where you wish to enable the tabs. This will prevent the loading of the script and style specific to this plugin on all other pages.
* Same as above is the case with 'Disable loading on all Pages', its for pages.
* You can replace the default shortcodes with your own, that are comfortable for you. 

== Screenshots ==

1. Tab 1 on post
2. Another tab on post (gallery tab)
3. Usage on Edit Post Panel

Visit the plugin page (http://blogern.com/wordpress-post-tabs/) to read more about it.

== Changelog ==

This is the first release of the plugin, so we would include the change log in the upcoming releases which will contain the new features added to this plugin in the respective versions

Visit the plugin page (http://blogern.com/wordpress-post-tabs/) to see the changelog and release notes.