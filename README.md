### A CodeIgniter skeleton application based on twitter bootstrap 2.1.1 and html5boilerplate 4.
---------------------------------------------------
	VERSION 1.2
Update libraries:
* Codeigniter 2.1.2
* bootstrap 2.1.1
* html5boilerplate 4.0.0
* Modernizr 2.6.2
* jQuery 1.8.1
* underscore.js 1.3.3
---------------------------------------------------
* Framework Codeigniter
* Twitter bootstrap
* html5boilerplate
* unique style css contains all bootstrap css (responsive and basic), ang global css for custom styles.
* unique plugin js contains all bootstrap plugins.
* view rendering handled by a smart MY_Controller.
* jQuery
* underscore.js
* nav_helper
* Modernizr
* .htacces tip for remove index.php
* basejs view always include in page. (usefull to access via js some server side information e.g. base_url())

USAGE
-------------------
1. edit .htaccess file in order to match your server config (see line 5 in the file);
	if you have http://localhost/site you nedd to set RewriteBase /site/
2. set up yor defaults values in application/config/development/custom.php
3. take a look to home controller and template view files to understand how does rendering works.
4. create your template: i've set up an header, footer, nav, and main for example purpose. Skeleton.php contains the scaffolding page.
5. pass your data to the view using in controller $this->data["my_var"] = "value";
