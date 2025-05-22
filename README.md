# Image-to-pencil-sketch-converter

The basic steps involved in converting an image to a pencil sketch are-

1.Read the image.
2.Convert to grayscale.
3.Invert the grayscale image.
4.Apply Gaussian blur to the inverted image.
5.Invert the blurred image.
6.Blend the grayscale image with the inverted blurred image using cv2.divide().
