# Autoencoder

This project demonstrates the training of an autoencoder using a modest dataset of AI-generated images. Unlike typical large-scale autoencoder projects that leverage massive datasets and high-end GPUs, our approach is both resource-efficient and accessible.

#Dataset

Number of Images: 3,000

Image Size: Approximately 200 KB each

Total Dataset Size: Around 350 MB

Data Source: AI-generated images, optimized for lower storage requirements

#Training Details

Hardware: CPU-based training (no GPU)

Training Duration: Approximately 8 to 10 hours

Epochs: 40

Hardware Constraints: Conducted on a personal laptop to ensure accessibility

#Results

Test Loss (MSE): 0.0027 — Indicative of high-quality reconstructions.

Mean PSNR: 26.63 dB — A good measure of reconstruction fidelity.

Mean SSIM: 0.7905 — Demonstrates strong structural similarity with the original images.

#Comparison with Large-Scale Projects

While many large-scale autoencoder projects employ extensive datasets (often several gigabytes per image) and high-end GPUs, our project emphasizes efficiency and accessibility. Despite the smaller dataset and the lack of GPU acceleration, the autoencoder still achieved impressive results, proving that high-quality image reconstruction is possible even with limited resources.

#Conclusion

This project showcases that it’s possible to train effective autoencoders without massive datasets or powerful hardware. By leveraging AI-generated images and optimizing for efficiency, we can achieve impressive results with accessible resources.
