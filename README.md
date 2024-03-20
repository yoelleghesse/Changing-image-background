This project loads a foreground image (with a green screen background) and a background image. It identifies pixels in the foreground image that match a specific color (green) and replaces them with pixels from the corresponding positions in the background image. The resulting image is saved as output.

Install OpenCV:

``pip install opencv-python``

Place the foreground image (with green screen background) and the background image in the project folder. Ensure the filenames match those specified in the script.

Run the script:

``python background_replacement.py``

The composed image will be saved as output.jpeg in the project folder.
