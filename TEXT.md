# P1 Presentation
- What is a CNN
- How to use it in detection and enhancement of an object.
- Limitations of a CNN
- Probelm in CNN
  - visual transfer loss
  - Wide ranges is not available in underwater images
- Fixes
  - GAN + CNN + new Architecture
  - Encoder -> decoder Arch

CNN quantizes the values of pixels. when two pixels have the difference in intensity as zero, they will be considered as same pixel that makes the image shitty.
- Fix: skip conections

Dividing into
- Enhancing the quality of image using pixels
- Integerating resNet(ResGAN) into this arch which is a combination of GAN and CNN which is going to help us in better object enhancement.