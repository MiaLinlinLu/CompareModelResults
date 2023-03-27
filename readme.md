# Steps:
## Run jupyter notebook on cluster  ---> get csv files for distance. 
[Calc_Distance_for_Batch_Samples_CFlow.ipynb](https://github.com/MiaLinlinLu/CompareModelResults/blob/main/Calc_Distance_for_Batch_Samples_CFlow.ipynb)

    ### how to run this jupyter notebook
    1, ```ssh arcdev1```
    
    2, ```cd /data/users2/llu13```
    
    3, ```module load freesurfer/7.3.2```
    
    4, ```jupyter notebook --no-browser --port=1034```
    copy the lINK.
    
    5, open another terminal on local laptop
    ```ssh -N -L localhost:1034:localhost:1034 llu13@arcdev1```
    
    6, login the jupyter notebook through the LINK
    
    
 ## Run jupyter notebook on local ----> plot histograms for distance

[plot_distance_from_csv_files.ipynb](https://github.com/MiaLinlinLu/CompareModelResults/blob/main/plot_distance_from_csv_files.ipynb)
    
   



