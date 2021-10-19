---
layout: page
published: true
title: Resume
order: 2
header-includes:
  - \usepackage{pdfpages}
---
```{r label, out.width = "85%", fig.cap = "Resume"}
knitr::include_graphics(path = "/docs/Resume.pdf")
`````

\includepdf[pages=-,nup=2,pagecommand={}]{/docs/Resume.pdf}

