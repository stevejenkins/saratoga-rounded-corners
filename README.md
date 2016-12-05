# saratoga-rounded-corners
CSS add-on to create rounded corners in Saratoga weather templates (http://saratoga-weather.org/template/)  
By: Steve Jenkins

My personal site: http://www.stevejenkins.com/  
My weather sites: http://weather.lakewebster.com/ & http://weather.sanfordshores.com/

##INSTRUCTIONS##

1) GitHub users, clone this repo into the root directory of your weather site with:

`https://github.com/stevejenkins/saratoga-rounded-corners.git`

Or download the zip file into your weather site's root directory and extract the contents into a new directory named `/saratoga-rounded-corners/`.

2) Edit `top.php` in the root directory of your weather site and find the following lines:

    <link rel="stylesheet" type="text/css" href="<?php echo $SITE['CSSscreen']; ?>" media="screen" title="screen" />
    <link rel="stylesheet" type="text/css" href="<?php echo $SITE['CSSprint']; ?>" media="print" />

Add the following line immediately **BELOW** those two lines:

    <link rel="stylesheet" type="text/css" href="/saratoga-rounded-corners/rounded.css" media="screen" title="screen" />

Et... *VOILA!* You should now have rounded corners for the default Saratoga Templates!

Of course, if you've previously modified your CSS, this may or may not work for you.

There's not really much damage this file can do, but I'll include a standard disclaimer anyway:

**USE THIS FILE AT YOUR OWN RISK! If it:**

- blows up your computer
- causes heart disease
- gives you flatulence or bad dreams
- makes your ex-wife come back and ask you for more alimony

...you're on your own. :)

Discussion of this CSS file is here:

http://www.wxforum.net/index.php?topic=25124.0

Enjoy!
