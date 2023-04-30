# Recognition of character-level sign language using static images 

This repo contains 3 datasets that are used for experiments:
1) asl_alphabet - ASL Alphabet Kaggle dataset - The data consists of 29 folders that correspond to the given classes that are A-Z. The training data set comprises 87,000 and each image is 200x200 pixels. There are 29 classes, that are 26 for the letters A-Z and three for DELETE, NOTHING, and SPACE.
2) massey_dataset - Massey hand gesture dataset - The dataset is a collection of images of ASL Alphabets and numbers. It contains 2515 images with 36 classes each having 70 samples and the class 'T' having 65 samples.
3) archive - Sign language for number Kaggle dataset - The dataset has hand gesture recognition for numbers. It has a total of 10 classes(0-9) each having 1500 images. Therefore, the count of total images in the dataset is 15,000.

This repo contains the code that we have used in our work:

1) `Code1 (LightGBM) - ASL Alphabet.ipynb`
2) `Code1 (LightGBM) - Massey.ipynb`
3) `Code1 (LightGBM) - Sign language for numbers.ipynb`
4) `Code2( Bag of visual words) - ASL Alphabet.ipynb`
5) `Code2( Bag of visual words) - Massey.ipynb`
6) `Code2( Bag of visual words) - Sign language for numbers.ipynb`

The file `graph.ipynb` contains the plots used in our work.

