[ruTorrent better UI](https://github.com/stevefromthenet/ruTorrent-better-ui)
========================
Only Tested with [ruTorrent](http://code.google.com/p/rutorrent/) 3.4 but may work with older versions.

Screenshots
-----------

**Before**
![Before](http://i.imgur.com/d68Az.png)

**After**
![after](http://i.imgur.com/ElfJF.png)


Quick Start
-----------

1. Navagte to your ruTorrent folder.
 
	@cd ~/public_html/rutorrent/ 

	*NOTE*: This may not be your path but it should be something simlar)


2. Backup the files your replacing.

	@cp index.html index.html.backup && cp css/style.css css/style.css.backup

3. now download files off github and upzip them
	@wget https://github.com/stevefromthenet/ruTorrent-better-ui/tarball/master
	@tar zxf master

4. Move your files into place

	@mv stevefromthenet-ruTorrent-better-ui-*/css/style.css css

	@mv stevefromthenet-ruTorrent-better-ui-dc956f0/index.html .




