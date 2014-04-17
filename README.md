Numpad (Sencha Touch Plugin)
======

Numpad plugin comes in handy when you want to avoid showing the full keyboard.

Installation video guide: http://www.screencast.com/t/vdkEd25Ek5Pt

Products: Sencha Touch 2.x

Browsers: Windows Phone (mobile) Blackberry (mobile) Android (mobile) iOS (mobile)

Authors: 
- Sebastian Tomescu - sebastian.tomescu@gmail.com
- Silviu Durduc - iamsilviu@gmail.com

Installation
======

 
***Numpad plugin is composed of two parts:***

 1. JavaScript ( 2 files ) [ Required ]
 2. SASS ( 2 files ) [ Optional ]


***Quick install:***
	
	Copy the ST_2~ content folder and paste it in your solution 
	(make sure your Sencha Touch sdk is 2.0+) 
	press yes to overwrite ( no files will be replaced ).


***Quick usage:***

	You can include numpadfield in your app.js 
	or you can use it in your component view like: 

	requires : ['Ext.ux.numpadfield'] 

	and add it as an item with:

	xtype : 'numpadfield'

	Notes: 
	Supports all confings and methods from Ext.field.Text.

***Configuration**

  - inherits Ext.field.Text configs
  - singleDot {Boolean} Default: true // allow multiple "." chars
  - disableFloatValues {Boolean} default: false // Relpace "." button with "00"

***Skining***
  - CSS skins can be found in extras folder and can be used as reference
  - SASS skins are found in resources/sass/_{skinName}. Usage: @import 'numpadDROID'
  
