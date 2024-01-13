Image Comparison Program

This Python program is designed to compare an original image with itself to establish the values of a "perfect" image. Subsequently, these perfect image values are used for comparison with four altered copies of the original image. The comparisons involve mean square root values, structural similarity values, and peak signal-noise ratio.

Description:
Original Image:

The image of Lena is read into "imA" from the file 'lena_g.bmp'.
Several copies of the original image are created and converted to grayscale.
Noise Generation:

Two arrays are created for generating noise in the image.
Gaussian noise is created with a specified variance.
Uniform noise is generated randomly between two values.
Salt and pepper noise is added to a copy of the original image.
Image Alterations:

Four copies of the original image undergo different alterations:
Gaussian noise is added to one copy ("imB").
Uniform noise is added to another copy ("imC").
Salt and pepper noise is added to a third copy ("imD").
The original image is transformed using contrast stretching ("imE").
Comparison Methods:

Three comparison methods are implemented:
Mean Square Error (MSE)
Peak Signal-to-Noise Ratio (PSNR)
Structural Similarity Index (SSIM)
Results Visualization:

The program displays the original image and each altered copy alongside their respective comparison values (MSE, PSNR, SSIM).
Usage:
Ensure that the image file 'lena_g.bmp' is present in the '/content/sample_data/' directory.
Run the program, and it will display the original and altered images with their comparison metrics.
