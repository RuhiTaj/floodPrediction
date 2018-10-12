# codefundo++

# floodPrediction

Prediction of floods using LSTM Neural networks:

Neural Networks are useful at situations, where we need to understand the nature of complicated hydrological system.

      Long Short Term Memory networks(LSTMs) are a special kind of Recurrent Neural Networks, capable of learning long-term dependencies.

      LSTMs are explicitly designed to avoid the long-term dependency problem. Remembering information for long periods of time is practically  their default behavior.
      

Why LSTMs?

   Traditional neural networks can’t classify an event based on previously occurred events, they only look into the features of current event classify it accordingly. Recurrent neural networks address this issue. They are networks with loops in them, allowing information to persist.
But in practice, RNNs are not absolutely capable of handling “long-term dependencies”. So we use LSTM networks since they are well-suited to classifying, processing and making predictions based on time series data, since there can be lags of unknown duration between important events in a time series. 

All recurrent neural networks have the form of a chain of repeating modules of neural network. 

Looking into possible inputs that can be taken for training an LSTM model:

Possible causes behind the Kerala floods-2018:

    * Lots of Rain. There was an increase of 41.44% rainfall this season compared to the average rainfall in past years.

    * The flood situation worsened not just because of the downpour, but the opening of shutters of 35 dams at the same time.
  
    * Some reasons for its vulnerability were geographical, a challenge posed by its position amidst the Ghats. Deforestation on the Ghats causing loss of major water sinks.

    * Many other causes – quarrying, mining, illegal repurposing of forests and high-rise building constructions also obstructed soil to absorb the heavy rains.

Hence, for predicting future floods in any area, following inputs have to be taken into consideration:

    * Real-time Rain fall/Precipitation and Rain fall patterns in past 50-75 years.

    * Capacity of surrounding dams.
     
    * Density of surrounding forests and density of concrete buildings around.

    * Water holding capacity of Soil in the area.


   As seen from above, a single LSTM model with above input can account for flood prediction in a particular area based on the input data set at that particular area.

Sources for data sets:

1) https://data.gov.in/keywords/annual-rainfall

2) http://esapubs.org/archive/ecol/E091/216/metadata.htm

3) http://www.indiawaterportal.org/met_data/

4) http://sldckerala.com/index.php?id=7

# floodPrevention

    * Notify the authorities and people about the possible rainfall pattern (heavy).

    * Mechanisms to tackle potential increment in levels of dams in surrounding dams.
     
    * Plan cities(density) according to possible flood overflow.

    * Routes to deviate the rain water,if the rain exceeds the water holding cpacity.
 
