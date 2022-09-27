---
title: 'Multi-View Scheduling of Onboard Live Video Analytics to Minimize Frame Processing Latency'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shengzhong Liu
  - Tianshi Wang
  - admin
  - Xinzhe Fu
  - Philip David
  - Maggie Wigness
  - Archan Misra
  - Tarek Abdelzaher


date: '2022-06-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-06-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of 42nd International Conference on Distributed Computing Systems*
publication_short: In *ICDCS 2022*

abstract: This paper presents a real-time multi-view scheduling framework for DNN-based live video analytics at the edge to minimize frame processing latency. The work is motivated by applications where a higher frame rate is important, not to miss actions of interest. Examples include defense, border security, and intruder detection applications where sensors (in this paper, cameras) are deployed to monitor key roads, chokepoints, or passageways to identify events of interest (and intervene in real-time). Supporting a higher frame rate entails lowering frame processing latency. We assume that multiple cameras are deployed with partially overlapping views. Each camera has access to limited onboard computing capacity. Many targets cross the field of view of these cameras (but the great majority do not require action). We take advantage of the spatial-temporal correlations among multi-camera video streams to perform target-to-camera assignment such that the maximum frame processing time across cameras is minimized. Specifically, we use a data-driven approach to identify objects seen by multiple cameras, and propose a batch-aware latency-balanced (BALB) scheduling algorithm to drive the object-to-camera assignment. We empirically evaluate the proposed system with a real-world surveillance dataset on a testbed consisting of multiple NVIDIA Jetson boards. The results show that our system substantially improves the video processing speed, attaining multiplicative speedups of 2.45⇥ to 6.85⇥, and consistently outperforms the competitive static region partitioning strategy.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
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
