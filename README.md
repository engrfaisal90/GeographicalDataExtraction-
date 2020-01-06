# GeographicalDataExtraction-
This script scrape data from openstreet map in a selected area. For complete details read the PDF file. For an overview just go through below pics.

</br> Here is the complete flow chart of how the algorithm works
![Screenshot](images/image1.png)

An area of one km radius is selected first.
![Screenshot](images/image2.png)

All the nodes in that area are scrapped. The Json files include all the properties. 
![Screenshot](images/image3.png)

This algorithm cut off the areas outside the buffer area in this way. 
![Screenshot](images/image4.png)

Finally we obtain all the entities, Polygons, road networks.
![Screenshot](images/image5.png)
