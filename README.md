# Boari_LSTM_On_vs_Off


1. If the csv called Linear_Kinematics.csv is already not in here, run 'Get_Boari_Data.ipynb' to get it.
2. Run 'HAR_lstm.ipynb' inside the Models folder, in the Model1 subfolder, to run the LSTM

###
- 'Get_Boari_Data.ipynb' -> Read Boari Dataset and turn linear kinematics and angular kinematics into independent csv files (initial script from Sara)
- 'load_data_boari_kinematics.ipynb' contains the code, modified from Sara´s GitHub to obtain all the kinematics information from Boari´s data. (https://github.com/nrg-projects/sara-on-off-boari/tree/main)

- 'HAR_lstm.ipynb' -> ipynb script that contains an LSTM model, slightly modified from @xieyulai´s code. run this code straight away, it will read the "Linear_Kinematics.csv"and start processing. This csv comes from the Get_Boari_data.ipynb
