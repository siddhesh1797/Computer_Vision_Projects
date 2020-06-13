This code can be used to generate photo-mosaic images, to use it you must have Python installed, along with the Pillow imaging library.

As well as an image to use for the photo-mosaic, you will need a large collection of different images to be used as tiles. The tile images can be of any shape or size (the code will automatically crop and resize them) but for good results you will need a lot of them - a few hundred at least. One convenient way of generating large numbers of tile images is to extract screenshots from video(Use provided Video2Images code for extracting frames)

Run the code from the command line:
```
python mosaic.py <image> <tiles directory>
```

For example:
```
python mosaic.py output.jpg /User/File/Images/
```
