---
layout: page
published: true
title: Resume
order: 2
header-includes:
  - \usepackage{pdfpages}
---
```{r label, out.width = "85%", fig.cap = "caption"}
knitr::include_graphics(path = "mychart.pdf")
`````

\includepdf[pages=-,nup=2,pagecommand={}]{/docs/Resume.pdf}

