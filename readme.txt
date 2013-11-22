*********************************************
*           Simple Template                 *
*By J. Marie Mayer / Laughing Dragon Studio *
*********************************************

Use of this template is permissible under the following conditions:
-Do not claim this template as your own
-Do not remove the tag in the footer, linking to my site.


**Instructions for customization**

Create a file in the includes>pagecontent folder for each page. 
This file should only include the div tag (<div id="content">), the
information that you want shown, and the closing tag (</div>). All
other coding is presented in the .css file, included.

For each page you want displayed, create a file based on the index.php
page. Replace the following:
     <?php include('includes/pagecontent/index.php')?>
with the name of the page you created above. For example:
     <?php include('includes/pagecontent/aboutme.php')?>

Keep in mind that many servers require that the capitalization of 
the files matches the call for them. 


**Images**
*Banner*
You can replace the banner with your own two ways:
1) Create a banner that is 150 pixels tall, by 
the width that you prefer. Add the file to the images folder
and replace the following code in the includes>header.php file
	<img src="../images/banner.png">
with the name of your banner. For example:
    <img src="../images/topimage.png">

2) You can open the file images>banner.png in a program such as
Photoshop or GIMP and change it, saving over the old file, and thus
keeping the code the same

*Navigation*
Similarly, you can replace the image next to the links by replacing 
the call for it in the includes>navigation file:
    <img src="../images/star.png">
With something like:
    <img src="../iamges/pawprint.png"> 
    
    
**Navigation links**
Replace the links in the includes>navigation.php with the links 
for your site or external sites.

*For pages on your site*
You do not have to include the http://domain. Merely add the name
of the page, such as:
<a href="aboutme.php">About Me</a>

*For pages not on your site*
You DO have to include the http://domain, such as:
<a href="http://google.com">Google</a>


*********************************************
*Any questions or concerns can be directed  *
*to me at laughingdragonstudio@gmail.com. I *
*also take commissions for custom, more     *
*elaborite templates and websites. For info *
*go to:                                     *
*http://laughingdragonstudio.zymichost.com  *
*                                           *
*                  ENJOY!                   *
*********************************************
