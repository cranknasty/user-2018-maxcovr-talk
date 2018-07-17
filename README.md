
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Find the best locations for facilities using `maxcovr`

A talk presented by [Nick Tierney](), presented at [UseR\!2018]()
Twitter: \[@nj\_tierney\](<https://twitter.com/nj_tierney>) GitHub:
\[@njtierney\](<https://github.com/njtierney>)

**Abstract**

> Want better wifi at the office? Improved access to healthcare? The
> maximal covering location problem (MCLP) can help\! The MCLP finds
> optimal locations of facilities to improve their coverage on a set of
> targets. This means better placed wifi routers and healthcare
> facilities. Although the MCLP was described in the 1970s, it can be
> daunting to actually implement as you need to know how to:

> 1)  Formulate an optimisation problem

> 2)  Make it talk to a solver engine

> 3)  Get the data into the appropriate format for the solver to
>     recognise

> 4)  Translate the model output into a usable format

> It is challenging, particularly if you are not familiar with
> optimisation, or techniques such as linear programming. It is,
> however, a great use case for an R package to abstract away detail you
> don’t need to worry about. The R package maxcovr provides a set of
> tools to perform, summarise, and visualise the MCLP, so that you can
> move on with your analysis, place better cellphone towers, and create
> better access to health facilities.In this talk, I describe why the
> MCLP is useful, where it can be applied, and demonstrate of the use of
> maxcovr, before finally discussing future directions.

# Slides

# Data

This talk drew upon publicly available datasets from the Brisbane
government - from <https://www.data.brisbane.qld.gov.au/>. The datasets
were initially suggested by friendly folks from the Stories with Data
Slack channel,

The data comes from the following repositories

  - [Property Address
    Locations](https://www.data.brisbane.qld.gov.au/data/dataset/property-address-data)
  - [Wireless hotspot
    locations](https://www.data.brisbane.qld.gov.au/data/dataset/wireless-hotspot-sites-libraries-and-parks)
  - [Bus stop
    locations](https://www.data.brisbane.qld.gov.au/data/dataset/brisbane-bus-stops)
  - [Public art
    locations](https://www.data.brisbane.qld.gov.au/data/dataset/public-art/resource/3c972b8e-9340-4b6d-8c7b-2ed988aa3343?view_id=ee54f886-717b-4cc1-b012-944d48ac597e)

Each of the datasets can be found in the [`data-raw/`]() folder
