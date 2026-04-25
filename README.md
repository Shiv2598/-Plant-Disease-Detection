# -Plant-Disease-Detection




🌿 Plant Disease Detection — ResNet-152

Trained a ResNet-152 model on leaf images to detect 38 plant diseases.
Used transfer learning — froze the backbone and trained only the classifier head.
Built as part of the FITT IIT Delhi Computer Vision Capstone (Skilled in Odisha).

Dataset:
https://www.kaggle.com/datasets/emmarex/plantdisease

Tech used:
- PyTorch 2.x
- Google Colab (T4 GPU)
- PlantVillage Dataset (54,306 images, 38 classes)

How to run:
1. Open the .ipynb file in Google Colab
2. Enable GPU (Runtime > Change runtime type > T4)
3. Upload your kaggle.json when asked
4. Run all cells top to bottom

Results:
- Val Accuracy: ~95%
- Training Time: ~2.5 hours on Colab GPU
