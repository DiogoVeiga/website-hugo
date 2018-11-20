+++
title = "DASMiner: discovering and integrating data from DAS sources"
date = 2009-11-17T11:46:49-05:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Diogo F.T. Veiga, Helena F. Deus, Caner Akdemir, Ana Tereza R. Vasconcelos, Jonas S. Almeida"]

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
publication = "BMC Systems Biology"
publication_short = ""

# Abstract and optional shortened version.
abstract = "BACKGROUND: DAS is a widely adopted protocol for providing syntactic interoperability among biological databases. The popularity of DAS is due to a simplified and elegant mechanism for data exchange that consists of sources exposing their RESTful interfaces for data access. As a growing number of DAS services are available for molecular biology resources, there is an incentive to explore this protocol in order to advance data discovery and integration among these resources. RESULTS: We developed DASMiner, a Matlab toolkit for querying DAS data sources that enables creation of integrated biological models using the information available in DAS-compliant repositories. DASMiner is composed by a browser application and an API that work together to facilitate gathering of data from different DAS sources, which can be used for creating enriched datasets from multiple sources. The browser is used to formulate queries and navigate data contained in DAS sources. Users can execute queries against these sources in an intuitive fashion, without the need of knowing the specific DAS syntax for the particular source. Using the source's metadata provided by the DAS Registry, the browser's layout adapts to expose only the set of commands and coordinate systems supported by the specific source. For this reason, the browser can interrogate any DAS source, independently of the type of data being served. The API component of DASMiner may be used for programmatic access of DAS sources by programs in Matlab. Once the desired data is found during navigation, the query is exported in the format of an API call to be used within any Matlab application. We illustrate the use of DASMiner by creating integrative models of histone modification maps and protein-protein interaction networks. These enriched datasets were built by retrieving and integrating distributed genomic and proteomic DAS sources using the API. CONCLUSION: The support of the DAS protocol allows that hundreds of molecular biology databases to be treated as a federated, online collection of resources. DASMiner enables full exploration of these resources, and can be used to deploy applications and create integrated views of biological systems using the information deposited in DAS repositories."
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
doi = "10.1186/1752-0509-3-109"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
