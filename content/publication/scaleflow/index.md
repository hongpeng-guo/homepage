---
title: "ScaleFlow: Efficient Deep Vision Pipeline with Closed-Loop Scale-Adaptive Inference"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yuyang Leng
  - Renyuan Liu
  - admin
  - Songqing Chen
  - Shuochao Yao

date: "2023-06-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of 31st ACM International Conference on Multimedia*
publication_short: In *ACM MM 2023*

abstract: Deep visual data processing is underpinning many life-changing applications, such as auto-driving and smart cities. Improving the accuracy while minimizing their inference time under constrained resources has been the primary pursuit for their practical adoptions. Existing research thus has been devoted to either narrowing down the area of interest for the detection or miniaturizing the deep learning model for faster inference time. However, the former may risk missing/delaying small but important object detection, potentially leading to disastrous consequences (e.g., car accidents), while the latter often compromises the accuracy without fully utilizing intrinsic semantic information. To overcome these limitations, in this work, we propose ScaleFlow, a closed-loop scale-adaptive inference that can reduce model inference time by progressively processing vision data with increasing resolution but decreasing spatial size, achieving speedup without compromising accuracy. For this purpose, ScaleFlow refactors existing neural networks to be scale-equivariant on multiresolution data with the assistance of wavelet theory, providing predictable feature patterns on different data resolutions. Comprehensive experiments have been conducted to evaluate ScaleFlow. The results show that ScaleFlow can support anytime inference, consistently provide 1.5× to 2.2× speed up, and save around 25% ∼ 45% energy consumption with < 1% accuracy loss on four embedded and edge platforms.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ""
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
