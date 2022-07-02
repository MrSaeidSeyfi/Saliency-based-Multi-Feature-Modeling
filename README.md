# Saliency-based-Multi-Feature-Modeling
Saliency-based multi-feature modeling for semantic image retrieval
## About project 
This project implemented based on [elsevier journal](https://www.sciencedirect.com/science/article/abs/pii/S1047320317302304).
### Project roadmap
![index](https://user-images.githubusercontent.com/87762511/176985877-31a77b30-886f-4c9e-bbf0-3aad9a379c8a.jpg)


## Abstract
Abstract
Semantic gap is an important challenging problem in content-based image retrieval (CBIR) up to now. Bag-of-words (BOW) framework is a popular approach that tries to reduce the semantic gap in CBIR. In this paper, an approach integrating visual saliency model with BOW is proposed for semantic image retrieval. Images are firstly segmented into background regions and foreground objects by a visual saliency-based segmentation method. And then multi-features including Scale Invariant Feature Transform (SIFT) features packed in BOW are extracted from regions and objects respectively and fused considering different characteristics of background regions and foreground objects. Finally, a fusion of z-score normalized Chi-Square distance is adopted as the similarity measurement. This proposal has been implemented on two widely used benchmark databases and the results evaluated in terms of mean Average Precision (mAP) show that our proposal outperforms the referred state-of-the-art approaches.
## Credits

This project uses the following sourse codes:

- [congve1](https://github.com/congve1/SaliencyRC) 
- [rmislam](https://github.com/rmislam/PythonSIFT) 

## Result
For a given query image smfm framework sorted the related images base on chi-square distance similarity.
![siftresult](https://user-images.githubusercontent.com/87762511/176985953-b5731d9a-f109-49eb-8a55-d95147e3dda4.jpeg)
