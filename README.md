# C&A HTML Display for Digital Out of Home

# Add images to images folder

Keep the naming convention in such way images don't overide each other, so the total of images can be presented on the day after in random order. 
 >Images should be less than 1Mb preferably. Optimize images before uploading, example like [tinypng](https://tinypng.com/) is great to compress images reducing image filesizes and preserving quality.

* Navigate to the [images folder](https://github.com/dentsucreativestudio/canda-dooh/tree/main/images) and click on the folder that image should be uploaded.
* Click on the **add file** dropdown button on top left. Select **upload files**. Either drag and drop or select the image from your computer, multiple images are allowed.
* At the bottom left of the page click on the green **Commit changes** button and wait until the changes are done. (You can skip the comments on this step).
* The images should be available within +-one minute to propagate in the server.

### Images folders
* Images [Wijnegem (03/12) => 11:00 to 18:00](https://github.com/dentsucreativestudio/canda-dooh/tree/main/images/01-wijnegem)
* Images [Antwerpen (04/12) => 13:00 to 17:00](https://github.com/dentsucreativestudio/canda-dooh/tree/main/images/02-antwerpen)
* Images [Belle Ile (10/12) => 11:00 to 18:00](https://github.com/dentsucreativestudio/canda-dooh/tree/main/images/03-belle-ile)
* Images [Belle Etoile (11/12) => additional location](https://github.com/dentsucreativestudio/canda-dooh/tree/main/images/05-belle-etoile)
* images [Waasland (17/12) => 11:00 to 20:00](https://github.com/dentsucreativestudio/canda-dooh/tree/main/images/04-waasland)

# Data Entry

* Data [Wijnegem](https://github.com/dentsucreativestudio/canda-dooh/tree/main/data/01-wijnegem)
* Data [Antwerpen](https://github.com/dentsucreativestudio/canda-dooh/tree/main/data/02-antwerpen)
* Data [Belle Ile](https://github.com/dentsucreativestudio/canda-dooh/tree/main/data/03-belle-ile)
* Data [Belle Etoile](https://github.com/dentsucreativestudio/canda-dooh/tree/main/data/05-belle-etoile) additional location
* Data [Waasland](https://github.com/dentsucreativestudio/canda-dooh/tree/main/data/04-waasland)


### Edit Images:

The images on rotation for the photo shoot day are the top 3 in the list. When adding new images add them above the existing images.
Image path example: 'path/to/url' *// example -> https://dentsucreativestudio.github.io/canda-dooh/images/04-waasland/Brand_Xmas_Shooting_1080x1920px_Anna.jpg* <br>

```
var settings = [
  //New images added above
  { image: 'https://dentsucreativestudio.github.io/canda-dooh/images/02-antwerpen/new_image_xxx.jpg'},
  { image: 'https://dentsucreativestudio.github.io/canda-dooh/images/02-antwerpen/new_image_yyy.jpg'},
  { image: 'https://dentsucreativestudio.github.io/canda-dooh/images/02-antwerpen/new_image_zzz.jpg'},
  //all other images below
  { image: 'https://dentsucreativestudio.github.io/canda-dooh/images/02-antwerpen/Brand_Xmas_Shooting_1920x1080px_Anna.jpg'},
  ...
];
 ```

* Navigate to [data folder](https://github.com/dentsucreativestudio/canda-dooh/tree/main/data) to edit and add new images to the list. 
* Click the **pencil icon** on top right corner to enter into edit mode. Make your chenges.
* At the bottom left of the page click on the green **Commit changes** button and wait until the changes are done. (You can skip the comments on this step).
* The data should be available within +-one minute to propagate in the server.



# HTML preview links

For pre-visualisation of what will be displayed in the DOOH screens.

###  Wijnegem:
* Live pictures on 3/12: [Preview](https://dentsucreativestudio.github.io/canda-dooh/HTML/canda_01_wijnegem_v1_photo_session_HTML_1080x1920/index.html)
* Pictures of previous days in random order on 4/12: [Preview](https://dentsucreativestudio.github.io/canda-dooh/HTML/canda_01_wijnegem_v2_day_after_HTML_1080x1920/index.html)

### Antwerp
* Live pictures on 4/12: [Preview 1080x1920](https://dentsucreativestudio.github.io/canda-dooh/HTML/canda_02_antwerpen_v1_photo_session_HTML_1080x1920/index.html), [Preview 1344x756](https://dentsucreativestudio.github.io/canda-dooh/HTML/canda_02_antwerpen_v1_photo_session_HTML_1344x756/index.html)
* Pictures of previous day in random order on 5/12: [Preview 1080x1920](https://dentsucreativestudio.github.io/canda-dooh/HTML/canda_02_antwerpen_v2_day_after_HTML_1080x1920/index.html), [Preview 1344x756](https://dentsucreativestudio.github.io/canda-dooh/HTML/canda_02_antwerpen_v2_day_after_HTML_1344x756/index.html)

### Belle Ile:
* Live pictures on 10/12: [Preview](https://dentsucreativestudio.github.io/canda-dooh/HTML/canda_03_belle_ile_v1_photo_session_HTML_1080x1920/index.html)
* Pictures of previous days in random order on 11/12: [Preview](https://dentsucreativestudio.github.io/canda-dooh/HTML/canda_03_belle_ile_v2_day_after_HTML_1080x1920/index.html)

### Belle Etoile: (additional location)
* Live pictures on 11/12: [Preview](https://dentsucreativestudio.github.io/canda-dooh/HTML/canda_05_belle_etoile_v1_photo_session_HTML_1080x1920/index.html)
* Pictures of previous days in random order on 12/12: [Preview](https://dentsucreativestudio.github.io/canda-dooh/HTML/canda_05_belle_etoile_v2_day_after_HTML_1080x1920/index.html)

### Waasland:
* Live pictures on 17/12: [Preview](https://dentsucreativestudio.github.io/canda-dooh/HTML/canda_04_waasland_v1_photo_session_HTML_1080x1920/index.html)
* Pictures of previous days in random order on 18/12: [Preview](https://dentsucreativestudio.github.io/canda-dooh/HTML/canda_04_waasland_v2_day_after_HTML_1080x1920/index.html)
