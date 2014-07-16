codex-menu
==============

Highly customizable light weight Right click menu plugin

you can use either with "jquery ui" library to get extra aniamtion effect on menu showing animation or else you can also use only with "jquery" library
Any one who knows basic javascript or jquery can easily use this plugin 




![alt tag](https://raw.githubusercontent.com/anishtr4/codex-menu/master/demo.png)

## Basic usage

$("body").codexmenu({});


## Settings

you change "body" to any selector
in menu item should be like 

'name' : 'link or function name'

if u want to define a function use "funct_" before function name (eg: funct_demofunction())

    $("body").codexmenu({
	menuitem : {
        Home : 'form.html',
		Nextpage : 'http://www.youtube.com',
		Tottalpages : 'funct_newfunction()',
		Find_us_on_facebook : 'http://www.facebook.com',
		Refresh : 'www.google.com',
		Exit : 'www.google.com'
    },
	jquery_ui :  'yes',
	animation     : 'bounce',/* if u are using jquery_ui(slide,fold,bounce,,scale)*/
	speed     : '1',
    item_bg     : '#ffff',
	item_hover_bg     : '#ffff',
	}); 


## License

Released under the MIT License.
