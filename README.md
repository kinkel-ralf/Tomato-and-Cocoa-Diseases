Makeathon Tomatoes is trained with a dataset provided at:                     
https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf

Makeathon Cocoa is trained with a dataset provided at:    
https://www.kaggle.com/datasets/zaldyjr/cacao-diseases   

In the ipynbs the export path to android is included with pytorch->onnx->tensorflow->tf-lite
(Note that currently we have implemented another model from a guide in the app, 
we verified that our tf-lite models run on python, but in android there is a bug with shape-mismatch 
(1x128x128x3 vs 1x3x128x128) that we couldn't fix in time for the presentation).
