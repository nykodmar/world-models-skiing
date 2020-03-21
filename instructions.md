For running the implementation upload world-models-skiing folder to your google drive root folder
and open [world_models_skiing.ipynb](world_models_skiing.ipynb) in Google Collaboratory.

Cells has dependency on the code above them, so the notebook cells must be executed in 
order (ctrl + F9 to execute all cells). 

After running the cells, Google asks you to grant permission for accessing to your google drive. 
(Needs access to the files in the folder)


Options of the program are:
  * RUN_TESTS - visualize progress and rerun testing the final results      
  * RETRAINING - for retraining at first delete the saved_models folder
                and in this order run:  
                  1. GENERATE_DATA_VAE  
                  2. RETRAIN_VAE  
                  3. GENERATE_DATA_LSTM  
                  4. RETRAIN_LSTM  
                  5. RETRAIN_CONTROLLER      
    
                                         
Used versions of notebook packages:  
atari-py==0.1.7  
glob2==0.6  
gym==0.10.11  
imageio==2.4.1  
imutils==0.5.2  
jupyter==1.0.0  
jupyter-client==5.2.4  
jupyter-console==6.0.0  
jupyter-core==4.4.0  
Keras==2.2.4  
Keras-Applications==1.0.7  
Keras-Preprocessing==1.0.9  
keras-vis==0.4.1  
matplotlib==3.0.3  
matplotlib-venn==0.11.5  
mesh-tensorflow==0.0.5  
numpy==1.16.1  
nvidia-ml-py3==7.352.0  
opencv-contrib-python==3.4.3.18  
opencv-python==3.4.5.20  
tensor2tensor==1.11.0  
tensorboard==1.13.1  
tensorboardcolab==0.0.22  
tensorflow==1.13.1  
tensorflow-estimator==1.13.0  
tensorflow-hub==0.4.0  
tensorflow-metadata==0.13.0  
tensorflow-probability==0.6.0  
torch==1.1.0  
torchsummary==1.5.1  
torchtext==0.3.1  
torchvision==0.2.2.post3                            
