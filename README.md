# Document-Scanner-using-Captured-Images
This is a mobile document scanner using OpenCV.

This project involves three basic steps.
1. Detect edges.
2. Use the edges to find the contour (outline) of the paper in the scanned image.
3. Apply a perspective transform to obtain the top-down view of the document.
4. Perform adaptive thresholding to obtain black-and-white document.

Assumptions:
1. The image is focused on the document.
2. The document is rectangular and has four distinct edges.

Recommendation:
1. Apply OCR to the document in the imgae.
2. Be able to download an editable PDF file.
3. Develop a fully pledged mobile app.
