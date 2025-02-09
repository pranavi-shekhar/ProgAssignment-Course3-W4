# Getting and Cleaning Data Course Project

**Human Activity Recognition Using Smartphones Dataset
Version 1.0**

Jorge L. Reyes-Ortiz, Davide Anguita, Alessandro Ghio, Luca Oneto.
Smartlab - Non Linear Complex Systems Laboratory
DITEN - Università degli Studi di Genova.
Via Opera Pia 11A, I-16145, Genoa, Italy.


## Contents of the Raw Dataset

#### For each record it is provided -


- Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
- Triaxial Angular velocity from the gyroscope. 
- A 561-feature vector with time and frequency domain variables. 
- Its activity label. 
- An identifier of the subject who carried out the experiment.

#### The raw dataset contains the following files -


- *README.txt*

- *features_info.txt* -  Shows information about the variables used on the feature vector.

- *features.txt*  - List of all features.

- *activity_labels.txt* - Links the class labels with their activity name.

- *train/X_train.txt* - Training set.

- *train/y_train.txt* - Training labels.

- *test/X_test.txt* - Test set.

- *test/y_test.txt* - Test labels.

#### The following files are available for the train and test data. Their descriptions are equivalent. 

- *train/subject_train.txt* - Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30. 

- *train/Inertial Signals/total_acc_x_train.txt* - The acceleration signal from the smartphone accelerometer X axis in standard gravity units *g*. Every row shows a 128 element vector. The same description applies for the *total_acc_x_train.txt* and *total_acc_z_train.txt* files for the Y and Z axis. 

- *train/Inertial Signals/body_acc_x_train.txt* - The body acceleration signal obtained by subtracting the gravity from the total acceleration. 

- *train/Inertial Signals/body_gyro_x_train.txt* - The angular velocity vector measured by the gyroscope for each window sample. The units are radians/second. 

##### Notes  
 
- Features are normalized and bounded within [-1,1].
- Each feature vector is a row on the text file.

## The Tidy Dataset


- The tidy dataset is a single file obtained by merging the training (**X_train.txt** and **y_train.txt**) and test (**X_test.txt** and **y_test.txt**) data together, along with the subject corresponding to each observation(**subject_train.txt** and **subject_test.txt**)
- The dataset contains only the average of mean and  standard deviation measurements of all the variables, for each subject performing each activity.


## License  
 
- Use of this dataset in publications must be acknowledged by referencing the following publication [1] 

- [1] Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. Human Activity Recognition on Smartphones using a Multiclass Hardware-Friendly Support Vector Machine. International Workshop of Ambient Assisted Living (IWAAL 2012). Vitoria-Gasteiz, Spain. Dec 2012

- This dataset is distributed AS-IS and no responsibility implied or explicit can be addressed to the authors or their institutions for its use or misuse. Any commercial use is prohibited.

*Jorge L. Reyes-Ortiz, Alessandro Ghio, Luca Oneto, Davide Anguita. November 2012.*
