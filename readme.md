# run code in jupyternotebook on cluster

## 
```ssh arcdev1```
```cd /data/users2/llu13```
```module load freesurfer/7.3.2```

##
```jupyter notebook --no-browser --port=1034```
copy the lINK.

## 
open another terminal on local laptop
```ssh -N -L localhost:1034:localhost:1034 llu13@arcdev1```

##
login the jupyter notebook through the LINK

