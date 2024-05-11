# IISCIFD
Indian Institute of science Indian Face Dataset

Faces form the basis for a rich variety of judgments in humans, yet the underlying features remain poorly understood. Fine-grained distinctions within a race might more strongly constrain the possible features, but are relatively less studied. Fine-grained race classification is also interesting because even humans may not be perfectly accurate on these tasks. This offers a unique opportunity to compare errors made by humans and machines, in contrast to standard object detection tasks where human performance is nearly perfect. 
We have benchmarked North Vs South categorisation on close to 130 humans and machines performance on a novel database of close to 1650 diverse Indian faces labeled for fine-grained race (South vs North India) as well as for age, weight, height and gender. We have explored a diverse set of features including part shape and configuration information, non CNN features such as HOG and LBP as well as various relevant CNNs.

We find that,
 (1) Humans show extremely consistent performance across faces (average accuracy: 63.6%), with some faces being consistently classified with > 90% accuracy and others consistently misclassified with < 30% accuracy; 

(2) Models trained on ground-truth labels showed slightly worse performance (average accuracy: 62%) but showed higher accuracy (72.2%) on faces classified with > 80% accuracy by humans. This was true for models trained on simple spatial and intensity measurements extracted from faces as well as deep neural networks trained on race or gender classification; 

(3) Using overcomplete banks of features derived from each face part, we found that mouth shape was the single largest contributor towards fine-grained race classification, whereas distances between face parts was the strongest predictor of gender. Our results show that computational models can explain a variety of face attributes and we hope that this study spurs further work on finer-grained classification of faces.

Please cite the following paper for IISCIFD: **Harish Katti; S. P. Arun, Are you from North or South India? A hard face-classification task reveals systematic representational differences between humans and machines,Journal of Vision, July 2019, Vol.19, 1.** doi:https://doi.org/10.1167/19.7.1 (weblink: https://jov.arvojournals.org/article.aspx?articleid=2737707)

Links for the face image dataset and visual features and behavioural data that have been extracted from these faces.

Please email harish2006@gmail.com for more details or queries.

CNSIFD face images: 500 x 500 gray scale images with normalised faces in elliptical cropped window. https://drive.google.com/file/d/1NHBi4phVG-EdMieYaht5biKX9Qe-zmEL/view?usp=sharing
Please use only images 1:459 in this set for illustrative purposes in publications. We only have informed consent for those. The rest have been obtained from the public domain and might be copyrighted.

CNSIFD attribute ground truth, behavioural data and computational features https://drive.google.com/file/d/1Lx4EVxOMZRfsaPf0SNtntUvnhrGgM4Ad/view?usp=sharing


Behavioural data, stimuli and code to generate analysis plots for the face occlusion behavioural experiment https://drive.google.com/file/d/17ri_Gq_CqTiLYnQqz5tojPf7NmiacA-4/view?usp=drive_link  
Please note that only faces 1:459 can be used for illustrations in publications. The rest have been obtained from the public domain and might be copyrighted.

A subset of 251 face images in color that can be used for publication https://drive.google.com/file/d/1NHBi4phVG-EdMieYaht5biKX9Qe-zmEL/view?usp=sharing 

All the code, data, images and visual features are made availalble purely for research purposes and should not be used for commercial gain.
