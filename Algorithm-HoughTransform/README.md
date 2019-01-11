## About Hough transform

The classical Hough transform was concerned with the identification of lines in the image,
but later the Hough transform has been extended to identifying positions of arbitrary shapes,
most commonly circles or ellipses. The Hough transform as it is universally used today 
was invented by Richard Duda and Peter Hart in 1972, who called it a "generalized Hough transform" 
after the related 1962 patent of Paul Hough (Method and means for recognizing complex patterns, 
U.S. Patent 3,069,654, Dec. 18, 1962)

## Identification of Lines 
Hough_phone.py is designed to
  * get all edges in the image (currently phone.jpg)
        cv2.Canny
  * get all lines having not less than 'min_line_len' edges
        cv2.HoughLinesP

In the result image 'phone_hough_transform' we see 
edges in the middle image and red lines in the right one.    		