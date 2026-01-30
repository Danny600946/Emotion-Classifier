A classifier implemented to identify emotions from human speech using VAD scores aquired from a wave2vec model. This classifier is designed to work within ROS using a client and server relationship. The classifier demonstrated a 72.4% mean accuracy when tested against unseen RAVDESS files. It should be noted the classifier was trained on other RAVDESS audios so will exhibit bias.

The code is designed such that the RAVDESS dataset is required and if found will automatically train and save the resulting pkl classifier file to be used after and during the first run.
