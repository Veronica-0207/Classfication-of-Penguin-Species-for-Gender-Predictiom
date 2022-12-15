# Classfication-of-Penguin-Species-for-Gender-Prediction

In this project, EDA is performed to interpret the dataset and binary classfiers are used to get the accuracy using F1 score performance metrics.

I used Palmer Penguin Dataset for data exploration and visualization. Penguins are a family of 17 to 19 species of birds that live primarily in the southern hemisphere. There are 3 different species of penguins in this dataset, collected from 3 islands in the Palmer Archipelago, Antarctica. The three penguin species are Adelie, Gentoo and Chinstrap. Gentoo penguins are the fastest underwater birds in the world. Kristen Gorman and the Palmer Station, Antarctica LTER, a member of the Long-Term Research Network. The dataset contains 345 penguin specimens divided among three species- Adelie, Gentoo, and Chinstrap, with their anatomical information and distributional records. The objective of this project was first, to identify male and female Adelie Penguins, Chinstrap Penguins and Gentoo Penguins at islands in the Palmer Archipelago near Palmer Station, Antarctica, using classification techniques, cluster the species for gender prediction and to find the data statistics using EDA. The algorithms used are – Logistic regression, Decision tree, Random Forest, Super vector machine, KNN, Naïve bayes.

Attributes:
● species
● island
● culmen_length_mm 
● culmen_depth_mm 
● flipper_length_mm
● body_mass_g 
● sex

Dataset Description :
● Data Dimension/Size: 344 Rows and 7 Columns
● 7 Columns consists of 4 quantitative variables and 3 qualitative variables
● 4 quantitative variables: culmen_length_mm, culmen_depth_mm, flipper_length_mm and body_mass_g
● 3 qualitative variables: species, island and sex
▪ species (Adelie, Chinstrap and Gentoo)
▪ island (Biscoe, Dream and Torgersen)
▪ sex (male and female)

CONCLUSION :

According to the dataset the majority population is held by the female around 51% and male around 49% in that Adelie species is the most common species known in Penguin followed by Gentoo and Chinstrap. 80% of the dataset is trained to predict the 20% of the dataset and the results are validated. Binary classification models such as logistic regression works very well for this dataset.
