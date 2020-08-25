---
title: "FastORB-SLAM: a Fast ORB-SLAM Method with Coarse-to-Fine Descriptor Independent Keypoint Matching"
authors:
- Qiang Fu, Hongshan Yu, Xiaolong Wang, Zhengeng Yang, Hong Zhang, and Ajmal Mian
date: "2020"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020 08"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv"
# publication_short: ""

abstract: Indirect methods for visual SLAM are gaining popularity due to their robustness to varying environments. ORB-SLAM2 is a benchmark method in this domain, however, the computation of descriptors in ORB-SLAM2 is time-consuming and the descriptors cannot be reused unless a frame is selected as a keyframe. To overcome these problems, we present FastORB-SLAM which is light-weight and efficient as it tracks keypoints between adjacent frames without computing descriptors. To achieve this, a two-stage coarse-to-fine descriptor independent keypoint matching method is proposed based on sparse optical flow. In the first stage, we first predict initial keypoint correspondences via a uniform acceleration motion model and then robustly establish the correspondences via a pyramid-based sparse optical flow tracking method. In the second stage, we leverage motion smoothness and the epipolar constraint to refine the correspondences. In particular, our method computes descriptors only for keyframes. We test FastORB-SLAM with an RGBD camera on TUM and ICL-NUIM datasets and compare its accuracy and efficiency to nine existing RGBD SLAM methods. Qualitative and quantitative results show that our method achieves state-of-the-art performance in accuracy and is about twice as fast as the ORB-SLAM2.

# Summary. An optional shortened abstract.
summary: Indirect methods for visual SLAM are gaining popularity due to their robustness to varying environments. ORB-SLAM2 is a benchmark method in this domain, however, the computation of descriptors in ORB-SLAM2 is time-consuming and the descriptors cannot be reused unless a frame is selected as a keyframe. To overcome these problems, we present FastORB-SLAM which is light-weight and efficient as it tracks keypoints between adjacent frames without computing descriptors.

tags:
- Source Themes
featured: true

links:
url_pdf: https://arxiv.org/pdf/2008.09870.pdf
url_video: https://www.youtube.com/watch?v=bFWTT-kGEQ0

# - name: Custom Link
#  url: http://example.org
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: https://www.youtube.com/watch?v=bFWTT-kGEQ0


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: fastorbslam.png
  focal_point: ""
  preview_only: true

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


