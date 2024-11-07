# Week-3DB

For my project, I decided to use implement a machine learning model to classify the type of tree coverage was in this 30x30M area. The data set provided plenty of details such as elevation, aspect, the shade amount at certain times and the soil type. 

The model I used for this project was a random forest classifier model because these models are easy to use and understand beacuse they are less likely to overfit. The dataset I used had 581,012 entries, which is quite large for a data set. This is another reason why I chose to use a random forest classifier model becuase of its ability to handle large data sets.

The model I used came out with a 95% accuracy score. This is good since model only need 70% accuracy to be considered "great". Of the 7 coverage types, the model did not identify Cottonwood/Willow coverage as well as the others. This had an accuracy of 92% whereas the other coverages had an accuracy of 94-97%.
1 -- Spruce/Fir
2 -- Lodgepole Pine
3 -- Ponderosa Pine
4 -- Cottonwood/Willow
5 -- Aspen
6 -- Douglas-fir
7 -- Krummholz
