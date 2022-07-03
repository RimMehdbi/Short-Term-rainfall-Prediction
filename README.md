# Short-Term-rainfall-Prediction

The objective of this project is to find a data-driven rainfall nowcasting model with a satisfactory predictive ability based solely on data received from rain gauges.
The performance of the following modeling approaches was investigated:
 * A statistical model: <a href= "https://github.com/RimMehdbi/Short-Term-rainfall-Prediction/blob/main/ARIMA_2013.ipynb"> ARIMA </a>.
 * A DL-based model: <a href= "https://github.com/RimMehdbi/Short-Term-rainfall-Prediction/blob/main/LSTM_2013.ipynb">LSTM</a>.
 * A naive model: <a href="https://github.com/RimMehdbi/Short-Term-rainfall-Prediction/blob/main/PersistenceModel_2013.ipynb" >The persistence model </a>.
 
 The models' performance was studied for four hydrological years with different hydrological characteristics. Results can be found in the following notebook: <a href= "https://github.com/RimMehdbi/Short-Term-rainfall-Prediction/blob/main/ResultsAnalysis.ipynb"> Results analysis </a>
 
 The uncertainty of the best performing model, which is LSTM, was quantified using the Monte Carlo Dropout technique as shown in the following notebook: <a href="https://github.com/RimMehdbi/Short-Term-rainfall-Prediction/blob/main/MC_LSTM_HL_2013.ipynb"> LSTM_MC </a>
 
