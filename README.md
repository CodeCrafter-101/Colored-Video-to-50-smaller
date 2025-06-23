# Colored Video to 50% (smaller)

## 
- Colored Video to 50% (Smaller) is a Python utility that resizes a colored video to half of its original resolution (both width and height). This is particularly useful for reducing file size, speeding up video processing, and optimizing media for web or mobile platforms, all while preserving the visual content.

## Requirements
- Make sure the following are installed:
- Python 3.x
- Libraries
  - `opencv-python` (`cv2`)
  - `os` (built-in)
- Install the required package:
  - ````
    pip install opencv-python
    ````

## Project Structure
 ![image](https://github.com/user-attachments/assets/c731d7bd-4af7-4359-81dc-d307496088f3)

## How to Use
1. Add your colored video to the input/ folder.
2. Run the script:
   -  ````
      python main.py
      ````
3. The script will:
   - Open the video
   - Resize each frame to 50% of the original width and height
   - Save the new video to the `output/` folder
