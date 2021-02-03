---
title: "DPANet: Depth Potentiality-Aware Gated Attention Network for RGB-D Salient Object Detection"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Runmin Cong 
- Qianqian Xu
- Qingming Huang

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2020-11-03T00:00:00Z"
doi: "https://doi.org/10.1109/TIP.2020.3028289"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Image Processing*
publication_short: In *IEEE TIP*

abstract: 
There are two main issues in RGB-D salient object detection: (1) how to effectively integrate the complementarity from the cross-modal RGB-D data; (2) how to prevent the contamination effect from the unreliable depth map. In fact, these two problems are linked and intertwined, but the previous methods tend to focus only on the first problem and ignore the consideration of depth map quality, which may yield the model fall into the sub-optimal state. In this paper, we address these two issues in a holistic model synergistically, and propose a novel network named DPANet to explicitly model the potentiality of the depth map and effectively integrate the cross-modal complementarity. By introducing the depth potentiality perception, the network can perceive the potentiality of depth information in a learning-based manner, and guide the fusion process of two modal data to prevent the contamination occurred. The gated multi-modality attention module in the fusion process exploits the attention mechanism with a gate controller to capture long-range dependencies from a cross-modal perspective. Experimental results compared with 16 state-of-the-art methods on 8 datasets demonstrate the validity of the proposed approach both quantitatively and qualitatively.


# Summary. An optional shortened abstract.
summary: 

tags: [saliency detection, rgb-d]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9247470'
url_code: 'https://github.com/JosephChenHub/DPANet.git'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
#caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  caption: 'Image credit: [**Unsplash**](/media/shenzhen.jpg)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example

---

**Abstract**: There are two main issues in RGB-D salient object detection: 
(1) how to effectively integrate the complementarity from the cross-modal RGB-D data; 
(2) how to prevent the contamination effect from the unreliable depth map. 
In fact, these two problems are linked and intertwined, but the previous methods tend to focus only on the first problem and ignore the consideration of depth map quality, which may yield the model fall into the sub-optimal state. 
In this paper, we address these two issues in a holistic model synergistically, and propose a novel network named DPANet to explicitly model the potentiality of the depth map and effectively integrate the cross-modal complementarity.
By introducing the depth potentiality perception, the network can perceive the potentiality of depth information in a learning-based manner, and guide the fusion process of two modal data to prevent the contamination occurred. 
The gated multi-modality attention module in the fusion process exploits the attention mechanism with a gate controller to capture long-range dependencies from a cross-modal perspective. Experimental results compared with 16 state-of-the-art methods on 8 datasets demonstrate the validity of the proposed approach both quantitatively and qualitatively.

![main](TIP_main.png)

![vis](vis.png)

![gma](gma.png)
