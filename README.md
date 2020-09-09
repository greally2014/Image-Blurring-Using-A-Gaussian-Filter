## Description
This project was conducted as part of my lab in computer physics programming in the third year of my physics degree. It blurrs an image using a Gaussian filter, a method commonly used by photo-editing software.

The method involves determining the Fourier transfrom of an image in the form of an array. A Fourier transform takes one from the spatial domain of an image to its frequency domain. The application of a Gaussian filter to the frequency domain of an image applies a blurring effect. This blurring effect is the result
of the filter removing particular frequency components of the image.

High-frequency components of an image are those subject to great change in pixel colour with little variance in pixel position. For example, a high-frequency component would be a strand of hair on someone's head. On the other hand, a low-frequency component is one with low variance in pixel colour with a large change in pixel position. An example of this would be a pixel composing part of a wall that makes up a large part of a picture. There is little change in pixel colour as you move along the wall.

By applying a filter, you can allow only low-frequency or high-frequency components to pass. This allows you to control what is blurred. If one filters out high-frequency components the "fine details" of an image are blurred. These include the edges of objects and surfaces, the corners of walls and strands of hair. If one blurs out all of the low-frequency components of an image, only the detail remians. This is commonly used in forensic analysis to remove the unnecessary clutter from images of crime scenes.

## Installation
Download and run the file on Jupyter Notebook.

## Required Python Libraries
Numpy
Scipy
Matplotlib
Pylab

## Usage
This program requires the image "OneCircle.png" which can be found in the repository.
