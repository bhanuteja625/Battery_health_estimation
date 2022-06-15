# Battery_health_estimation

This project is aimed at estimating the state of health of the battery using machineleanring techniques such as DNN, CNN, simpleRNN, GRU, LSTM.

The file Model.ipynb consists of all the data preprocessing modules and ML models used in the project. The weights of the Ml models are saved in .H5 format so that the
weights can be easily loaded and used.

the weights of each model are saved with their model name and with the extension .h5. The model weights can be loaded eleminating the neccesity for training the model over and over again saving time.

the plots between the actual testlabels and the predicted SOH can be seen below for each model.

Prediction plot for DNN for Battery 05:

![12](https://user-images.githubusercontent.com/61615845/173832477-62a96147-e548-49a2-a008-933db7933f25.png)

Prediction plot for GRU for Battery 05:

![20](https://user-images.githubusercontent.com/61615845/173832778-374b12db-739e-459a-b979-02e6b5328117.png)

Prediction plot for LSTM for Battery 05:

![28](https://user-images.githubusercontent.com/61615845/173832871-8f27d954-04be-45be-9cbf-503ecbd2d65b.png)
