Frank Lin, 3032804062, fklin@berkeley.edu, https://franailin.github.io/cs194-proj1/

Main code file: main.ipynb



Run each cell consecutively to get results

methods:

metric(image1, image2) - calculates SSD between two images

crop_and_combine(im):
im is an image result from sk.img_as_float, and this method will align the blue, red, and green channels from a small jpg. It returns the best dx and dy for translation, and also the translated image.

pyramid_search(im):
im is an image result from sk.img_as_float, and this method will align the blue, red, and green channels from a tif. It returns the best dx and dy for translation, and also the translated image.

The last two cells loop through every image and tif and calls the appropriate function (either crop_and_combine or pyramid_search) and displays the results.