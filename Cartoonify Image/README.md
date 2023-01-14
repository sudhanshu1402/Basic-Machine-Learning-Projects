# Cartoonify Image
The project cartoonify image is a simple machine learing project that turns any image into a cartoon view image.
To convert an image to a cartoon, multiple transformations are done. Firstly, an image is converted to a Grayscale image. Yes, similar to the old day’s pictures.! Then, the Grayscale image is smoothened, and we try to extract the edges in the image. Finally, we form a color image and mask it with edges. This creates a beautiful cartoon image with edges and lightened color of the original image.

## Libraries Used
- CV2: Imported to use OpenCV for image processing
- easygui: Imported to open a file box. It allows us to select any file from our system.
- Numpy: Images are stored and processed as numbers. These are taken as arrays. We use NumPy to deal with arrays.
- Imageio: Used to read the file which is chosen by file box using a path.
- Matplotlib: This library is used for visualization and plotting. Thus, it is imported to form the plot of images.
- OS: For OS interaction. Here, to read the path and save images to that path.

## Input
![bros](https://user-images.githubusercontent.com/99204211/183352481-3b72fe53-556a-4e49-aef8-62599933ba53.jpg)

## Output
![image](https://user-images.githubusercontent.com/99204211/183352754-79aab67b-5873-4ec9-a407-e5ad5a66f6c8.png)
