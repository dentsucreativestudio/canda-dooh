# C&A HTML Display for Digital Out of Home

# Add images to images folder

* Navigate to the [images folder](https://github.com/dentsucreativestudio/canda-dooh/tree/main/images) and click on the folder that image should be uploaded.
* Click on the **add file** dropdown button on top left. Select **upload files**. Either drag and drop or select the image from your computer, multiple images are allowed.
* At the bottom left of the page click on the green **Commit changes** button and wait until the changes are done. (You can skip the comments on this step).
* The images should be available within +-one minute to propagate in the server.

### Horizontal Images 

Image directoy path horizontal:
https://dentsucreativestudio.github.io/canda-dooh/images/horizontal

Example of final horizontal image:
https://dentsucreativestudio.github.io/canda-dooh/images/horizontal/canda-horizontal-02.jpg

### Vertical Images 

Image directoy path vertical:
https://dentsucreativestudio.github.io/canda-dooh/images/vertical

Example of final vertical image:
https://dentsucreativestudio.github.io/canda-dooh/images/vertical/canda-vertical-01.jpg


# Data Entry

This files determine the date, time and image urls. The time of each entry indicates the time until the current image will be displayed.<br>


### Edit dates:

* Navigate to [data folder](https://github.com/dentsucreativestudio/canda-dooh/tree/main/data) to edit the [horizontal settings](https://github.com/dentsucreativestudio/canda-dooh/blob/main/data/horizontal-images-settings.js) or [vertical settings](https://github.com/dentsucreativestudio/canda-dooh/blob/main/data/vertical-images-settings.js). 
* Click the **pencil icon** on top right corner to enter into edit mode. Make your chenges.
* At the bottom left of the page click on the green **Commit changes** button and wait until the changes are done. (You can skip the comments on this step).
* The data should be available within +-one minute to propagate in the server.

date: monthday *// example -> 1128* <br>
time: hourminute *//example -> 1230* <br>
image: 'path/to/url' *// example -> https://dentsucreativestudio.github.io/canda-dooh/images/horizontal/canda-horizontal-02.jpg* <br>

