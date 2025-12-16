# AI2100-Deep-learning-IITH

Intro: Anomaly detection in videos<br>
Used DL/CV Techniques: Future frame prediction, self-supervised learning and contrastive learning<br>
Tech-stack used: Pytorch and Python<br>
Metrics: PSNR and regularities score<br>
What is done during the project: Done literative review, we replicated results of a research paper with our code<br>

Example: During inference 8-frame snippet is passed to model,<br> 1) future frame prediction: finds the 8th frame given 7 frames and applied PSNR with ground truth<br>
                                                              2) self-supervised: augmented snippet with self-supervision(giving each augmented snippet a class label) it                                                                         becomes a classification task and regularity score is calculated<br>
                                                              3) contrastive: group augmented snippet of same snippet together and regularity score is calculated
         -> if the regularity score is low indicates anomaly.

For more info check out code and report.
