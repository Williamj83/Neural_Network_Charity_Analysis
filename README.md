# Neural_Network_Charity_Analysis


## Project Overview
The purpose of this analysis is to use create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

- Preprocessing Data for a Neural Network Model
- Compile, Train, and Evaluate the Model
- Optimize the Model

## Results

### Data Preprocessing
- The data was imported, analyzed, and cleaned.

![cleaned_data](https://github.com/Williamj83/Neural_Network_Charity_Analysis/blob/main/Images/clean_data.png)


## Compiling, Training, and Evaluating the Model
- first attempt; 80 neurons in the first layer and 30 in the second

![compile_trained_model1](https://github.com/Williamj83/Neural_Network_Charity_Analysis/blob/main/Images/Model_1.png)

### Performance

![model1_loss_accuracy](https://github.com/Williamj83/Neural_Network_Charity_Analysis/blob/main/Images/model_1_loss.png)

- second attempt, 100 neurons in the first layer, 30 in the second and 10 in third

![compile_trained_model2](https://github.com/Williamj83/Neural_Network_Charity_Analysis/blob/main/Images/Model_2.png)

### Performance

![model2_loss_accuracy](https://github.com/Williamj83/Neural_Network_Charity_Analysis/blob/main/Images/Model_2_loss.png)

- third attempt, 100 neurons in the first layer, 60 in the second layer and 40 in the third layer.

![compile_trained_model3](https://github.com/Williamj83/Neural_Network_Charity_Analysis/blob/main/Images/Model_3.png)

### Performance

![model3_loss_accuracy](https://github.com/Williamj83/Neural_Network_Charity_Analysis/blob/main/Images/Model_3_loss.png)


## Summary
This model was able to reach 79% accuracy rating. Perhaps removing additional uncessary columns would increase that even more.
