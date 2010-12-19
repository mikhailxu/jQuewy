![jQuewy](http://jquewy.com/img/logo_small.png)

## What is jQuewy?

Put simply, jQuewy is a library for easy loading of other libraries.
More specifically, jQuewy collects the latest libraries online, and automatically inserts them into the header of your page. This allows you to forget the urls of individual libraries, and focus on what's more important - especially when prototyping - the custom logic your site will depend on.

##Usage:

	$j("jquery","ui","tools",function(){
		// The scripts are ready to use
	});
	
or
	$j(["jquery","ui","tools"],function(){
		// The scripts are ready to use
	});

or
	$j("jquery,ui,tools",function(){
		// The scripts are ready to use
	});

## Supported libraries

Add the following to the header, or in a firebug prompt:
	$j.list();

## More info, and contact
To find the version you are using, use `$j();`
Contact us at [http://jquewy.com/](http://jquewy.com/).
