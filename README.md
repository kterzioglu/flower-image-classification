# flower-image-classification
Flower Image Classification with VGG16 Transfer Learning (Keras)

Developed a flower species classifier using TensorFlow's flower dataset (5 classes: Daisy, Dandelion, Rose, Sunflower, Tulip; 3,670 images). Resized to 150x150, split 75/25% train/test with balanced classes. Leveraged pre-trained VGG16 (ImageNet): removed top, added FC layers (256 ReLU + 5 softmax). Experiments: (1) Froze all VGG16, fine-tuned custom layers (70% acc); (2) Unfroze block5, retrained (85% acc); (3) Unfroze all, retrained (88% acc). Compared results: Full unfreeze yielded best accuracy via end-to-end adaptation but risked overfitting. Submitted Jupyter notebook with code, comments, and interpretations. AI certificate coursework.

