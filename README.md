# image-color-palette-generator
This is an Image processing project to extract colors from any given image
I used the Image Object from PIL library to open the image
I then extracted the colors from the image in RGB format using the extcolors library alongside the frequency of each color
Then I used colormap to convert the RGB color codes to HEX code
I then proceeded to create a pandas dataframe using the hex codes and color frequency as columns
And finally I plotted a pie chart using matplotlib.pyplot, showing the colors and their percentage in the image
