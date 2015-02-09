# saratoga-rounded-corners
CSS add-on to create rounded corners in Saratoga weather templates  
By: Steve Jenkins

Personal site: http://www.stevejenkins.com/  
Weather site: http://weather.lakewebster.com/

**INSTRUCTIONS**

1) Extract and save the weather-rounded-corners.css file in the root directory of your weather website

2) Edit top.php and find the following lines:

    <link rel="stylesheet" type="text/css" href="<?php echo $SITE['CSSscreen']; ?>" media="screen" title="screen" />
    <link rel="stylesheet" type="text/css" href="<?php echo $SITE['CSSprint']; ?>" media="print" />

Add this line immediately BELOW those two lines:

    <link rel="stylesheet" type="text/css" href="/weather-rounded-corners.css" media="screen" title="screen" />

And... VOILA! You should now have rounded corners for the default Saratoga Templates!

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
