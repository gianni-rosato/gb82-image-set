# GB82 Image Dataset

The GB82 image dataset is a **public domain image dataset for developing image compression algorithms.**

Included in this repo is also the GB82-SC dataset consisting of screen content images. It focuses on text and graphics, including samples from Linux (GNOME), macOS, iOS, Android, & Windows. You can find these images in the `sc-*` directories.

## Purpose

There are many datasets available that aim to assist in measuring image compression performance. The GB82 image dataset is designed to assist multimedia encoder developers in producing efficient image compression algorithms well-equipped for challenging content.

Photographic content contains a wide array of compression challenges: Fine details in important faces, low-contrast sky gradients with sparse clouds, digital noise, grains of sand on the beach, and more.

This dataset aims to be:
- **Representative of broad photographic content**
- **Challenging**: Optimizing for weak error metrics like PSNR should not yield visually compelling results on most images
- **Flexible**: It should be easy to produce a subset of this dataset that allows one to focus on a specific class of artifacting
- **Productive**: A smaller dataset means faster iteration and subsequent improvement

It leans toward photographic images in order to present realistic challenges that an encoder might encounter in a production use case.

## Details

The dataset features 25 different images, provided as either a total of 6.8MB of lossless JPEG-XL images or 9.6MB of lossless PNG images. All images are:
- 576x576
- 8-bit RGB
- D65 white point
- RGB primaries
- sRGB transfer function

The images in the dataset can be categorized as:
- 3 portraits (2 human, 1 dog)
- 6 landscapes
- 8 closeups of inanimate objects or scenes
- 4 low-light shots
- 3 realistically rendered graphics shots
- 1 non-photographic image

## License

All images are CC0. See the [LICENSE](LICENSE) for more information.
