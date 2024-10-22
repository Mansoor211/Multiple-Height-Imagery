# Multiple-Height-Imagery
The Dataset emerged as one of the most challenging aspects of this research undertaking. The project necessitated the acquisition of a dataset comprising downward-looking drone camera images exhibiting a minimum overlapping of 75%–80% between consecutive images. Unfortunately, the existing stereo image datasets available in the market mainly consisted of street views or images of objects in confined spaces with limited variations in depth. Consequently, the creation of a custom dataset became imperative to cater to the specific requirements and objectives of this project. 

Data Acquisition: The data gathering process necessitated the utilization of a professional drone equipped with the capability to fly at various heights, including higher altitudes. In addition, a suitable location was chosen for the drone flights, leading to the selection of the NUST Main Campus,H-12 Islamabad. A total of 10 flights were eticulously planned to cover a diverse range of 10 different heights. The drone employed for data collection was the Phantom 4 Pro, which conducted multiple flights over the NUST Main Campus to collect the necessary data. The dataset encompassed data gathered at 10 distinct heights, commencing from 100 m and ascending in increments of 20 m up to 280 m. 

To optimize the drone flights, the area of interest was defined using the Pix4dcapture mobile app, and its Grid 2D option was utilized for setting the flight paths. This app provides different options in which if you select the area on map, start point, end point, height, and front/side overlapping, it will automatically send the drone to capture images as per the area selected. The consecutive images (with overlapping) were then used as pairs. About, 80% front overlapping (consecutive images) and 20% side overlapping were used to capture maximum images from a specific area (front overlapping is more relevant in consecutive images). The consecutive images as pairs with 80% overlapping were used. As far as “base” distance is concerned, it was automatically adjusted as per the height of the UAV so that overlapping remains the same (80%), and the base distance is not used as a parameter during training. For further insights, refer to research paper link below.


Research Paper:
https://ieeexplore.ieee.org/document/10582419

Dataset Link
https://drive.google.com/drive/folders/1hzCqH5LxRMypbz_8alxzVNmkiIY_Difb?usp=sharing
