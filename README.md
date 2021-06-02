# Fast-Style-Transfer
Fast Style Transfer Demo build using Google Colab notebook.
This demo makes use of Tensorflow light models that I trained and converted.
The tensorflow model was paired with the architecture offered by Justin Johnson et al. in their 
work <a href="https://arxiv.org/pdf/1603.08155.pdf">"Perceptual Losses for Real-Time Style Transfer and Super-Resolution"</a> as well as the 
Instance Normalization proposed by Dmitry Ulyanov et al. in their work <a href="https://arxiv.org/pdf/1607.08022.pdf">"Instance Normalization: The Missing Ingredient for Fast Stylization"</a>.
All training was carried out on a Google Cloud AI Platform notebook equipped with a Tesla V100 GPU and the COCO dataset.

# Acknowledgements
This demo was inspired by <a href="https://github.com/sayakpaul">Sayak Paul's</a> awesome examples and his wonderful repository <a href="https://github.com/sayakpaul/Adventures-in-TensorFlow-Lite">Adventures-in-TensorFlow-Lite</a>, which you should definitely check out.
