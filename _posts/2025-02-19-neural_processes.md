---
layout: post
title: Neural Processes in PyTorch
date: 2025-02-18 00:00:00-0400
description: PyTorch implementation of Latent Neural Processes
categories: ML NP Coding
giscus_comments: false
related_posts: true
---

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/neural-processes-in-pytorch.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/neural-processes-in-pytorch.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}