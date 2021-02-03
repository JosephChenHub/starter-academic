---
title: "Global Context-Aware Progressive Aggregation Network for Salient Object Detection"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Qianqian Xu
- Runmin Cong 
- Qingming Huang

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-03-02T00:00:00Z"
doi: "https://doi.org/10.1609/aaai.v34i07.6633"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-03-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In * Proceedings of the AAAI Conference on Artificial Intelligence*
publication_short: In *AAAI, 2020*



# Summary. An optional shortened abstract.
summary: 

tags: [saliency detection]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ojs.aaai.org/index.php/AAAI/article/download/6633/6487'
url_code: 'https://github.com/JosephChenHub/GCPANet'
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

**Abstract**: 
Deep convolutional neural networks have achieved competitive performance in salient object detection, in which how to learn effective and comprehensive features plays a critical role. Most of the previous works mainly adopted multiple-level feature integration yet ignored the gap between different features. Besides, there also exists a dilution process of high-level features as they passed on the top-down pathway. To remedy these issues, we propose a novel network named GCPANet to
effectively integrate low-level appearance features, high-level semantic features, and global context features through some progressive context-aware Feature Interweaved Aggregation (FIA) modules and generate the saliency map in a supervised way. Moreover, a Head Attention (HA) module is used to reduce information redundancy and enhance the top layers features by leveraging the spatial and channel-wise attention, and the Self Refinement (SR) module is utilized to further refine
and heighten the input features. Furthermore, we design the Global Context Flow (GCF) module to generate the global context information at different stages, which aims to learn the relationship among different salient regions and alleviate the dilution effect of high-level features. Experimental results on six benchmark datasets demonstrate that the proposed approach outperforms the state-of-the-art methods both quantitatively and qualitatively.


![main](main.png)

![vis](vis.png)

