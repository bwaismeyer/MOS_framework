# The Multinomial Outcome Simulator (MOS) 
The MOS is an R and Shiny application for exploring multinomial models through simulation and visualization.

Specifically, users interact with an instance of the application by adjusting model inputs and then observing as the application simulates likelihoods for the model outcomes.

An MOS application instance is created by forking the MOS\_framework repo (or otherwise collecting the key files), customizing the MOS\_config.R file, and providing any resources needed by the instance (e.g., a data CSV, additional R scripts that process imported data, etc.).

This goal of this customization is to provide a specific multinomial model formula, the well-formatted data frame this model will be fit against, and some basic user-interface configuration.

Once an MOS application instance has been defined, it can be run and shared like any Shiny application (and there are a lot of options for [sharing a Shiny application](http://shiny.rstudio.com/tutorial/lesson7/)).

A demonstration MOS instance hosted on AWS can be viewed [here]()**(Not Yet). The complete code for the instance is available [here]()**(Nope - Not Yet Either)**.
