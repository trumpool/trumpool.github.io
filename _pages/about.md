---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io). -->

I'm an undergraduate from [College of Computer Science](http://www.en.cs.zju.edu.cn/), [Zhejiang University](https://www.zju.edu.cn/). 

My research interest includes natural language processing, multimodal models and image editing.

I am very fortunate to be advised by [Prof. SiLiang Tang](https://person.zju.edu.cn/en/siliang) and [Prof. Juncheng Li](https://scholar.google.com.hk/citations-user=lm9s-QgAAAAJ&hl=zh-CN) of DCD Lab from [School of Computer Science](http://www.en.cs.zju.edu.cn/), Zhejiang University. 

You can find my CV here: [Xiaoyang Wan's Curriculum Vitae](../assets/CV.pdf).

[Email](3210105708@zju.edu.cn) / [Github](https://github.com/trumpool)

<!-- A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
2. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
3. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
4. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
5. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
6. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->

### My Research Experience

Here is my research experience. I am interested in the intersect of large language model and image comprehension. You are welcome to contact with me.

-----
### AnyEdit: Unified High-Quality Image Edit with Any Idea （Accepted By CVPR 2025）
#### Advisors: Juncheng Li, Aug 2024 - Jan 2025

- Debugged and optimized existing image editing pipelines, including diffusion models and HuggingFace frameworks, to address challenges in large-scale image editing tasks.
- Configured and executed various scripts for the AnyEdit project, including setting up the environment(e.g., Conda), downloading pre-trained weights, and running multiple pipelines with specified parameters.
- Compared performance across pipelines to identify the ideal model for a certain task, analyzing results for accuracy, efficiency, and visual consistency for move&resize pipeline. And use masks of different objects in the image to identify the most ideal object for the task.
- Designed and implemented a checkpoint save-and-resume mechanism, allowing the system to automatically save progress and resume operations seamlessly after interruptions.

### Contextual Synthesis for Comprehensive Multi-modal Description
#### Collaborate with Hongjun Liu, Mar 2024 - Jun 2024

- Built a Retrieval-Augmented Generation (RAG) knowledge base by constructing datasets that pair comic images with contextual information retrieved from Wikipedia, utilizing Contriver, a powerful multilingual and cross-lingual retrieval model.
- Enabled language models like GPT to generate contextually accurate responses by retrieving relevant comic descriptions from the knowledge base and combining them with generated image descriptions.

### Other Projects

Here are some interesting project I have done in my courses and spare time, you are welcome to discuss any details with me.

-----
### 2D Game Development in NUS School of Computing Summer Workshop
#### Lecturer: Kelvin Sung, Jun 2023

- Actively participated in the entire game development process, from the initial proposal, creating prototypes, and rough demos, through alpha and beta testing, to the final player testing and game release.
- Build a solid turn-based game system to support multiple players and their skill casting at arbitrary time, using Unity and C#.
- **Achieved an A+ score** (top 5% in the course), and [our game](https://fluuuegel.github.io/WebGL/) secured the **2nd place** in the final showcase. Remarkably, this was accomplished without any prior hands-on experience in Unity, while competing against seasoned game developers in the course.

### DAMO Academy & ModelScope Practical AIGC Training Program
#### Aug 2023 - Sep 2023

- Created stylized AIGC styles based on base model majicMix-v6 by prompt-engineering to create solid 
art style, and trained LoRA to make New Year Style portraits.
- Integrated new styles we create into facechain, a deep-learning toolchain for generating your DigitalTwin released by modelscope.
- Won **3rd prize in the 6th Open Source Innovation Competition** for the new portrait style we provided.

### Zhejiang University B/S Software Development Course (96/100)
#### Course Project: Building a MQTT server for managing Internet of Things (IoT) devices.*

- Utilized the UmiJS framework, Ant Design component library and React to build a user interface for device management. Implemented features include login authentication, data analytics, and device location tracking.
- Adopted Go as the programming language for backend development, integrated with the Gin framework for efficient architecture, and utilized GORM for seamless database operations, all while working with a MySQL database.