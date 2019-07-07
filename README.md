# Semantic Image Segmentation on Android

This is a basic application to demonstrate the network presented 
in [\[1\]][1] *An Efficient Solution for Semantic Segmentation: ShuffleNet
V2 with Atrous Separable Convolutions*. To check out the network itself and the other
trained models please refer to the main repository: [sercant/mobile-segmentation][2].

There are already bundled Tensorflow-Lite models under app/assets folder. You can import
the project directly to Android studio, compile and run the application in your Android
phone.

If you find the code useful for your research, please consider citing us:

```tex
@InProceedings{turkmen2019efficient,
  author    = {Sercan T{\"u}rkmen and Janne Heikkil{\"a}},
  title     = {An Efficient Solution for Semantic Segmentation: {ShuffleNet} V2 with Atrous Separable Convolutions},
  booktitle = {Image Analysis},
  year      = {2019},
  editor    = {Michael Felsberg and Per-Erik Forss{\'e}n and Ida-Maria Sintorn and Jonas Unger},
  volume    = {11482},
  pages     = {41--53},
  address   = {Cham},
  publisher = {Springer International Publishing},
  doi       = {10.1007/978-3-030-20205-7_4},
  isbn      = {978-3-030-20205-7},
  url       = {http://dx.doi.org/10.1007/978-3-030-20205-7_4},
}
```

[1]: https://doi.org/10.1007/978-3-030-20205-7_4
[2]: https://github.com/sercant/mobile-segmentation
