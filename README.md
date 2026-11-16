# CSC4026

Computer vision and image processing coursework implemented as Jupyter
notebooks, covering contrast enhancement, morphological operations, and image
classification.

## Install

Requires Python 3.

```bash
pip install -r requirements.txt
```

## Usage

Open and run any `.ipynb` notebook.

### Workspace

- [`histogram-equalization/`](histogram-equalization/): Contrast enhancement
  comparing HE, AHE, and CLAHE using PSNR and SSIM.
- [`dilation-erosion/`](dilation-erosion/): Morphological dilation and erosion
  across square, cross, vertical, and horizontal structuring elements.
- [`opening-closing/`](opening-closing/): Morphological dilation, erosion,
  opening, and closing on binary images.
- [`knn/`](knn/): K-Nearest Neighbors image classification on CIFAR-10 with
  5-fold cross-validation.
- [`linear-classification/`](linear-classification/): Linear classification on
  CIFAR-10 exploring random weight initialization, class scores, multiclass SVM
  hinge loss, Softmax probabilities, and weight template visualization.
