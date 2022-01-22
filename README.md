# Virus-Envelope-Protien-detection count
Here is the application of Computer vision- Blob Detection methodology to detect and count the Envelope protiens of sample images of Human Coronavirus and mouse hepatitis virus (Image source- https://www.utmb.edu/virusimages/VI/coronaviruses and cdc)

In computer vision, blob detection methods are aimed at detecting regions in a digital image that differ in properties, such as brightness or color, compared to surrounding regions (Source-Wikipedia)
From a process perspective it involves morphological operations on the binary image to remove any noise and then the application of methodoligies like

1) Gaussians approach (LoG)
2) Difference of Gaussian (DoG)
3) Determinant of Hessian (DoH)

Original Image- Converted to Binary

![image](https://user-images.githubusercontent.com/98158660/150641680-02b7be62-1b23-49f6-9bda-3b530871cf70.png)

Morphological operations on the Binary image (Erosion & dilution)

![image](https://user-images.githubusercontent.com/98158660/150641732-7f694d82-efdd-4a50-af55-56b010c73656.png)

Envelope protiens (blobs in this case) detected using Laplacian of Gaussian approach

![image](https://user-images.githubusercontent.com/98158660/150641781-9cc031a0-d2f8-413e-a338-232146a86f67.png)
