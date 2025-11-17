---
title: "Master's Thesis: Reconstructing CAD models of non-complex objects from point clouds: A data-driven approach"
importance: 100
excerpt: "Point cloud data from laser scanners can be acquired in large quantities, yet it lacks explicit connectivity. CAD models, in contrast, offer structured and parametric representations used widely across industry. In this work I developed a deep learning model that transforms point clouds of scanned objects into their corresponding CAD models (sketch-and-extrude operations). The model is trained on the publicly available DeepCAD dataset. To improve reconstruction performance, a segmentation approach is applied that splits each CAD model into its individual extrusions, forming primitive CAD models. Experiments show that training on these segmented primitives not only increases reconstruction quality and model generalizability but also enables the inference of more complex CAD models. ([Paper](TODO), [Code](https://github.com/saidharb/Point-Cloud-Reconstruction/tree/main))<br/><img src='/images/MA.png'>"
collection: portfolio
---

My master's thesis was done at IGP at TU Braunschweig in 2025 under the supervision of Dr. Maboudi and Prof. Gerke. You can find the paper [here](http://saidharb.github.io/files/improving_htd_DOTA.pdf) and the code in this [GitHub repository](https://github.com/saidharb/Point-Cloud-Reconstruction/tree/main).
