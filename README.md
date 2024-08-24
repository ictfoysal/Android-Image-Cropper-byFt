# Android Image Cropper

🚩 **The Project is currently maintained** 🚩  
Please use [CanHub's fork](https://github.com/ictfoysal/Android-Image-Cropper-byFt)!  
Thank you everybody for using the library. It was very fun to create and a privilege to help you build awesome apps.  
The same way I took an unmaintained initial implementation from edmodo, I'm happy to see CanHub taking it now.  
Good luck and happy coding! :octocat:

[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-Android--Image--Cropper-brightgreen.svg?style=flat)](https://android-arsenal.com/details/1/1722)

---

## Overview

Powerful (Zoom, Rotation, Multi-Source), customizable (Shape, Limits, Style), optimized (Async, Sampling, Matrix), and simple image cropping library for Android.

![Crop](https://raw.githubusercontent.com/ArthurHub/Android-Image-Cropper/master/art/demo.gif)

## Features

- **Built-in CropImageActivity**: A ready-to-use activity for cropping images.
- **Image Sources**: Set the cropping image as a Bitmap, Resource, or Android URI (Gallery, Camera, Dropbox, etc.).
- **Image Manipulation**: Support for image rotation and flipping during cropping.
- **Auto Zoom**: Automatically zoom in/out to the relevant cropping area.
- **Auto Rotate**: Automatically rotate the bitmap based on image Exif data.
- **Image Size Limits**: Set the minimum and maximum limits for the result image in pixels.
- **Initial Crop Window**: Set the initial size and location of the crop window.
- **Image Resizing**: Request a specific size for the cropped image.
- **Bitmap Memory Optimization**: Prevents OutOfMemory (OOM) errors by optimizing bitmap memory usage.
- **API Level Support**: Compatible with API Level 14 and above.

## Customizations

- **Cropping Window Shape**: Choose between Rectangular or Oval shapes (cube/circle by fixing aspect ratio).
- **Aspect Ratio**: Options for Free, 1:1, 4:3, 16:9, or Custom aspect ratios.
- **Guidelines Appearance**: Control guidelines appearance: Off, Always On, or Show on Touch.
- **Cropping Window Style**: Customize the border line, border corner, and guidelines thickness and color.
- **Background Color**: Set a custom background color for the cropping area.
- **And More**: Additional customization options to tailor the cropping experience to your needs.

## Usage

For a working implementation, please have a look at the [Sample Project](https://github.com/ArthurHub/Android-Image-Cropper/tree/master/sample).

See the [GitHub yt](https://www.youtube.com/@IctFoysal) for more info.

### Include the Library

Add the following dependency to your `build.gradle` file:

```groovy
dependencies {
    implementation ("com.github.ictfoysal:Android-Image-Cropper-byFt:2.9")
}

