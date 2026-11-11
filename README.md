We analyse classification behaviour on Fashion-MNIST, a dataset of 70,000 28x28 grayscale images across 10 clothing categories. Our goal is to examine how the model handles different types of apparel, looking into common misclassifications, confidence drops, and feature importance across broad item groupings (such as seasonal or structural categories). We also want to see how image transformations affect predictions and inspect internal representations to understand what visual features drive errors.

Dataset: https://www.kaggle.com/datasets/zalando-research/fashionmnist


Repository: https://github.com/kefth/fashion-mnist

We use a ResNet-18 model trained with normalisation and data augmentations (random horizontal/vertical flips, translation, and rotation). Depending on what patterns turn up, we may compare this setup against an unaugmented baseline or focus on specific failure clusters across related clothing types.
