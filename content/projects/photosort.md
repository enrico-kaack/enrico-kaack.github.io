+++
categories = ["Project"]
date = "2024-09-24"
description = "A web-based tool designed to help you quickly sort through old pictures directly in your browser."

title = "Photo Sort"
slug = "photo-sort"
type = "post"
series = ["Projects"]
[ author ]
  name = "Enrico Kaack"
+++

## Photo Sort

**Photo Sort** is a web-based tool designed to help you quickly sort through old pictures directly in your browser, keeping the process private and local.

![Review page screenshot. Showing the image and exif information and a image gallery with marked images as accepted and rejected.](/projects/photosort/review.png)


### Background

The idea for Photo Sort came from a common problem: I had a lot of old pictures lying around on various hard drives. Before putting them into a more organized photo solution, I realized I needed a better way to sort them. System tools made this process cumbersome, and sorting images one by one manually was tedious.

As a first solution, I turned to ChatGPT, which helped me create a Python script. This script displayed each image and let me choose to either accept or reject it. While this worked, I wanted a smoother and more interactive experience. That’s when I decided to build a web-based version with a better user interface—thus, Photo Sort was born.

### Design Goals

- **Privacy First**: All image processing should happen locally, ensuring that no pictures are ever uploaded to a server.
- **Ease of Use**: The user interface should be simple and intuitive, allowing users to sort through images quickly without a steep learning curve.
- **Speed and Performance**: Sorting and copying images should be fast and responsive, even for large batches of photos.

### Features

- **Folder-based Sorting**: Easily select a folder of images to sort through.
- **Accept or Reject Images**: Review each picture and choose whether to keep it or discard it.
- **Local File Handling**: The browser’s File System API allows you to load and save files directly from your device.
- **Deduplication**: Already sorted images are saved to avoid sorting them again in future sessions.
- **Output Folder Selection**: Choose a destination folder for saving all accepted images.
- **No Uploads, Full Privacy**: Images never leave your device—everything happens locally in the browser.
