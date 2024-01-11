# Homographies and Image Stitching

## Homography-Based Planar Object Detection

This repository implements a system for localizing a planar textured object in an image using homography. The classical pipeline involves extracting local features, obtaining scale- and orientation-independent feature descriptors, matching features in the query image, and robustly estimating the homography matrix. The camera resection from the estimated homography is then utilized to seamlessly insert another image with the correct perspective into the original scene. The README provides insights into the implementation, discusses the results, and evaluates computational time based on different feature detectors, descriptors, and matching strategies.

### Results
- Sample images showcasing planar object detection.
- Computational time measurements for various configurations.

## Image Stitching for Panorama Creation

This section focuses on stitching five horizontally overlapping photographs into a single panoramic image. The process involves recovering transformation parameters between each pair of images, warping the images to align them, and creating an image mosaic. The README guides users through the implementation, discusses results obtained using various feature detectors, descriptors, and matching strategies, and provides insights into computational efficiency. The visual demonstration showcases the effectiveness of the image stitching process.

### Results
- Panoramic image created from the input set of five images.
- Comparative analysis of feature-based image stitching strategies.

## Wide Panorama with 7 Images

Expanding on the panorama creation, this part introduces the challenge of joining seven images to create a wide panorama without distortion near the edges. Instead of projecting the mosaic on a plane, alternative surfaces like a sphere or cylinder are explored to mitigate unwanted distortions. The README outlines the approach, discusses the choice of surfaces, and showcases the results. Users gain insights into handling larger image sets for panorama creation, enhancing their understanding of advanced image warping techniques.

### Results
- Wide panorama created from a set of seven images.
- Comparison of distortion effects using different projection surfaces.

