# GeographicalDataExtraction-
This script scrape data from openstreet map in a selected area. For complete details read the Geographical_data_extraction_read.PDF file. For an overview just go through below pics.

</br> Here is the complete flow chart of how the algorithm works
![Screenshot](images/image1.png)

* Step:1
 
An area of one km radius is selected first.
</br>
![Screenshot](images/image2.png)

</br>
All the nodes in that area are scrapped. The Json files include all the properties. 
</br>
![Screenshot](images/image3.png)

</br>
This algorithm cut off the areas outside the buffer area in this way. 
</br>
![Screenshot](images/image4.png)
</br>

Finally we obtain all the entities, Polygons, road networks.
</br>
![Screenshot](images/image5.png)
</br>
