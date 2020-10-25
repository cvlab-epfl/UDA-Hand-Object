# UDA-Hand-Object
Unsupervised Domain Adaptation with Temporal Consistency for 3D Joint Hand-Object Reconstruction

This repository contains the code for the paper [**Unsupervised Domain Adaptation with Temporal Consistency for 3D Joint Hand-Object Reconstruction**]. Mengshi Qi, Edoardo Remelli, Mathieu Salzmann and Pascal Fua.

In this work, we propose a novel geometry-preserved domain transfer method for joint 3D hand-object reconstruction. Specifically, we introduce a geometric 3D pose preservation constraint cycle generative adversarial network (CycleGAN) to transfer labeled synthetic data to real-style data, which helps to train 3D reconstruction model and bridge the gap between synthetic domain and real domain by capturing essential geometry information. Furthermore, we design a new temporal
consistency loss function to make full use of unlabeled video-based real data, which is enable to enhance the training of our proposed model and effectively avoid the model collapsed in a self-supervised manner.
