# MLPublicPres_DecryptingCrypto
ML2 Public Presentation with Marc Castro, Vincent Rivera, Paolo de Guzman, Colleen Nepomuceno and Sydney Austria

Executive Summary

Bitcoin is one of the most popular digital currencies that has surged in popularity and trading volume in the last few years. We adopted the methodology of Ayala et. al (2021) in combining machine learning with technical analysis to formulate a robust trading strategy to predict prices of bitcoin. We used price per minute data from Binance.com spanning Jan to Sept 2021. The ML model with the lowest prediction error as measured by MAE and MSE is the linear regression model, which worked due to the short time periods (15 minutes). The prediction from the ML model was integrated into the technical analysis signals given by MACD, RSI and EMA. 

Our results show that the ML model improved the net-of-fees returns of TA-only, ML-only and the naïve strategy. It also resulted in the lowest number of trades. We further validated the performance of our model by looking at data from Sept 2021 when bitcoin was in a downtrending market. Our results show that the ML model can limit the losses as it was able to generate the highest net of fees return among the strategies evaluated.
