# thp2022
* WordPress 6.1 Full Site Editor Theme matching thp.org Divi Theme
* To install it takes several steps:
1. Download the code as a zip file from here and upload it as a new theme and activate it.
2. Go into site editor and edit the header to add your site logo. To import your old "Primary Menu" into the FSE menu, click on the navbar and in the settings select which men. AFter it imports, you should no longer mess with the old classic menus but make any needed changes in site editor.
3. go to <yoursite>/wp-admin/customize.php and add these line to the Additional CSS window and save it:
```
header {position:sticky !important; top:0; background-color:white; z-index:100; margin-bottom:-25px !important;}
.countup {text-align:center;font-family:sans-serif; font-size:50px;}
a.wp-block-button__link {border:2px solid blue;padding:5px 20px !important;}
a.wp-block-button__link:hover {color:white; background-color:#0000aa;}
```

