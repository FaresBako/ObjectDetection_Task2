What 3 objects were chosen and why?


I chose Mouse, Pen and Perfume. Mouse because of the shape and how it is easy to detect unlike the pen it was small and thin that the system barely able to detect it, it was a bit difficult for the AI to detect it, finally the perfume it was the biggest object and there was some textures in it that can maybe distinguish it from other objects.



How did you collect and split the data?



I gathered the data manually by taking a pic for each object, then labeled them by label studio and extract them in YOLO form which later through google colab we unzipped the data and by YAML we split the data and train and validate it.

In running the model i used an external source to run the python code 

the source: https://www.ejtech.io/code/yolo\_detect.py





What challenges or false detections occurred, and what would you do to improve detection accuracy?



I struggled with the pen it was hard to detect it because of its small shape. one of the solution is feeding the model more pictures of the object and train it more, and increase the number of epochs.









