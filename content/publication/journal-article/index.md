---
title: "A methodology of steel microstructure recognition using SEM images by machine learning based on textural analysis"
authors:
- admin
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2020-10-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-10-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*materials today communications*, Volume 25, December 2020, 101514"
publication_short: ""

abstract: 熱処理の異なる8種の鉄鋼組織のSEM(Scanning Electron Microscope)画像に対してGLCM(Gray-Level Co-occurrence Matrix)というテクスチャ特徴量を用いてGBDTで組織分類を行なった研究です。修士2年の8月から実験を行い、修論として執筆し卒業後も論文の執筆に携わり2020年10月にジャーナルに投稿しました。

# abstract: We attempt image-based recognition of scanning electron microscopy (SEM) of low-carbon steels using machine learning (ML) methodology utilizing feature extraction with textural analysis. Specimens are subjected to eight different heat treatments to generate microstructures of martensite, upper bainite, lower bainite, and these mixed structures are selected as candidates for the proposed recognition method. Additionally, two types of SEM sources, i.e. field emission (FE) and tungsten (W), are used, and the images individually apply to the classifications. To extract features, a textural analysis based on gray-level co-occurrence matrix (GLCM) is adopted based on the captured SEM images. For evaluating GLCM features, the original SEM images are cropped into 16 mini-images, and the following three recognition schemes are then applied recognize mini-images individually, recognize original image categories by majority vote on predictions of mini-images, and recognize original image by using feature averages of the mini-images for training. We also adopt two decision tree-based machine learning models of random forest (RF) and gradient boosting machine (GBM). The voting schemes for both models accomplish satisfactory accuracies of about 85% for eight steel microstructures. Especially, GBM is found to exhibit more stable performance than that of RF, as differences in accuracies between types of SEM sources are lower. In addition, differences between the SEM sources are discussed by focusing on important features estimated by these ML models, and the features from FE-SEM tend to be distributed more broadly than those of W-SEM. Although a textural value called homogeneity is commonly selected as an important feature, regardless of sources and models, the other important GLCM features exhibit different trends for both SEM sources. Models trained by FE- and W-SEM tend to prefer indices of high sensitivity with regards to local brightness differences and smoothness, respectively. Due to these differences in GLCM features and their importance, models trained with images from one SEM source cannot adequately recognize the other SEM images.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
# featured: false

links:
- name: "URL"
  url: "https://www.sciencedirect.com/science/article/abs/pii/S2352492820325253"


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

---

