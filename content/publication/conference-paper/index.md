---
title: "Rapid Tactile Transfer Framework for Contact-Rich Manipulation Tasks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Xuanbing Peng
  - Jiayu Zhou
  - Zhuoran Sun
  - Xiaogang Xiong
  - Yunjiang Lou

# Author notes (optional)
# author_notes:
#   - "Equal contribution"
#   - "Equal contribution"

date: '2024-10-19T00:00:00Z'
doi: '10.1109/IROS58592.2024.10801764'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-25T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/RSJ International Conference on Intelligent Robots and Systems*
publication_short: In *IROS*

abstract: An increasing number of robotic manipulation tasks now use optical tactile sensors to provide tactile feedback, making tactile servo control a crucial aspect of robotic operations. This paper presents a rapid tactile transfer framework (RTTF) that achieves optical-tactile image sim2real transfer and robust tactile servo control using limited paired data. The sim2real aspect of RTTF employs a semi-supervised approach, beginning with pretraining the latent space representations of tactile images and subsequently mapping different tactile image domains to a shared latent space within a simulated tactile image domain. This latent space, combined with the proprioceptive information of the robotic arm, is then integrated into a privileged learning framework for policy training, which results in a deployable tactile control policy. Our results demonstrate the robustness of the proposed framework in achieving task objectives across different tactile sensors with varying physical parameters. Furthermore, manipulators equipped with tactile sensors, allow for rapid training and deployment for diverse contact-rich tasks, including object pushing and surface following.

# Summary. An optional shortened abstract.
summary: This paper introduces a rapid tactile transfer framework (RTTF) that uses semi-supervised learning to achieve robust tactile servo control and sim2real transfer for robotic manipulation tasks with limited data.

tags:
  - Robotic Manipulation

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/10801764'
url_code: 'https://github.com/NathanWu7/TLSM'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/UkUYNzcmwyk'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
