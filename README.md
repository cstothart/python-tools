python-tools
=============

A collection of Python tools.

#ImageTools#

### Tools ###

A collection of simple image manipulation tools:

* Automatic Image Cropping -- Automatically crops all of the images in a given folder.
```
![alt text](https://raw.githubusercontent.com/cstothart/python-tools/master/C04.bmp "Original Image")
![alt text](https://raw.githubusercontent.com/cstothart/python-tools/master/C04_cropped.bmp "Cropped Image")
```

* Image Resizing -- Proportionally resizes all of the images in a given folder.
```
![alt text](https://raw.githubusercontent.com/cstothart/python-tools/master/C04.bmp "Original Image")
![alt text](https://raw.githubusercontent.com/cstothart/python-tools/master/C04_resized.bmp "Resized Image")
```

### Usage Examples (Windows) ###

###### Automatic Cropping ######

Crop all of the images in folder_with_images and place the cropped images in the same folder.
```
python ImageTools.py c folder_with_images
```

Crop all of the images in folder_with_images and place the cropped images in folder_for_modified_images.
```
python ImageTools.py c folder_with_images --outDir folder_for_modified_images
```

###### Proportional Resizing ######

Make all of the images in folder_with_images 300x300 pixels and place the resized images in the same folder.
```
python ImageTools.py s folder_with_images --newWidth 300
```

Make all of the images in folder_with_images 300x300 pixels and place the resized images in folder_for_modified_images.
```
python ImageTools.py s folder_with_images --outDir folder_for_modified_images --newWidth 300
```