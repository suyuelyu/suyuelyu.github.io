---
title: "Variational autoencoder for design of synthetic viral vector serotypes"
authors:
- Suyue Lyu
- Shahin Sowlati-Hashjin
- Michael Garton
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2024-01-23"
doi: "https://doi.org/10.1038/s42256-023-00787-2"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-23"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Nature Machine Intelligence"
publication_short: ""

abstract: Recent, rapid advances in deep generative models for protein design have focused on small proteins with lots of data. Such models perform poorly on large proteins with limited natural sequences, for instance, the capsid protein of adenoviruses and adeno-associated virus, which are common delivery vehicles for gene therapy. Generating synthetic viral vector serotypes could overcome the potent pre-existing immune responses that most gene therapy recipients exhibit—a consequence of previous environmental exposure. We present a variational autoencoder (ProteinVAE) that can generate synthetic viral vector serotypes without epitopes for pre-existing neutralizing antibodies. A pre-trained protein language model was incorporated into the encoder to improve data efficiency, and deconvolution-based upsampling was used for decoding to avoid degenerate repetition seen in long protein sequence generation. ProteinVAE is a compact generative model with just 12.4 million parameters and was efficiently trained on the limited natural sequences. Viral protein sequences generated were used to produce structures with thermodynamic stability and viral assembly capability indistinguishable from natural vector counterparts. ProteinVAE can be used to generate a broad range of synthetic serotype sequences without epitopes for pre-existing neutralizing antibodies in the human population, effectively addressing one of the major challenges of gene therapy. It could be used more broadly to generate different types of viral vector, and any large, therapeutically valuable proteins, where available data are sparse.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
- name: JOURNAL LINK
  url: "https://www.nature.com/articles/s42256-023-00787-2"
url_pdf: ''
url_code: 'https://doi.org/10.24433/CO.2530457.v2'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
