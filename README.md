# Estimating Discrete Choice Models using Apollo

This repo provides several examples of estimation of a discrete choice models using the [Apollo](http://www.apollochoicemodelling.com/index.html) package in [Rstudio](https://www.rstudio.com/). The example code is drawn directly from the helpful list of [examples](http://www.apollochoicemodelling.com/examples.html) found on the Apollo website. Cloning this repository will allow you to replicate the design, choice card creation, and econometric simulation as discussed in the [summary document](https://bryanparthum.github.io/apollo_choice_modeling_examples/examples/Choice-Modeling-Using-Apollo.html).

While exploring the Apollo website, please read the helpful [manual](http://www.apollochoicemodelling.com/files/manual/Apollo.pdf) for detailed explanations of the package and the models available. 

## Replication instructions
Click on the "fork" button at the very top right of the page to create an independent copy of the repo within your own GitHub account. Alternatively, click on the green "clone or download" button just below that to download the repo to your local computer. 

All examples can be found in the markdown document `examples/Choice-Modeling-Using-Apollo.rmd`, or referenced directly using `examples/Choice-Modeling-Using-Apollo.html`.

## Requirements

The examples use *R*, a free open-source and available for download [here](https://www.r-project.org/).

## Performance

The analyses in these examples involve computationally intensive random parameter logit estimations. The computation time for each regression ranges from 5 to 45 minutes using 16 cores with 32GB RAM.

## Problems

If any errors are discovered, please inform the owner of this repository at parthum.bryan@epa.gov. Thank you!

## License

The software code contained within this repository is made available under the [MIT license](http://opensource.org/licenses/mit-license.php). The data and figures are made available under the [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/) license.
