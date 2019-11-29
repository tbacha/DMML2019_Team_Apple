Read me file

The goal of the project is to predict if a Kickstarter project will fail or succed depending on its informations.

Our starting point is this dataset from Kaggel: https://ai.googleblog.com/2015/06/inceptionism-going-deeper-into-neural.html

On this dataset, we can find around 375'000 Kikckstarter project's informations. We have informations such as the name of the project, its category, the important dates, the money they need and if the project was a sucess or a fail.

First, we decided to delete the row about the project that are not either fail or succed. It does not represent a large part of our database. We then had to clean the datas because we found some weird row. For exemple, we have succesful project data has no contributor or who earned nothing.

To have a better visualization of our database, we made some EDA that you can find in the notebook. This helped us to have the first insights and to know in which direction we will go with our machine learning tools.
