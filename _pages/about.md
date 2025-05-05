---
permalink: /
title: "Introduction"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am now a master researcher at [Harbin Engineering University, China](https://english.hrbeu.edu.cn/).My research interest include Fisheries Acoustics, Machine Learning and Global Navigation Satellite System and Acoustic ranging(GNSS-A).I am also a member of [AFAS](https://www.afas-acoustic.org/).Now my research focus on underwater target tracking based on machine learning and kalman filter.

Education
======
**M.Eng. in Information and Communication Engineering, 2025(Supervised by [Wei Ge](https://homepage.hrbeu.edu.cn/web/gewei))**

Harbin Engineering University, Harbin, Heilongjiang Province, China

**B.A in Marine Technology, 2022(Supervised by [Yong Tang](https://hyxy.shou.edu.cn/2024/1113/c7720a335682/page.htm))**

Dalian Ocean University, Dalian, Liaoning Province, China

Research Reference 
======
1. [Watanabe S, Ishikawa T, Yokota Y, et al. GARPOS: Analysis software for the GNSS‐A seafloor positioning with simultaneous estimation of sound speed structure[J]. Frontiers in Earth Science, 2020, 8: 597532.](https://www.frontiersin.org/journals/earth-science/articles/10.3389/feart.2020.597532/full)
2. [Watanabe S, Ishikawa T, Nakamura Y, et al. Full-Bayes GNSS-A solutions for precise seafloor positioning with single uniform sound speed gradient layer assumption[J]. Journal of Geodesy, 2023, 97(10): 89.](https://link.springer.com/article/10.1007/s00190-023-01774-6)
3. [Yokota Y, Ishikawa T, Watanabe S. Gradient field of undersea sound speed structure extracted from the GNSS-A oceanography[J]. Marine Geophysical Research, 2019, 40(4): 493-504.](https://link.springer.com/article/10.1007/s11001-018-9362-7)
4. [Yokota Y, Watanabe S, Ishikawa T, et al. Temporal Change of km‐Scale Underwater Sound Speed Structure and GNSS‐A Positioning Accuracy[J]. Earth and Space Science, 2022, 9(12): e2022EA002224.](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2022EA002224)
5. [Tomita F. Enhanced GNSS-acoustic positioning method implementing with constraints on underwater sound speed structure[J]. Earth, Planets and Space, 2024, 76(1): 178.](https://link.springer.com/article/10.1186/s40623-024-02120-6)
6. [Ikuta R, Tadokoro K, Ando M, et al. A new GPS‐acoustic method for measuring ocean floor crustal deformation: Application to the Nankai Trough[J]. Journal of Geophysical Research: Solid Earth, 2008, 113(B2).](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2006JB004875)
7. [Urmy S S, De Robertis A, Bassett C. A Bayesian inverse approach to identify and quantify organisms from fisheries acoustic data[J]. ICES Journal of Marine Science, 2024, 81(7): 1461-1477.](https://academic.oup.com/icesjms/article/81/7/1461/7220877)
8. [Cotter E, Bassett C, Lavery A. Classification of broadband target spectra in the mesopelagic using physics-informed machine learning[J]. The Journal of the Acoustical Society of America, 2021, 149(6): 3889-3901.](https://pubs.aip.org/asa/jasa/article/149/6/3889/1059295)
9. [Dunn M, McGowan-Yallop C, Pedersen G, et al. Model-informed classification of broadband acoustic backscatter from zooplankton in an in situ mesocosm[J]. ICES Journal of Marine Science, 2024, 81(7): 1371-1384.](https://academic.oup.com/icesjms/article/81/7/1371/7460294)
10. [Stanton T K, Lee W J, Baik K. Echo statistics associated with discrete scatterers: A tutorial on physics-based methods[J]. The Journal of the Acoustical Society of America, 2018, 144(6): 3124-3171.](https://pubs.aip.org/asa/jasa/article/144/6/3124/993369)
11. [Lee W J, Stanton T K. Statistics of broadband echoes: Application to acoustic estimates of numerical density of fish[J]. IEEE Journal of Oceanic Engineering, 2015, 41(3): 709-723.](https://ieeexplore.ieee.org/abstract/document/7342987/)
12. [Loranger S, Jech M J, Lavery A C. Broadband acoustic quantification of mixed biological aggregations at the New England shelf break[J]. The Journal of the Acoustical Society of America, 2022, 152(4): 2319-2335.](https://pubs.aip.org/asa/jasa/article/152/4/2319/2839494)

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
