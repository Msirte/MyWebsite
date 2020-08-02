+++
# Date this page was created.
date = 2020-05-20T00:00:00

# Project title.
title = "Smart Glasses for Face Recognition"
font_size="12"

# Project summary to display on homepage.
summary = "Build face recognition glasses for fun."

weight = 2

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["deep-learning", "personal", "electronics"]
categories = []

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = "" # //bit.ly/rlel-github-meetup

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = []

# Does the project detail page use math formatting?
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
  
  # Show image only in page previews?
  preview_only = true

+++
<h8 style="text-align: justify;">

For some unknown reasons, I have been troubled by face blindness. It is difficult for me to distinguish faces, even from classmates who have lived together for many years. This has caused a lot of inconvenience to my life. Although I can distinguish individuals by sound, scene, and clothing, these will fail in some cases, especially when I watch a movie. After enduring long-term confusion, I decided to use what I learned to make face recognition glasses. The glasses consist of a camera, nanopi, LCD screen, battery and some optical components. The face recognition algorithm uses a neural network based on MTCNN and is implemented in C++, which relies on the ncnn library from tencent. At present I have completed the joint debugging of the algorithm and the display module [Fig. 1]. The 3D printed housing, battery and optical design is in progress. 

<figure>
 <img src="fig1.png" alt="a" width="600px" height="600px"/>
  <figcaption>
      <h10>Fig. 1. Joint debugging.</h10>
  </figcaption>
</figure>

This is not a very mature solution because of its weight and power consumption. I hope to use 5G technology to migrate algorithms to the cloud server in the future, which can release the front-end load. Although the glasses only have face recognition function, similar applications can be implanted, which provides a good idea for future wearable devices. I believe that with the advent of the 5G era, wearable devices, such as smart glasses, must have a broad market.

This is still an onging project and further work need to be done. This is my personal project, just for fun.

Code: <https://github.com/Msirte/face-galsses>

____________________________
References:
* <https://github.com/yiji-gr/face_recognize>
