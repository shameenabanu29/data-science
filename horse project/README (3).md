Horse colic prediction

Introduction :
      

      This data science project leverages historical medical records to effectively determine the survival probability of horses with colic by utilizing predictive models that evaluate the likelihood of their survival, taking into account past medical conditions.



Objective:


        * estimate the probability of survival for horses affected by colic.
        * provide valuable insight to veterinarians and horse owners.
        *identify the most influential features for accurately predicting outcomes.




Selection of data
   


         object                       float               integer
                                *rectal temp           *  hospital
         *surgery               *pulse                    number
         *age                   *respiratoy rate       * lesson1
         *temp of extremities   *nasogastric reflux ph * lesson2
         *peripheral_pulse      *packed cell volume    * lesson3
                                *total protein
         *mucous membrane       *abdomo protein
         *capillary refil time
         * pain
         *peristaisis
         *abdominal distention
         *nasogastric tube
         *nasogatric reflux
         *rectal exam feces
         *abdomen
         *outcome
Approach:
        Datacleaning:
               discarded columns with more than 50% of the data missing
               * nasogatric reflux ph
               * abdomo protein
               * abdomo apperance

         Data reduction:
         discarded column that were irrelevant to the calculations
            *cp data
            *hospital number

        Data transformation:
                the "outcomes" colums was converted from           catagorical   to numeric.

        Feature engineering:
                 the remaining categorical data was converted to numeric using one hot encoding.


Methods: 
          iam using here random forest clssifier and decision tree
          because acuracy is good when compared to other methods in supervised machine learning.

Summary:
         most effective model:
         randomforest classifier ,test accuracy >96%

Top three features correlated with outcome:
         packed cell volume
         pulse
         total protein


Noteworthy correlations:
         peristalsis vs abdominal distention
         absence of feces vs necessity of surgery
               



video link:


         


  



