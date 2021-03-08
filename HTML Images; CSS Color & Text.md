# HTML Images; CSS Color & Text

# Images

# Choosing Images for Your Site
As a website grows, keeping images in a separate folder helps you understand how the
site is organized. Here you can see an example of the files for a website; all of the images are
stored in a folder called images.On a big site you might like to add subfolders inside the images
folder. For example, images suchas logos and buttons might sit in
a folder called interface, product photographs might sit in a pagecalled products, and images
related to news might live in a folder called news

<img scr="https://user-media-prod-cdn.itsre-sumo.mozilla.net/uploads/gallery/images/2019-01-06-11-03-35-1fd7e9.png">

# Height & Width of Images
You will also often see an <img>element use two other attributes that specify its size:
height This specifies the height of the image in pixels.
width This specifies the width of the image in pixels

# Where to Place Images in Your Code
Where an image is placed
in the code will affect how it
is displayed. Here are three
examples of image placement
that produce different results:
# before a paragraph
The paragraph starts on a new
line after the image.
# inside the start of a
paragraph
The first row of text aligns with
the bottom of the image.
# in the middle of a
paragraph
The image is placed between the
words of the paragraph that it
appears in.

# EX
<img src="images/bird.gif" alt="Bird" width="100"
height="100" />

# Three Rules for Creating Images

There are three rules to remember when you
are creating images for your website

# Save images in the right format
# Save images at the right size
# Use the correct resolution

# Tools to Edit & Save Images
The most popular tool amongst web professionals is Adobe Photoshop. (In fact, professional web designers often use this
software to design entire sites.) The full version of Photoshop is expensive, but there is a cheaper
version called Photoshop Elements which would suit the needs of most beginners

# Cropping Images
When cropping images it is important not to lose valuable information. It is best to source
images that are the correct shape if possible.

# Image Resolution
Images created for the web should be saved at a resolution of 72 ppi. The higher the resolution
of the image, the larger the size of the file

JPGs, GIFs, and PNGs belong to a type of image format known as bitmap. They are made up of
lots of miniature squares. The resolution of an image is the
number of squares that fit within a 1 inch x 1 inch square area.

# Vector Images
When an image is a line drawing(such as a logo, illustration, ordiagram), designers will often
create it in vector format.Vector formatted images arevery different to bitmap images.
Vector images are created by placing points on a grid, and
drawing lines between those points. A color can then be
added to "fill in" the lines that have been created.
The advantage of creating line drawings in vector format is that
you can increase the dimensions of the image without affecting the quality of it.

# Animated GIFS
Below you can see the individual frames that make up an
animated GIF that shows an orange dot revolving around
a circle — like the kind of animation you might see when aweb page is loading

# Transparency

If the transparent part of the image has straight edges and it is 100% transparent (that is,
not semi-opaque), you can save the image as a GIF with the transparency option selected
# Examining Images on the Web

If you are updating a website, you might need to check the size of an
existing image before creating a new one to replace it. This can be
achieved by right-clicking on the image and making a selection from
the pop-up menu that appears. (Mac users will need to hold down the
control key and click rather than right-click.)
Downloading Images
If you want to download images from a website, you can do so by
accessing the same pop-up menu. (Please remember however that all
images online are subject to copyright and require explicit permission to
reuse.)
On the left you can see how tocheck the size of images and how to download them using
Safari. Below is a brief overviewof what to select in the pop-up menu to perform these functions
in various browsers

# Example
<html>
<head>
<title>Images</title>
</head>
<body>
<h1>
<img src="images/logo.gif"
alt="From A to Zucchini" />
</h1>
<figure>
<img src="images/chocolate-islands.jpg"
alt="Chocolate Islands"
title="Chocolate Islands Individual Cakes" />
<p>
<figcaption>
This recipe for individual chocolate
cakes is so simple and so delectable!
</figcaption>
</p>
</figure>
<h4>More Recipes:</h4>
<p>
<img src="images/lemon-posset.jpg"
alt="Lemon Posset"
title="Lemon Posset Dessert" />
<img src="images/roasted-brussel-sprouts.jpg"
alt="Roasted Brussel Sprouts"
title="Roasted Brussel Sprouts Side Dish" />
<img src="images/zucchini-cake.jpg"
alt="Zucchini Cake"
title="Zucchini Cake No Frosting" />
</p>
</body>
</html>

