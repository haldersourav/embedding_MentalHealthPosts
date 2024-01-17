# Transformer-based embedding of posts regarding mental health from cancer patients and their caregivers
Posts from cancer patients and their caregivers on various platforms were analyzed using a transformer-based neural network to generate a high-dimensional embedding vector space for visualizing and identifying the similarities and dissimilarities between the various posts. This analysis has the potential to provide insights into the emotional aspects of cancer patients' posts for a mental health study.

### Data
Over 10,000 posts from cancer patients and their caregivers on platforms like Reddit, Daily Strength, and the Health Board were collected (More details about the dataset, as well as the dataset, can be found here: https://www.kaggle.com/datasets/irinhoque/mental-health-insights-vulnerable-cancer-patients). The posts were related to five types of cancer: brain, colon, liver, leukemia, and lung cancer. Two team members scored each post based on the emotions expressed, using a scale from -2 to 1. Negative scores (-1 or -2) were given for posts showing grief or suffering, positive scores (1) for happy emotions like relief or accomplishment, and posts with no emotion received a score of 0 and were considered neutral. 

### Neural network 
##### TSDAE (Transformer-based Sequential Denoising Auto-Encoder)
TSDAE is an unsupervised sentence embedding learning method. Further details of this network can be found in this paper: https://arxiv.org/abs/2104.06979

### Important libraries
1) PyTorch (https://pytorch.org)
2) Sentence Transformers (https://www.sbert.net)
