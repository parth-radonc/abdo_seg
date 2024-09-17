# Abdominal Organs Auto Segmentation on 3D CT Scans <br />
Abdominal Organ Auto segmentation on 3D CT Scans <br />

# Dataset <br />
   Synapse Multi-organ CT Dataset(BTCV) <br />
# Models Used - <br />
   3D UNET <br />

# Classes <br />
   Background, Spleen, Right and Left kidney, Gall bladder, Esophagus, Liver, Stomach, Aorta, IVC, Veins, Pancreas, Right and Left Adrenal <br />

# Configuration <br />
   Image Preprocessing - Random Center Crop, Drop Invalid range,    Clipping, Resizing, Volume Intensity Normalization <br />
   Optimizer- Adam Optimizer <br />
   LR - Cosine Annealing LR <br />
   Loss Fn - BCEDICE LOSS at Multiple Output Layers/scales <br />

# Results <br />
   Dice Score between 0.8 - 0.95 for all the classes <br />

![ Alt text ](https://github.com/parth-radonc/abdo_seg/blob/main/Results/res.jpg?raw=true) 

 
