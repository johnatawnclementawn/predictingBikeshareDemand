# predictingBikeshareDemand
Predicting Bike share demand, University of Pennsylvania MUSA Public Policy Analytics - Fall 2021



8.6 Assignment - Predict bike share trips

One of the most difficult operational problems for urban bike share systems is the need to ‘re-balance’ bicycles across the network. Bike share is not useful if a dock has no bikes to pickup, nor if there are no open docking spaces to deposit a bike. Re-balancing is the practice of anticipating (or predicting) bike share demand for all docks at all times and manually redistributing bikes to ensure a bike or a docking place is available when needed.

In this assignment, you will pick a city with a bike share open data feed and forecast space/time demand for bike share pickups. Most bike share data has fields for origin, destination and date/time.

Envision a bike re-balancing plan and design an algorithm to inform such a plan. The deliverables include:

    2-3 paragraphs that introduce the reader to bike share and the need for re-balancing. How will re-balancing occur? Perhaps you will manage a small fleet of trucks to move bikes from here to there or perhaps you will offer rewards, discounts or other incentives for riders to move a bike from place to place. Keep in mind, your plan will inform the appropriate time lag features you can use. How far forward do you wish to predict for at any given time?

    Your unit of analysis here is the bike share station, not Census tracts. Engineer features to account for weather and time effects and experiment with some amenity features. Develop two different training/test sets including 1) a 3 week training set and a 2 week test set of all the stations and 2) a complete 5 week panel for cross-validation.

    Develop exploratory analysis plots that describe the space/time dependencies in the data and create an animated map. Interpret your findings in the context of the re-balancing plan.

    Use purrr to train and validate several models for comparison on the latter two week test set. Perform either random k-fold cross validation or LOGO-CV on the 5 week panel. You may choose to cross validate by time or space. Interpret your findings in the context of accuracy and generalizability.

    Conclude with how useful your algorithm is for the bike re-balancing plan.

