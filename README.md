# neural-project

## HOG 80.0439% classifier: SVM
`hog_cut.py`
- resize image (128,128)
- use mask after YCrCb conversion
- get max contour 
- draw the hand on new image to cut some of unwanted background
- resize new image (128,128)

## HOG 80.0439% classifier: SVM and adaboost
`adaboost.py`

## HOG 78.728% -> classifier: Random forest
`hog_random_forest.py`
- same as `hog_cut.py` 

## HOG 78.28947368421053% -> classifier: MLP
`mlp.py`
- same as `hog_cut.py` 
## HOG 75.43859649122807% -> soft voting (classifier: MLP , RDF , SVM)
`soft.py`
- same as `hog_cut.py` 
## HOG 72.37%
`hog_opencv.py`
- resize image (128,128)
- use mask after YCrCb conversion

## HOG & LBP 63.4%
`lbp.py`
- resize image (128,128)
- use mask after YCrCb conversion

## PCA & HOG 54.17%
`pca_feature.py`
- resize image (128,128)
- use mask after YCrCb conversion

## HOG  50.22% -> classifier: decision tree
`decison_tree.py`
- resize image (128,128)
- use mask after YCrCb conversion
- get max contour 
- draw the hand on new image to cut some of unwanted background
- resize new image (128,128)
