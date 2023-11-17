# Final-Year-Project-4th-Year
INVESTIGATING THE PERFORMANCE OF DIFFERENT MACHINE LEARNING MODELS PREDICTING PARTICULATE MATTER IN DUBLIN

Air-pollution has been identified as the largest environmental risk to public health.
Fine particulate matter with a diameter of less than 2.5 microns (PM2.5), is the air pollutant associated with the most respiratory diseases. Levels of PM2.5 have been linked
to ambient weather conditions such as temperature, relative humidity, mean sea level
pressure and wind speed. Studies have attempted to use machine learning to predict
PM2.5 levels with varying levels of success, often using these meteorological variables
as predictors. In Ireland, there is less PM2.5 data available than other many other
countries. Which machine learning models are most effective for predicting PM2.5
levels will change based on the available data. In this paper, the available features are
analysed and the Random Forest, Deep Learning, Gradient Boosted Trees and Gated
Recurrent Units machine learning models are implemented using meteorological data
as features. The models are all trained based on stations in Dublin city. The ability of
each model to predict PM2.5 is analysed using three common error metrics,the Mean
Squared Error,the Mean Absolute Error and the Root Mean Squared error. The highest performing model XGBoost had a MAE =3.2, a MSE=18, and a RMSE=4.2, though
there was similar performance between the top performing models.The importance
of each feature was tested through the inbuilt feature importance function of the XGBoost model. The robustness of the top models was tested by seeing how accurately
they could predict PM2.5 in another city in Ireland based on the meteorological data
for that city. The top performing model for predicting in Cork was XGBoost, with an
MAE=4.2, an MSE=31, an RMSE=5.5.
