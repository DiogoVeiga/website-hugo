+++
title = "Predicting transcriptional regulatory interactions with artificial neural networks applied to E. coli multidrug resistance efflux pumps"
date = 2008-06-19T11:47:36-05:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Diogo F.T. Veiga, Fábio F.R. Vicente, Marisa F. Nicolás, Ana Tereza R. Vasconcelos"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "BMC Microbiology"
publication_short = ""

# Abstract and optional shortened version.
abstract = "BACKGROUND: Little is known about bacterial transcriptional regulatory networks (TRNs). In Escherichia coli, which is the organism with the largest wet-lab validated TRN, its set of interactions involves only approximately 50% of the repertoire of transcription factors currently known, and 25% of its genes. Of those, only a small proportion describes the regulation of processes that are clinically relevant, such as drug resistance mechanisms. RESULTS: We designed feed-forward (FF) and bi-fan (BF) motif predictors for E. coli using multi-layer perceptron artificial neural networks (ANNs). The motif predictors were trained using a large dataset of gene expression data; the collection of motifs was extracted from the E. coli TRN. Each network motif was mapped to a vector of correlations which were computed using the gene expression profile of the elements in the motif. Thus, by combining network structural information with transcriptome data, FF and BF predictors were able to classify with a high precision of 83% and 96%, respectively, and with a high recall of 86% and 97%, respectively. These results were found when motifs were represented using different types of correlations together, i.e., Pearson, Spearman, Kendall, and partial correlation. We then applied the best predictors to hypothesize new regulations for 16 operons involved with multidrug resistance (MDR) efflux pumps, which are considered as a major bacterial mechanism to fight antimicrobial agents. As a result, the motif predictors assigned new transcription factors for these MDR proteins, turning them into high-quality candidates to be experimentally tested. CONCLUSION: The motif predictors presented herein can be used to identify novel regulatory interactions by using microarray data. The presentation of an example motif to predictors will make them categorize whether or not the example motif is a BF, or whether or not it is an FF. This approach is useful to find new pieces of the TRN, when inspecting the regulation of a small set of operons. Furthermore, it shows that correlations of expression data can be used to discriminate between elements that are arranged in structural motifs and those in random sets of transcripts."
abstract_short = " "

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "10.1186/1471-2180-8-101"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
