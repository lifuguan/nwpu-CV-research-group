---
title: VALSE Paper Review (Presented by Dr. Le Yang)

event: VALSE Conference
event_url: https://www.bilibili.com/video/BV1aT411g7gZ/

location: Virtual


summary: Colar：Effective and Efficient Online Action Detection by Consulting Exemplars
abstract: 时序动作定位任务致力于从漫长的视频中发现有意义的动作片段，并标注起止时间和动作类别。在实际应用中，算法需要在线地处理视频流并及时准确地检测出正在发生的动作，这将传统的时序动作定位任务发展为新兴的在线动作检测任务。已有方法通常在一个视频片段内部精细地建模时序依赖，从而进行在线动作检测。这种学习范式会导致两个问题：(1) 即使两个动作实例属于同一类别，他们可能由于来自不同视频而无法进行信息交互。(2) 训练过程希望为每类动作学习特定的一种表征，但同类动作的不同阶段通常具有较大的差异性。为应对上述两点挑战，本文提出样例查询机制，在动态样例分支中，通过比较时序样例和当前帧的相似性，以一种简单高效的方式建模时序信息；在静态样例分支中，通过比较类别样例和当前帧的相似性，能进行跨视频信息交互并为每类动作学习多样性的表征。相比已有方法，所提方法效率更快，检测精度更高，能为后续在线动作检测研究提供简单有效的基准模型。

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-07-10T18:00:00Z'
date_end: '2022-07-10T20:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2022-07-10T20:00:00Z'

authors: ['杨乐']
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Image**](featured.jpg)'
  focal_point: Right

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
---
