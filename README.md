# Video Watermarking Using LSB

This project demonstrates invisible watermarking in videos using the Least Significant Bit (LSB) technique. The goal is to embed a watermark 
into video frames in a way that is imperceptible to viewers but recoverable when needed.
 THis includes :

- Frame extraction from input video
- using scene change detection using histogram difference method for key frame selection
- Canny edge detection along with otsu method for region selection
- Watermark embedding using the LSB technique
- Reconstruction of the video with embedded watermark
- Extraction of the watermark from watermarked video frames
- Visualization and comparison of original vs watermarked frames
