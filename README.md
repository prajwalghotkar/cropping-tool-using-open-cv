🖼️ Image Cropping Tool using OpenCV https://github.com/prajwalghotkar/OpenCV
##### Project Description:
***This project is a simple and interactive image cropping tool built using Python and OpenCV. It allows users to manually select a region of interest (ROI) within an image using mouse input and displays the cropped section in a new window. The tool provides a straightforward way to crop images without using complex GUI libraries, making it lightweight and efficient for quick cropping tasks.***

##### Key Features:
- **Interactive Mouse Selection**: Click and drag to select the area to crop.
- **Live Feedback**: The selected rectangle is visualized during the selection process.
- **On-the-Fly Cropping**: Once the selection is made, the cropped image appears in a new window.
- **Simple Exit Mechanism**: Press 'x' to close the application.

##### Tech Stack:
- **Language**: Python
- **Libraries**:OpenCV (cv2),NumPy

##### How It Works:
- 1) The program loads an image using OpenCV.
- 2) Mouse callbacks track when and where the user clicks and drags on the image.
- 3) On mouse release, the selected rectangle is used to crop the region from the original image.
- 4) The cropped portion is then displayed in a new window.
- 5) The user can continue cropping or press 'x' to exit the tool.

##### Usage Instructions:

- 1) Place your image in the image/Airplane-2.png).
- 2) Run the Python script.
- 3) In the displayed window:
-- Click and drag to draw the crop area.
-- Release the mouse to see the cropped image.
-- Press x to exit the application.

##### Output:
- **Original Window: Shows the full image.**

<img width="1920" height="1026" alt="Screenshot 2025-07-31 011008" src="https://github.com/user-attachments/assets/7fd415a2-1bb6-4213-880e-17fbb46336f1" />
<img width="1920" height="1041" alt="Screenshot 2025-07-31 011019" src="https://github.com/user-attachments/assets/63ca3c05-5458-4808-83d3-123c9fffcd37" />

---
- **New Window: Displays the cropped region after selection.**

<img width="1920" height="1031" alt="Screenshot 2025-07-31 005528" src="https://github.com/user-attachments/assets/4b84e929-5de3-4b6e-af75-04666a34cc2d" />

##### Future Improvements:
- Add GUI options (e.g., Tkinter or PyQt) for better user experience.
- Save the cropped image directly to disk.
- Support multiple cropping and batch processing.


https://github.com/prajwalghotkar/OpenCV

