# Homographies and Image Stitching

## Homography-Based Planar Object Detection

This exercise implements a system for localizing a planar textured object in an image. The camera resection from the estimated homography is then utilized to seamlessly insert another image with the correct perspective into the original scene.

### Results
- Sample images showcasing planar object detection.
- Computational time measurements for various configurations.

## Image Stitching for Panorama Creation

This section focuses on stitching five horizontally overlapping photographs into a single panoramic image. The process involves recovering transformation parameters between each pair of images, warping the images to align them, and creating an image mosaic.

### Input
![ex_2_0](https://github.com/javipzv/homographies-and-image-stitching/assets/90279135/169c50a1-def1-4d6a-9eae-c35e80b530f4)

### Output
<p align="center">
  <img src="https://github.com/javipzv/homographies-and-image-stitching/assets/90279135/2633c3e1-1360-471f-a93f-4c05b95b885d" width="900" height="600" alt="Descripción de la imagen">
</p>

## Wide Panorama with 7 Images

Expanding on the panorama creation, this part introduces the challenge of joining seven images to create a wide panorama without distortion near the edges. Instead of projecting the mosaic on a plane, alternative surfaces like a sphere or cylinder are explored to mitigate unwanted distortions.

### Input
![ex3_0](https://github.com/javipzv/homographies-and-image-stitching/assets/90279135/3629af3c-6144-49ac-80cb-ec97477e2414)

### Output
![ex3](https://github.com/javipzv/homographies-and-image-stitching/assets/90279135/7129ca58-8c53-4202-90a4-aa611387bcb9)


