# Keyence_LJXSample_OpenCV
OpenCV sample for Keyence LJXA controller
The sample code is extend from the official sample code Sample_ImageAcquisition in LJ-XA Navigator

All image process function are based on OpenCVSharp4:
1. Get height data and turn into rainbow image.
2. Get Luminance data.
3. Mix height and gray data for better visualization.
4. Roi output height max,min,avg
5. Position check with height to binary image.
6. Combin image
