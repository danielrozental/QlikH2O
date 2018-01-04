# QlikH2O
Integration Example Between Qlik and H2O using Python SSE Plugin

Simple example using kmeans algorithm in H2O to calculate clusters over Iris dataset.

This is not intended as a deep analysis on the Iris dataset but as an integration example between Qlik and H2O using the recently introduced Server Side Extensions and the open sourced Python plugin.


## Qlik Sense App
1. Shows the dataset and calculates the clusters. Lets you define how many clusters there will be used to group individuals.
2. Shows and original clases and calculated clusters.
3. Allows the user to define the attributes for a new individual and see what cluster it gets grouped into.

## Configurations
1. Download the modified Python SSE Plugin from the [repo](https://github.com/danielrozental/QlikH2O/)
2. Install and configure Python (If not sure where to start you can download [Anacondas Distribution](https://www.anaconda.com/download/))
3. Download and run [H2O.ai](https://www.h2o.ai/download/)
4. Install [H2O Python Modules](http://docs.h2o.ai/h2o/latest-stable/h2o-docs/downloading.html)
5. Download [SSE_H2O_Cluster.qvf](https://github.com/danielrozental/QlikH2O/blob/master/Example%20Files/SSE_H2O_Cluster.qvf) and copy it to Documents\Qlik\Sense\Apps
6. Configure Python Plugin in Qlik Sense's settings.ini file (https://community.qlik.com/community/advanced-analytics-integration).
7. Run Python ExtensionService_H2O_Cluster.py
8. Open the Qlik Sense SSE H2O Cluster app and test it

## For more information
* [Qlik OSS Repository SSE documentation and examples](https://github.com/qlik-oss/server-side-extension)
* [Qlik Advaned Analytics Community Group](https://community.qlik.com/community/advanced-analytics-integration)
* [H2O.ai](H2O.ai)
