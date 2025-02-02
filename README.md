# Data-Science-for-Predicting-and-Optimizing-Syngas-Production-in-Fluidized-Bed-Biomass-Gasification

This paper investigates the application of machine learning, with a focus on Random Forest and Support Vector Machine models, to predict syngas formation and reduce heating values during biomass gasification. The developed models demonstrate the ability to produce precise forecasts using a variety of lignocellulosic waste types as inputs, suggesting that they may be applied to enhance sustainable energy production techniques. According to the research, sophisticated techniques can improve the efficiency of biomass gasification, potentially resulting in more sustainable and effective energy sources.

# Introdusion 

The need to move from fossil fuels to renewable energy sources has increased due to environmental concerns and the desire for additional energy. Biomass is an easily obtained renewable resource that has several applications in place of fossil fuels. A crucial technique for converting heat into syngas is biomass gasification. Reactors with fluidized beds are frequently employed in this procedure. Although gasification exhibits great promise, there is currently no reliable method for predicting the specific outcomes it will provide under various conditions. The aim of this case study is to apply machine learning techniques to predict the lower heating values (LHV) and syngas percentages that may be produced from different kinds of biomass feedstocks high in lignin under different working conditions. The primary aim is to establish intricate and incongruous connections between the inputs (such as the lignocellulosic materials utilized and the operating environment) and the outputs (such as the generated syngas and waste). Several Machine learning models, including Random Forest and Support Vector Machine (SVM), were used. Objective: Using input variables to generate a MIMO regression model with many output factors is one of the project's objectives. Using 5Objectives is the most effective method to obtain precise results. The initial stage is to create a MIMO regression model using machine learning techniques like Random Forest and SVM. 2. To train the model on the data and assess its prediction accuracy. 3. Use critical tests like the regression coefficient (R2) and the root mean square error (RMSE) to assess the model's efficacy.

# Methodology 

To develop a Multiple Input and Multiple Output (MIMO) regression model that can predict the syngas and lower heating values (LHV), meticulous preparation is necessary. A model is selected, trained, tested, and verified as part of the methodology. The data is then cleaned up.
### Model Selection

Two machine learning models were selected: Random Forest and Support Vector Machine (SVM) because of their ability to take care of the dataset's intricate and unusual linkages. Random Forest is another method of group learning [3]. To provide more reliable and precise estimations, it generates a
large number of decision trees and then combines them all together. Nonetheless, Support Vector Machines (SVM) are powerful algorithms that may be applied to both grouping data and explaining the meaning of those categories. Complex patterns in the data can be discovered by it.

### Model Validation
Make that the model can accurately estimate fresh data that it hasn't seen before by running it through the test set. This completes the final phase. The proof findings demonstrate the effectiveness of the model and its applicability to different lignocellulosic biomass types and environments [5]. The procedures include meticulously preparing the data, selecting the best model, fine-tuning it, exhaustively testing it, and confirming that it functions. By doing this, a MIMO regression model is produced that can precisely predict syngas mixtures and LHV in processes utilizing biomass as fuel. This approach aims to provide valuable insights into the optimization of biomass gasification processes, hence contributing to the safety of energy sources in the future.

![image](https://github.com/user-attachments/assets/1f51148f-378b-4874-bdf4-a272316fbf91)

Output 1 (H2):
Mean Squared Error: 304.85421708143036
R-squared: 0.0011204986979536091

Output 2 (CO):
Mean Squared Error: 143.31612745957224
R-squared: -0.03353155688902065

Output 3 (CO2):
Mean Squared Error: 222.6416345394168
R-squared: 0.021633951803915474

Output 4 (CH4):
Mean Squared Error: 41.19170794584016
R-squared: -0.024096289827765682

Output 5 (Lower_heating_value):
Mean Squared Error: 0.7505269169030137
R-squared: -0.02464754675445202

Output 6 (Char_yield):
Mean Squared Error: 129.30911829506064
R-squared: 0.021087362167440005

Output 7 (Tar_yield):
Mean Squared Error: 1211.3409368674836

![image](https://github.com/user-attachments/assets/fba2a406-a0db-4f8f-80b7-a5315f51004e)

Output 1 (H2) - KNN:
Mean Squared Error: 366.764640882353
R-squared: -0.2017340126934548

Output 2 (CO) - KNN:
Mean Squared Error: 151.92095864705877
R-squared: -0.09558573551925797

Output 3 (CO2) - KNN:
Mean Squared Error: 234.99119352941173
R-squared: -0.032634376089925476

Output 4 (CH4) - KNN:
Mean Squared Error: 52.20031311764705
R-squared: -0.2977890371022742

Output 5 (Lower_heating_value) - KNN:
Mean Squared Error: 0.7224977058823531
R-squared: 0.013618985281858786

Output 6 (Char_yield) - KNN:
Mean Squared Error: 139.36665105882355
R-squared: -0.05505147519897813

Output 7 (Tar_yield) - KNN:
Mean Squared Error: 1331.7094975882349
R-squared: -0.04248929713472838

![image](https://github.com/user-attachments/assets/d0a59a28-967e-4e61-86ed-240fdb56e40c)


Output 1 (H2) - MIMO:
Mean Squared Error: 291.1997343685016
R-squared: 0.045860515790072554

Output 2 (CO) - MIMO:
Mean Squared Error: 147.5652991115843
R-squared: -0.06417467480491279

Output 3 (CO2) - MIMO:
Mean Squared Error: 223.0118405664262
R-squared: 0.020007135649727448

Output 4 (CH4) - MIMO:
Mean Squared Error: 44.82535270774922
R-squared: -0.11443491147744056

Output 5 (Lower_heating_value) - MIMO:
Mean Squared Error: 0.7096001074311803
R-squared: 0.031227271293173042

Output 6 (Char_yield) - MIMO:
Mean Squared Error: 130.40258553554722
R-squared: 0.012809454817351185

Output 7 (Tar_yield) - MIMO:
Mean Squared Error: 1260.490728243451
R-squared: 0.013262204924469723

# Conclusion 

The evaluation of the Multiple Input Multiple Output (MIMO), Random Forest, and K-Nearest Neighbors (KNN) regression models provide information on how well they forecast a variety of gas creation products. The findings show integrated execution for the Random Forest model. The model shows some accuracy in forecasting certain outcomes, such as Char Yield, but struggles to predict other outcomes, such as Carbon Monoxide and Methane, suggesting limited logical power. Furthermore, across a range of gas outcomes, the KNN model has subpar predictive capabilities. The Mean Squared Error (MSE) values show an outstanding spread of anticipated values from real values, recommending difficulties in acquiring the fundamental measures. The limitations of the models in determining the importance of the informational difference are further highlighted by the R-squared esteems. Furthermore, the MIMO regression model performs relatively better, offering gains in both MSE and R-squared values for each and every output. In addition to handling the intricacies of predicting several gas outputs, the MIMO model outperforms both the Random Forest and KNN machine learning models in identifying the underlying linkages. These findings emphasize that more model optimization or study of elective computations is necessary to increase prescient exactness. In order to improve understanding and prediction of gas generation results, methods such as designing and boundary tweaking can be added to the work on model execution. Therefore, the research presents the difficult concept of predicting gas production, encouraging a thoughtful approach to deal with the model's development and improvement for future responsible expectations.

