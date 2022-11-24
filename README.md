Github Link: https://github.com/AnnieMo-ZY/CS85-Ai-Guided-Financial-Trading

# CS85-Ai-Financial-Guided-Trading 📈
**Capstone Project**

***Director: Dr. Khushi***

***Tutor: Ling Qi***


1: Codes for finding the trading pattern and trading events are in each member's folder

James Wang - MACD （Columns: dir_change, two_peaks)

Ziying Cen - GRYP (events, absolute_top,absolute_mid, absolute_bottom, ratio_top, ratio_mid
ratio_bottom, R,G,Y)

Yue Wu - Bollinger band (Columns: bb_event1- bb_event8)

Qimin Chen - PSAR (Columns: Trend, Change, Break)

Shen Yan - MA Crossover (Columns: label_15_70...)

Mingyuan Li - SO (Columns: SO1, SO2)


2: In model folder, dataframe.zip contains the combined trading events + ta indicators for all 8 currencies. (use dataframe.zip for modelling, Dataframe.zip have all the required columns for modelling).

3: Model Weight file is store in .h5 format. Use keras.models.load_model to load weights and make predictions to reproduce the results.

4: Code to detect these trading events is in group members' folder under Trade Event folder. (MACD, GRYP，Bolling Band，PSAR，MA，SO)
