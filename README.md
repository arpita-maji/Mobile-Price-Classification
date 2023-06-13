
# Mobile Price Classification using Machine Learning Techniques
Mobile price classification is a common task in the field of machine learning where the goal is to build a predictive model that can classify mobile phones into different price ranges based on their features and specifications. The classification model aims to automate the process of determining the price category of a mobile phone, which can be useful for both consumers and sellers in making informed decisions. It provides valuable insights for consumers, helping them compare and make decisions based on estimated price ranges. For sellers, these models assist in determining competitive pricing strategies and understanding market dynamics.

## Dataset
The dataset was initially retrieved from Kaggle under the title "Mobile Price Classification". A [link](https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification) to the dataset is provided, and it is also provided into the repository. The dataset consists of a nearly 2000 data entries of mobile phone features (RAM, size, etc.), specifications etc and their price range. The various features and information with each combination of those will result in different price range  can be used to predict the price range of a mobile phone.

### Features: 
The data features are as follows:
1. battery_power: Total energy a battery can store in one time measured in mAh.
2. blue: Has bluetooth or not.
3. clock_speed: speed at which microprocessor executes instructions.
4. dual_sim: Has dual sim support or not.
5. fc: Front Camera mega pixels.
6. four_g: Has 4G or not.
7. int_memory: Internal Memory in Gigabytes.
8. m_dep: Mobile Depth in cm.
9. mobile_wt: Weight of mobile phone.
10. n_cores: Number of cores of processor.
11. pc: Primary Camera mega pixels.
12. px_height: Pixel Resolution Height.
13. px_width: Pixel Resolution Width.
14. ram: Random Access Memory in Mega Bytes.
15. sc_h: Screen Height of mobile in cm.
16. sc_w: Screen Width of mobile in cm.
17. talk_time: longest time that a single battery charge will last when you are.
18. three_g: Has 3G or not.
19. touch_screen: Has touch screen or not.
20. wifi: Has wifi or not.
21. price_range: This is the target variable with value of 0 (low cost), 1(medium cost), 2 (high cost) and 3 (very high cost).

## Methodology
1. Remove handle null values (if any).
2. Split data into training and test data.
3. Apply the following models on the training dataset and generate the predicted value for the test dataset:
    -  Logistic Regression.
    -  KNN Classification.
    -  SVM Classifier with linear and rbf kernel.
    -  Decision Tree Classifier.
    -  Random Forest Classifier.
4. Predict the price range for test data.
5. Compute Confusion matrix and classification report for each of these models.
6. Report the model with the best accuracy.