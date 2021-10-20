# Sleep-Prediction

Background -

In our previous assignment we built a model that could classify sleep stages based on a number of time series features. The next stage is to create a model that will take a look at this same sleep stage data and allow us to forecast how a subject’s sleep cycle will look in the immediate future.

Motivations for Building this Forecasting Model and Tracking Sleep Patterns in General-

The Institute of Medicine (US) Committee on Sleep Research estimates that between 50 and 70 million Americans have trouble with the duration and the quality of their sleep. They have found that the negative effects of this are even more impactful when the poor quality sleep and/or inadequate sleep duration takes place on a chronic, daily basis, rather than on occasion[1].

There are a whole host of detrimental physical effects that are causally associated with poor quality sleep and sleep deprivation. Palagini et al[2] showed how sleep loss can lead to high blood pressure/hypertension. Meier-Ewert et al[3] did similar for cardiovascular risk, showing a clear risk increase with chronic sleep loss.

The negative effects aren’t just physical, Strine and Chapman[4] found that poor sleep quality also has severe negative effects on mental health and wellbeing. Peterman et al[5] also showed a link between sleep disorders and increases in anxiety and depression.

Some Novel Uses that We have come up with for why You may want to be able to Forecast Sleep Stages

If someone has a tendency to sleepwalk, it may be useful to be able to have some kind of alert system that will activate before this person is likely to start. This sleepwalking happens in the non-rem sleep stages[6] and so it may be useful, for the parents of a child for example, to forecast when their child is likely to enter this stage.

While battery life in these smart watches has gotten a lot better over recent years, they could of course still die during a night’s sleep. If this happened and we only had a portion of the night’s sleep data a good forecasting model may be able to fill in the rest of the night with a useful degree of accuracy so the subject can still have some idea of how the sleep went.

Similarly, if something out of the ordinary happened during a given night and interupted your sleep, you may want to compare the true sleep data for the night with a forecast version that ignores where you unexpectedly woke up and instead fills in the remaining hours based on the previous undisturbed.

If the model was trained on data that included all of the awake hours from the day before the sleep, it would be theoretically possible to forecast how many good quality hours sleep you may get based on when you go to sleep that night. This could help influence decisions on when you should go to bed on a given day to try to ensure you get adequate sleep duration and quality.

[Link to Jupyter Book web page](https://weldonj.github.io/CA4015_Assignment_3/Intro_and_Desc_of_Data.html) detailing our further use of wearable sensor data to predict future sleep stages.
