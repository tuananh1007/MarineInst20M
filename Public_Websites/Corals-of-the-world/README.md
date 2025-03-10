# Corals-of-the-world

Please download the original images from the official [Corals-of-the-world](http://www.coralsoftheworld.org/page/home/) based on the provided `urls.txt` file.

After downloading the coral reef images, please run the following codes to do some post-processing to get the same images as our training images.

```
python processing_corals_of_the_world.py
```

We do not have the copyright of these images. We only provide the image URL for you to download the images on your own.

The annotations of the images are included in the `corals-of-the-world.zip`. Please note that we do not provide the mask annotations for all the coral reef images.

## Citation

If you find the data are useful in your research, please consider citing:

```bibtex
@misc{corals,
  title={Corals of the World},
  author={Turak E. and DeVantier L.M},
  howpublished={\url{http://coralsoftheworld.org/v0.01(Beta)}},
  year={2016}
}
@article{ziqiang2024marineinst,
  title={MarineInst: A Foundation Model for Marine Image Analysis with Instance Visual Description},
  author={Ziqiang Zheng, Yiwe Chen, Huimin Zeng, Tuan-Anh Vu, Binh-Son Hua, Sai-Kit Yeung},
  journal={European Conference on Computer Vision (ECCV)},
  year={2024},
  publisher={Springer}
}
```
