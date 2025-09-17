---
permalink: /
title: "Xinchen Ma"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome! 

I am a Ph.D. Candidate in Finance at the London School of Economics and Political Science. I am on the 2025-2026 job market. My research interests are **Corporate Finance**, **Data Economy**, **FinTech**, and **Banking**.

Email: x.ma25@lse.ac.uk

<!-- [Curriculum Vitae](https://pages.github.com/) -->

------

Working Papers
======
### Open Banking and Fintech Innovation Adoption: Evidence from Mobile Apps (Job Market Paper)

**Abstract:** This paper examines the impact of open banking adoption on competition and innovation in digital financial services. I construct a novel dataset by decompiling historical Android app source code to identify open banking API integrations among finance apps in the UK and EU. Linking this with monthly app performance data, I find that adoption significantly increases downloads, user activity, and revenue. Exploiting cross-country variation in authorization status within the same app, I provide causal evidence that access to consumer banking data drives these gains. Benefits are amplified during periods of heightened demand: apps with open banking performed better during the COVID-19 shock, particularly in lending, investment, and among startup fintechs. On the supply side, incumbent banks most exposed to open banking—especially in lending—face the strongest pressure, but respond by raising fee intensity and asset yields. Thus, banks are not only hurt but also adapt strategically. Overall, open banking fosters innovation while reshaping competition in the mobile finance ecosystem.

- **Presented at:** AFA 2026 PhD Student Poster (scheduled), *Trans-Atlantic Doctoral Conference 2025*, *HEC Paris Finance PhD Workshop 2025*, *LSE PhD Workshop*
<br><br>
### The Supply and Demand for Data Privacy: Evidence from Mobile Apps 
with **Huan Tang** and **Bo Bian**

**Reject & Resubmit** at _Journal of Political Economy_

**Abstract:** This paper investigates how consumers and investors react to the standardized disclosure of data privacy practices. Since December 2020, Apple has required all apps to disclose their data collection practices by filling out privacy ''nutrition'' labels that are standardized and easy to read. We web-scrape these privacy labels and first document several stylized facts regarding the supply of privacy. Second, augmenting privacy labels with weekly app downloads and revenues, we examine how this disclosure affects consumer behavior. Exploiting the staggered release of privacy labels and using the nonexposed Android version of each app to construct the control group, we find that after privacy label release, an average iOS app experiences a 14% (15%) drop in weekly downloads (revenue) when compared to its Android counterpart. The effect is stronger for more privacy-invasive and substitutable apps. Moreover, we observe negative stock market reactions, especially among firms that harvest more data, corroborating the adverse impact on product markets. Our findings highlight data as a key asset for firms in the digital era. 

**Award:** Best Paper Award at the Annual Conference in Digital Economics 2022 

**Presented at:** SITE 2024, FIRS 2024, EFA 2023, SFS Cavalcade 2023, AEA 2023, Colorado Finance Summit 2022, CEPR Household Finance Seminar, TSE-Yale Regulating the Digital Economy Workshop 



Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

------
Work in Progress
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
