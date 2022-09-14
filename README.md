# Time-series-forecasting-for-sensor-data

After using various different resources ranging from automl libraries to individual models, a basic conclusion that for multivariate modelling[ involving various different 
features which can show interdependance] indidividual models had better tendency for accuracy.

This thesis led me to automate other parts of the system to create a smooth pipleline and reduce the need to re-take my steps.
I used the darts library to automate as much as i could and got best results with the NBEATSModel model in it. The process of elimination was quite manual had to test out differnt 
models that supported multivariate data in the first place.

The data was quite varied so had to scale it all in place.

Known improvements possible: the last rows data was not used at all, I would like to figure out how to use them in time series without using the 9,10,11,12,13 ones and 
make prediction even better.

NBEATModel- propose a deep neural architecture based on backward and forward residual links and a very deep stack of fully-connected layers. The architecture has a number of desirable properties,
being interpretable,applicable without modification to a wide array of target domains, and fast to train.

known problems: Due to the relatively small size of dataset overfitting may be a problem.
