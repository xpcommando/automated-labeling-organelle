Using OpenCV2 to detect the shape of organelles, we can extract the points representing the shape. 
These points can serve as the label data for the organelle, eliminating  manual labeling in training, 
and the need for fluorescence staining in the future organelle detection.

Prepare: fluorescence images(TRITC.png), 
         refractive index images(RI.png), 
         label file(sample_label.json) in any one 

1.Put in a label file  for initializing the new label file's frame

2.Put in a fluorescence image and relevant refractive index image

3.Run

4.Got the new label file of refractive index image

