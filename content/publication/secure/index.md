---
title: 'Secure Broadcast Protocol for Unmanned Aerial Vehicle Swarms'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tianyuan Liu
  - King-Shan Lui
  - Claudiu Danilov
  - Klara Nahrstedt


date: '2020-09-30T00:00:00Z'
doi: '10.1109/ICCCN49398.2020.9209739'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-09-30T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of 29th International Conference on Computer Communications and Networks*
publication_short: In *ICCCN 2020*

abstract: The technology advancement has made Unmanned Aerial Vehicle (UAV) swarm a promising method to achieve complicated missions that a single UAV cannot support. Leader-followers formation is a widely used swarm management scenario where a leader drone frequently broadcasts controlling messages to all follower drones to achieve collaboratively a common mission. However, managing such a UAV swarm, especially when the member drones dynamically join and leave the swarm, introduces significant security challenges and performance overhead.In this work, we propose a Swarm Broadcast Protocol (SBP) to facilitate the security protection of leader-followers formation based UAV swarms. SBP contains a security key management scheme that manages a broadcast key among the swarm for leader to broadcast encrypted messages to followers. When swarm membership changes, the broadcast key will be updated and synchronized among the swarm to maintain both backward and forward secrecy. The overhead of SBP is small that only constant computational overhead is needed for both swarm leader and followers to achieve key synchronization when a new drone joins regardless of the current swarm size. This feature would highly reduce the overhead when there are many individual drone joining events. Through experiments on network emulator, we show that SBP achieves lowest bandwidth overhead and CPU utilization to handle multiple swarm membership changing events, comparing with two public-key-based swarm management protocol baselines.

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
