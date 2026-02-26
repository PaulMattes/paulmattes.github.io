---
title: 'SIR: Structured Image Representations for Explainable Robot Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jan Schwab
  - Jens Oliver Bosch
  - Maximilian Xiling Li
  - Nils Blank
  - Minh-Trung Tang
  - Moritz Haberland
  - Rudolf Lioutikov

date: '2026-06-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Computer Vision and Pattern Recognition Conference*
publication_short: In *CVPR*

abstract: Existing robot policies based on learned visual embeddings lack explicit structure and are sensitive to visual distractions. Thus, the representations that drive their behaviour are often opaque, making their decision-making process difficult to interpret. To address this, we introduce Structured Image Representations (SIR), a method that leverages Scene Graphs (SGs) as an intermediate representation for robot policy learning. Our approach first constructs a fully connected graph, using 2D or 3D image-derived features as initial node representations. Then, a module learns to sparsify this graph end-to-end, creating a minimal, task-relevant sub-graph that is passed to the action generation model. This process makes our model intrinsically explainable. Evaluations on RoboCasa show that our sparse graph policies outperform image-based baselines on average with 19.5% vs 14.81% success rate. We also demonstrate that our graph-based representations are significantly more robust to distractor objects, showing almost no performance degradation, as opposed to image representations. Most importantly, we show that the learned sparse graphs are a powerful tool for model analysis. By analysing when the model’s sub-graph deviates from human expectation, such as by including distractor nodes or omitting key objects, we successfully uncover dataset biases, including spurious correlations and positional biases. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/intuitive-robots/SIR_Model'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false
---

## Read the Paper

<div class="columns is-centered">
    <object data="sir.pdf" type="application/pdf" width="100%" height="800px">
        <p>Your browser doesn't support embedded PDFs. <a href="sir.pdf">Click here to download the paper.</a></p>
    </object>
</div>
