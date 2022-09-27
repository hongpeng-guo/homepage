---
title: 'BoFL: Bayesian Optimized Local Training Pace Control for Energy Efficient Federated Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Haotian Gu
  - Zhe Yang
  - Xiaoyang Wang
  - Eun Kung Lee
  - Nandhini Chandramoorthy
  - Tamar Eilam
  - Deming Chen
  - Klara Nahrstedt


date: '2022-07-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-07-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of ACM/IEEE 6th Symposium on Edge Computing*
publication_short: In *SEC'22*

abstract: Federated learning (FL) is a machine learning paradigm that enables a cluster of decentralized edge devices to collaboratively train a shared machine learning model without exposing users’ raw data. However, the intensive model training computation is energy- demanding and poses severe challenges to end devices’ battery life. In this paper, we present BoFL, a training pace controller deployed on the edge devices that actuates the hardware operational frequencies over multiple configurations to achieve energy-efficient federated learning. BoFL operates in an explore-then-exploit manner within limited rounds of FL tasks. BoFL explores the large hardware frequency space strategically with a tailor-designed Bayesian optimization algorithm. BoFL first find a set of good operational configurations within few task training rounds, and then exploits these configurations in the remaining rounds to achieve minimized energy consumption for model training. Experiments on multiple real-world edge devices with different FL tasks suggest that BoFL can reduce energy consumption of model training by around 26%, and achieve near-optimal energy efficiency.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/hongpeng-guo/BoFL'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://docs.google.com/presentation/d/1W--1i-k9emR_i1eJup0d3dsFi8On9be7sXAelYaXH5Y/edit?pli=1#slide=id.p'
url_source: ''
url_video: ''
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
