---
title: "NDNet: Narrow While Deep Network for Real-Time Semantic Segmentation"
authors:
- Zhengeng Yang, Qiang Fu, Hongshan Yu, Wei Sun, Wenyan Jia, Mingui Sun, Zhi-Hong Mao
date: "2020-12-1"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-08"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Trans on ITS"
# publication_short: ""

abstract: The rapid development of autonomous driving in recent years presents many challenges for scene understanding. As an essential step towards scene understanding, semantic segmentation has received increased attention in the past few years. Although deep learning based approaches have achieved great success in improving the segmentation accuracy, most of them suffer from an inefficiency problem and can hardly be applied to real-time applications. In this paper, we analyze the computational cost of Convolutional Neural Network (CNN) and find that the inefficiency of CNNs is mainly caused by their wide structure rather than deep structure. In addition, the success of pruning based model compression methods proves that there are many redundant channels in CNNs. Thus, we design a narrow while deep backbone network to improve the efficiency of semantic segmentation. By casting our network to fully convolutional network (FCN32) segmentation architecture, the basic structure of most segmentation methods, we achieve 61.5% mIoU on Cityscapes validation dataset with only 4.2G floating-point operations (FLOPs) on 1024x2048 inputs, which already outperforms one of the earliest real-time deep learning based segmentation methods: ENet (58.3% mIoU, 3.8G FLOPs on 640x360 inputs). By further refining the output resolution of our network to the 1/8 of the input resolution with a simple encoder-decoder structure, we achieve 65.3% mIoU on Cityscapes test set with 14.0G FLOPs and 39.9 frames per second (FPS) on Titan X card. We have made our model publicly available at https://github.com/zgyang-hnu/NDNet.

# Summary. An optional shortened abstract.
# summary: In this paper we present FastORB-SLAM which is light-weight and efficient as it tracks keypoints between adjacent frames without computing descriptors.

tags:
 - Source Themes
featured: true

links:
url_pdf: https://ieeexplore.ieee.org/abstract/document/9078852
# url_video: https://www.youtube.com/watch?v=bFWTT-kGEQ0
# - name: Custom Link
#  url: http://example.org
# url_code: https://github.com/zgyang-hnu/NDNet
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: https://www.youtube.com/watch?v=bFWTT-kGEQ0


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# {{< figure src="fastorbslam.png" title="A caption" >}}

image: 
  placement: 1
  caption: "Photo by [Academic](https://sourcethemes.com/academic/)"
  focal_point: "Center"
  preview_only: true
  alt_text: An optional description of the image for screen readers.
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  # focal_point: ""
  # preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---


