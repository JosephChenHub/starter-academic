---
title: "Deep Partial Rank Aggregation for Personalized Attributes"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Qianqian Xu
- Zhiyong Yang
- admin
- Yangbangyan Jiang
- Xiaochun Cao
- Yuan Yao
- Qingming Huang


# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In * Proceedings of the AAAI Conference on Artificial Intelligence*
publication_short: In *AAAI, 2021*



# Summary. An optional shortened abstract.
summary: 

tags: [recommendation, personalized attributes]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://github.com/qianqianxu010/AAAI21/blob/main/AAAI21-DeepPartialRank.pdf'
url_code: 'https://github.com/qianqianxu010/AAAI21'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 


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
In this paper, we study the problem of how to aggregate pair-
wise personalized attributes (PA) annotations (e.g., Shoes A
is more comfortable than B) from different annotators on the
crowdsourcing platforms, which is an emerging topic gaining
increasing attention in recent years. Given the crowdsourced
annotations, the majority of the traditional literature assumes
that all the pairs in the collected dataset are distinguishable.
However, this assumption is incompatible with how humans
perceive attributes since indistinguishable pairs are ubiqui-
tous for the annotators due to the limitation of human percep-
tion. To attack this problem, we propose a novel deep pre-
diction model that could simultaneously detect the indistin-
guishable pairs and aggregate ranking results for distinguish-
able pairs. First of all, we represent the pairwise annotations
as a multi-graph. Based on such data structure, we propose
an end-to-end partial ranking model which consists of a deep
backbone architecture and a probabilistic model that captures
the generative process of the partial rank annotations. Specif-
ically, to recognize the indistinguishable pairs, the probabilis-
tic model we proposed is equipped with an adaptive percep-
tion threshold, where indistinguishable pairs could be auto-
matically detected when the absolute value of the score dif-
ference is below the learned threshold. In our empirical stud-
ies, we perform a series of experiments on three real-world
datasets: LFW-10, Shoes, and Sun. The corresponding results
consistently show the superiority of our proposed model.


# ![main](main.png)

 <img src="main.png" />


