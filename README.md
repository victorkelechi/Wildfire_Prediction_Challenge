# Wildfire Burnt Area Prediction in Zimbabwe (2014-2016)

## Table of Contents
- [Overview](#overview)
- [Objective](#objective)
- [Data](#data)
- [Model and Approach](#model-and-approach)
- [Results](#results)
- [Future Work and Recommendation](#future-work-and-recommendation)

### Overview
*Each year, thousands of fires blaze across the African continent. Some are natural occurrences, part of a ‘fire cycle’ that can actually benefit some dryland ecosystems. Many are started intentionally, used to clear land or to prepare fields for planting. And some are wildfires, which can rage over large areas and cause huge amounts of damage. Whatever the cause, fires pour vast amounts of CO2 into the atmosphere, along with smoke that degrades air quality for those living downwind.*
*Figuring out the dynamics that influence where and when these fires occur can help us to better understand their effects. And predicting how these dynamics will play out in the future, under different climatic conditions, could prove extremely useful.*

## Objective
*The objective of this project is to create a machine-learning model capable of predicting the burned area in different locations over 2014 to 2016.*

## Data
*Data on burned areas across Zimbabwe for each month since 2001 up to the end of 2013 is provided, along with some additional information (such as rainfall, temperature, land cover etc) that extends into the test period.*
*The region is split into 533 equal areas, centered around the locations provided in the lat/lon columns. The target variable, burn_area, is the percentage of the area that has been burned in a given month. Due to the way it’s measured, there may be some overlap of burned areas for two successive months, and so the total burned area over a time period isn’t necessarily equal to the sum of the ‘burn_area’ figures for all months.*

## Model and Approach
*Using a Support Vector Machine (SVM) model, this project predicts the burnt area percentage based on climatic and environmental variables. The robustness of this algorithm in handling nonlinear relationships makes it outstanding.*
*Building this predictive model, a structured approacch involving data exploration, preprocessing (feature selection,feature scaling), model selection, and evaluation was utilized. The perfomance of the model was evaluated using Root Mean Squared Error (RMSE).*

## Results
*The Support Vector Model (SVM) achieved a Root Mean Squared Error (RMSE) of 0.0962. This low RMSE value demonstrates that the model effectively predicts wildfire burn areas in Zimbabwe with a high degree of accuracy. This performance suggests that the SVM model is well-suited for this type of environmental prediction task, providing reliable insights into burn area dynamics and potential patterns over time.*

## Future Work and Recommendation
*Additional Data Sources: Incorporating more environmental and weather data could enhance accuracy.*

*Alternative Models: Experimenting with other algorithms, such as Random Forest or Gradient Boosting, could yield further improvements.*
