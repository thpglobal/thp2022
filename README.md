# thp2022
* WordPress 6.1 Full Site Editor (FSE) Theme matching thp.org Divi Theme
* FSE is different from older "classic" themes - for an 8 minute crash course. watch [this youtube video.](https://www.youtube.com/watch?v=u9TX2X82R18) 
## Note: This is the THP-Germany version.
* Since the footers live in the theme, you might want to contact jc@thp.org to get copies adjusted for en.thpbd.org or advocacy.thp.org
@@ To install on an existing site, follow these steps
1. If you are converting from an existing non-FSE site, print the home page to a PDF so you can easily access your footer. The footer data is store now in the theme, not the database, so the first time you use it you'll need to copy and paste it from somewhere or type it in.
1. Add the search25.png file to your media library. I'm sure there must be a way I could build it into the theme, but I've not figured it out!
1. Download the code as a zip file from here and upload it as a new theme and activate it.
1. Go into site editor and edit the header to add your site logo. To import your old "Primary Menu" into the FSE menu, click on the navbar and in the settings select which men. AFter it imports, you should no longer mess with the old classic menus but make any needed changes in site editor.
1. The header contains a custom HTML block for the search icon and the Give Now image - edit it to tasste
1. go to <yoursite>/wp-admin/customize.php and add these line to the Additional CSS window and save it:
```
header {position:sticky !important; top:0; background-color:white; z-index:100; margin-bottom:-25px !important;}
.countup {text-align:center;font-family:sans-serif; font-size:50px;}
a.wp-block-button__link {border:2px solid blue;padding:5px 20px !important;}
a.wp-block-button__link:hover {color:white; background-color:#0000aa;}
```
## To build a site with this theme on a new empty site,
* Create the pages you want linked to your main menu first.
* Then follow the steps above. The navigation bar will initialize to the pages you've created, and you can move them around.

